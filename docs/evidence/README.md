# Evidencia del sistema desplegado

Esta carpeta guarda las pruebas de que el informe describe el sistema que el equipo construyó. Cada afirmación del Capítulo IV sobre repositorios, direcciones y URL sale de un hecho comprobable, y cada requisito v1 se apoya en una prueba automatizada o en un clip grabado.

## Qué contiene

| Archivo | Para qué sirve |
|---|---|
| [deployment-facts.json](deployment-facts.json) | Lista de hechos del despliegue: repositorios, URL, direcciones de contratos, imagen, paquete y proveedor de tasas. Cada hecho vivo trae la regla para comprobarlo contra su fuente. |
| [traceability-matrix.md](traceability-matrix.md) | Matriz de los 21 requisitos v1 con sus pruebas automatizadas, sus clips y su estado. |
| [clips.md](clips.md) | Índice de los clips de la demostración, con enlace y huella sha256 cuando existan. |
| `gate-runs/` | Registro de las ejecuciones de las compuertas A y B. Esta carpeta se crea en un plan posterior de la Fase 7. |

## Hechos pendientes

Tres hechos dependen de un despliegue en vivo y todavía no tienen valor: la URL base de la API, la URL de Swagger UI y el enlace de invitación de Firebase App Distribution. En el archivo de hechos llevan el estado `pending` y el valor `null`, y en los diagramas del Capítulo IV aparecen marcados como pendientes. Nadie los llena con un valor supuesto: se completan cuando el servicio existe y se puede comprobar.

## Regla de datos públicos

Todo lo que entra a esta carpeta es público. Se pueden registrar direcciones de contratos, hashes de transacciones, números de bloque y tiempos medidos. No se registra nunca una llave, una URL que lleve una llave, una contraseña, un token ni un secreto de invitación. Si un dato necesita uno de esos secretos para existir, se describe sin el secreto, por ejemplo "no se publica, la URL lleva una llave".

## Cómo se comprueba

Un verificador en Python, que usa solo la biblioteca estándar, lee estos archivos y los compara con los repositorios hermanos. El verificador vive en el espacio de planificación local del equipo, en `.planning/ops/report-checks/check-evidence.py`, y no forma parte de este repositorio. Cada subcomando imprime una palabra que termina en `-ok` o en `-FAIL` y devuelve 0 o 1.

Modo borrador, que acepta hechos y clips pendientes:

```
python3 -I .planning/ops/report-checks/check-evidence.py facts latifi-report/docs/evidence/deployment-facts.json .
python3 -I .planning/ops/report-checks/check-evidence.py c4 latifi-report/README.md latifi-report/docs/evidence/deployment-facts.json
python3 -I .planning/ops/report-checks/check-evidence.py matrix latifi-report/docs/evidence/traceability-matrix.md .planning/REQUIREMENTS.md .
```

Modo final, que rechaza lo pendiente. Añade `--final` a cada comando y, en la matriz, `--ci` para consultar con `gh` que cada ejecución de CI citada terminó en `success`:

```
python3 -I .planning/ops/report-checks/check-evidence.py facts latifi-report/docs/evidence/deployment-facts.json . --final
python3 -I .planning/ops/report-checks/check-evidence.py c4 latifi-report/README.md latifi-report/docs/evidence/deployment-facts.json --final
python3 -I .planning/ops/report-checks/check-evidence.py matrix latifi-report/docs/evidence/traceability-matrix.md .planning/REQUIREMENTS.md . --final --ci
```

El comando `selftest` corre casos que deben fallar y casos que deben pasar para cada regla, de modo que un resultado verde significa que la comprobación sí puede fallar.

## Cómo la usa la Fase 8

La Fase 8 toma esta carpeta como fuente del informe final: los diagramas de 4.3.1 a 4.3.3 con sus valores reales, la matriz como evidencia de requisitos y los clips como evidencia de la demostración. Antes de entregar, se corren los tres comandos en modo final. Si alguno falla, el informe todavía afirma algo que el sistema no respalda.
