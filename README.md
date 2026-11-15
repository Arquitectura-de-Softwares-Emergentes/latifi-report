<div align="center">

<h3>Universidad Peruana de Ciencias Aplicadas</h3>

<img alt="upc-logo" src="docs/assets/cover/UPC-logo.png" width="100"/><br>

<strong>Ingeniería de Software - 202602</strong><br>
<strong>1ASI0728 - Arquitecturas De Software Emergentes - Virtual</strong><br>
<strong>Sección: 2620-9046</strong><br>
<strong>Profesores:Rojas Malásquez, Royer Edelwer</strong><br>

<br><strong>Informe del Trabajo Final</strong><br><br>

<strong>Startup: LatiFi</strong><br>
<strong>Producto: LatiFi Wallet</strong><br>

### Team Members

| Apellidos y Nombres | Código |
|---|---|
| Angulo Abud Juan Carlos | U202317692 |
| Quiroz Zambrano Fabrizio Javier | U202213406 |
| Burga Loarte Anaely | U202118264 |
| Vilca Valverde Fiorella Angela | U20211e417 |

<strong>16 de septiembre de 2026</strong><br>
</div>
<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---|---|---|---|
| 1.0 | 16/09/2026 | Juan Angulo | Creación del repositorio e inicialización del informe. Redacción del avance de TB1 con los Capítulos I a IV, datos del curso y primer perfil de integrante. |
| 1.1 | 19/09/2026 | Fabrizio Quiroz | Registro de la entrevista 1 del segmento prestatario, User Persona y Empathy Map del prestatario, y estructura inicial de Student Outcome 3. |
| 1.2 | 19/09/2026 | Anaely Burga | Nombres de integrantes, As-Is y To-Be Scenario Mapping, y diagramas de EventStorming, Domain Storytelling, Bounded Context Canvases y Context Map del Capítulo IV. |
| 1.3 | 19/09/2026 | Fiorella Vilca | Entrevista 1 del segmento prestamista, User Persona, User Task Matrix y Empathy Map del prestamista, y perfil de integrante. |
| 1.4 | 19/09/2026 | Juan Angulo | Rediseño de la carátula, revisión de estilo y de cumplimiento del enunciado, entradas de Student Outcome 3, integración de los aportes de Fiorella Vilca, Registro de Versiones y Avance de Conclusiones. |
| 1.5 | 04/10/2026 | Fabrizio Quiroz | Registro de las entrevistas 2 y 3 del segmento prestatario con sus capturas. |
| 1.6 | 08/10/2026 | Juan Angulo | Análisis de entrevistas (2.2.3), System Landscape y Deployment Diagram del Capítulo IV, ajuste a Android como única plataforma móvil, actualización del Avance de Conclusiones, capturas de Collaboration Insights, Anexo de Videos de Exposiciones y foto de Juan Angulo en el perfil de integrante. |
| 1.7 | 04/10/2026 | Fabrizio Quiroz | Style Guidelines (6.1) y Navigation Systems (6.2.5) del Capítulo VI (avance de TP1). |
| 1.8 | 08/10/2026 | Juan Angulo | Labeling Systems, Searching Systems y SEO Tags and Meta Tags (6.2.2 a 6.2.4) del Capítulo VI (avance de TP1). |
| 1.9 | 08/10/2026 | Juan Angulo | Organization Systems (6.2.1) del Capítulo VI (avance de TP1). |
| 2.0 | 08/10/2026 | Anaely Burga | Landing Page Mock-up (6.3.2), con las tres secciones de la landing page (avance de TP1). |
| 2.1 | 08/10/2026 | Anaely Burga | Landing Page Wireframe (6.3.1), con la distribución de las tres secciones de la landing page (avance de TP1). |
| 2.2 | 09/10/2026 | Juan Angulo | Capítulo V completo: diseño táctico de los cinco bounded contexts, con diccionario de clases por capa, diagramas de componentes C4, diagramas de clases y esquemas de base de datos. |
| 2.3 | 30/10/2026 | Juan Angulo | Numeración de las secciones 6.3 y 6.4, trazabilidad de cada wireframe y mock-up con las historias de usuario y notas de coherencia con 6.1, 6.2.3 y A11Y.md. |
| 2.4 | 30/10/2026 | Juan Angulo | Auditoría del Capítulo V contra ADR-0001 a ADR-0006 y el ABI v0 de eventos: parámetros y tipos de eventos alineados con el ABI, rango de cuotas de 1 a 6, y tablas de la capa de interfaz REST alineadas con el borrador OpenAPI. |
| 2.5 | 30/10/2026 | Juan Angulo | Corrección de alcance del Capítulo VI: Android como única plataforma móvil con iOS como trabajo futuro, inglés (en_US) como idioma por defecto con español (es_419) compatible, y 6.2.5 sin segundo factor ni enlaces profundos desde notificaciones. |
| 2.6 | 30/10/2026 | Juan Angulo | Wireflows de la aplicación móvil (6.4.2) para el prestatario y el prestamista, con el objetivo del usuario, la persona, el diagrama y la explicación de cada flujo, vinculados a los wireframes de 6.4.1 y a las historias de usuario. |
| 2.7 | 30/10/2026 | Juan Angulo | Corrección del escenario To-Be (3.1) sin colateral ni valoración por oráculo: flujo de solicitud, fondeo, pago en cuotas, indexado y reputación, con la moneda local solo como referencia, y un diagrama Mermaid que reemplaza la imagen anterior. US-AUTH-01 pasa a crear o importar una billetera (ADR-0001) y TS-API-03 incluye `LoanRequested` (ADR-0002). |
| 2.8 | 30/10/2026 | Juan Angulo | Swift y iOS reformulados como trabajo futuro en 1.2, 4.1 y 4.2, con Android como única plataforma que construye el equipo. |
| 2.9 | 30/10/2026 | Juan Angulo | Numeración de la arquitectura de software del Capítulo IV como 4.3, 4.3.1, 4.3.2 y 4.3.3, según el enunciado, y confirmación de 2.2.3 (análisis de entrevistas), 4.3.1 y el diagrama de despliegue agregado en la versión 1.6. |
| 3.0 | 30/10/2026 | Juan Angulo | Reparación de la tabla de contenido: sección 4.3 y sus subsecciones agregadas, todas las secciones numeradas listadas hasta tres niveles (Capítulo V hasta 5.X) y niveles de encabezado de 6.1.1 y 6.1.2 normalizados. Versión del avance TP1. |
| 3.1 | 12/11/2026 | Juan Angulo | Alineación de los diagramas C4 de 4.3.1 a 4.3.3 con el sistema construido (billetera externa con Reown, indexador embebido, GitHub Pages, Dokploy, GHCR y Firebase App Distribution), tabla de despliegue y carpeta docs/evidence con los hechos verificados. |
| 3.2 | 15/11/2026 | Juan Angulo | Integración de la rama `main` en `develop`: borrador de 6.4.3 a 6.5 y del Capítulo VII de Fabrizio Quiroz, con la numeración 6.4.1 a 6.4.4. |
| 3.3 | 15/11/2026 | Juan Angulo | Wireframes de la aplicación (6.4.1, 45 pantallas de Anaely Burga), wireflows rehechos sobre esos wireframes (6.4.2) y mock-ups del diseño final (6.4.3, 38 pantallas). |
| 3.4 | 15/11/2026 | Juan Angulo | Prototipo en modo Demo (6.5), evidencia de despliegue de los cuatro productos (7.2.1.7), analíticos de colaboración del Sprint 1 (7.2.1.8), introducción de 7.3, URL de la API y de Swagger en los diagramas C4, conclusiones del Sprint 1 y Anexo A con la entrega TB2. |
| 3.5 | 15/11/2026 | Juan Angulo | Student Outcome de TB2 de Juan Angulo, capturas del historial de commits de los cinco repositorios y corrección del número de tareas del Sprint Backlog 1. |

# Project Report Collaboration Insights

URL del repositorio: https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-report

El Project Report se redacta en Markdown, con `README.md` como archivo principal, dentro de un repositorio público de la organización del equipo en GitHub. El equipo aplica GitFlow: `develop` concentra la integración del informe, `main` recibe las versiones entregables y cada integrante avanza sus secciones en ramas propias que se integran mediante pull requests. Los mensajes de commit siguen la convención Conventional Commits, y el PDF de cada entrega se genera a partir de este repositorio.

**TB1.** Juan Angulo redactó el avance de los Capítulos I a IV y mantiene el flujo de ramas. Fabrizio Quiroz registró las entrevistas 1, 2 y 3 del segmento prestatario y elaboró su User Persona y su Empathy Map. Anaely Burga elaboró los As-Is y To-Be Scenario Mapping y los diagramas de dominio del Capítulo IV. Fiorella Vilca registró la entrevista del segmento prestamista y elaboró su User Persona, el User Task Matrix y el Empathy Map correspondiente. Cada aporte queda registrado por commit y es coherente con el Registro de Versiones.

**TP1.** Fabrizio Quiroz redactó las Style Guidelines (6.1) y los Navigation Systems (6.2.5). Juan Angulo elaboró el Capítulo V completo y los Organization Systems, Labeling Systems, Searching Systems y SEO Tags and Meta Tags (6.2.1 a 6.2.4). Anaely Burga elaboró el Wireframe y el Mock-up de la landing page (6.3). Cada aporte queda registrado por commit y es coherente con el Registro de Versiones.

**TB2.** Juan Angulo desarrolló la aplicación Android y sus pruebas automatizadas, implementó la landing page, LatiFi API y los smart contracts, y desplegó los cuatro productos (7.2.1). Anaely Burga elaboró los 45 wireframes de la aplicación (6.4.1). Fabrizio Quiroz redactó el borrador de los user flows (6.4.4), del prototipo (6.5) y del Capítulo VII. Fiorella Vilca mantuvo el perfil del equipo en el repositorio del informe. El historial de commits de cada repositorio, en 7.2.1.8, respalda estos aportes.

Las capturas siguientes muestran los analíticos del repositorio del informe en GitHub al 8 de octubre de 2026. En ellas aparecen los cuatro integrantes del equipo como contribuidores: Sve-nnN (Juan Angulo), Relycloud (Fabrizio Quiroz), userxx1000 (Anaely Burga) y fiore-prac (Fiorella Vilca).

![Analítico de contribuidores del repositorio del informe](resources/Annexes/collab-contributors.png)

![Historial de commits de la rama main](resources/Annexes/collab-commits.png)

![Network graph con las ramas main y develop](resources/Annexes/collab-network.png)

<div style="page-break-after: always;"></div>

# Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
    - [Segmento 1: Prestatario, Emprendedor o Independiente No Bancarizado (segmento principal)](#segmento-1-prestatario-emprendedor-o-independiente-no-bancarizado-segmento-principal)
    - [Segmento 2: Prestamista, Persona con Capital Ocioso (segmento secundario, lado de la oferta)](#segmento-2-prestamista-persona-con-capital-ocioso-segmento-secundario-lado-de-la-oferta)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [Carriles de Arquitectura / Capas (Swimlanes / Bounded Context Layers)](#carriles-de-arquitectura--capas-swimlanes--bounded-context-layers)
    - [Descripción Secuencial del Flujo (TO-BE Steps)](#descripción-secuencial-del-flujo-to-be-steps)
    - [Ventajas Clave / Mejora frente al AS-IS (Value Proposition)](#ventajas-clave--mejora-frente-al-as-is-value-proposition)
    - [Tabla Comparativa Resumen: AS-IS vs. TO-BE](#tabla-comparativa-resumen-as-is-vs-to-be)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [Design Purpose](#design-purpose)
    - [Attribute-Driven Design Inputs](#attribute-driven-design-inputs)
    - [Architectural Design Decisions](#architectural-design-decisions)
    - [Quality Attribute Scenario Refinements](#quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [Bounded Contexts](#bounded-contexts)
    - [EventStorming](#eventstorming)
    - [Candidate Context Discovery](#candidate-context-discovery)
    - [Domain Message Flows Modeling](#domain-message-flows-modeling)
    - [Bounded Context Canvases](#bounded-context-canvases)
    - [Context Mapping](#context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape and Context Level Diagrams](#431-software-architecture-system-landscape-and-context-level-diagrams)
    - [4.3.2. Software Architecture Container Level Diagrams](#432-software-architecture-container-level-diagrams)
    - [4.3.3. Software Architecture Deployment Diagrams](#433-software-architecture-deployment-diagrams)
- [Capítulo V: Tactical-Level Software Design](#capítulo-v-tactical-level-software-design)
  - [5.1. Bounded Context: Lending](#51-bounded-context-lending)
  - [5.2. Bounded Context: Identity/Wallet](#52-bounded-context-identitywallet)
  - [5.3. Bounded Context: Reputation](#53-bounded-context-reputation)
  - [5.4. Bounded Context: Exchange Rate](#54-bounded-context-exchange-rate)
  - [5.5. Bounded Context: Marketing/Landing](#55-bounded-context-marketinglanding)
- [Capítulo VI: Solution UX Design](#capítulo-vi-solution-ux-design)
  - [6.1. Style Guidelines](#61-style-guidelines)
    - [6.1.1. General Style Guidelines](#611-general-style-guidelines)
    - [6.1.2. Web, Mobile & Devices Style Guidelines](#612-web-mobile--devices-style-guidelines)
  - [6.2. Information Architecture](#62-information-architecture)
    - [6.2.1. Organization Systems](#621-organization-systems)
    - [6.2.2. Labeling Systems](#622-labeling-systems)
    - [6.2.3. Searching Systems](#623-searching-systems)
    - [6.2.4. SEO Tags and Meta Tags](#624-seo-tags-and-meta-tags)
    - [6.2.5. Navigation Systems](#625-navigation-systems)
  - [6.3. Landing Page UI Design](#63-landing-page-ui-design)
    - [6.3.1. Landing Page Wireframe](#631-landing-page-wireframe)
    - [6.3.2. Landing Page Mock-up](#632-landing-page-mock-up)
  - [6.4. Applications UX/UI Design](#64-applications-uxui-design)
    - [6.4.1. Applications Wireframes](#641-applications-wireframes)
    - [6.4.2. Applications Wireflow Diagrams](#642-applications-wireflow-diagrams)
    - [6.4.3. Applications Mock-ups](#643-applications-mock-ups)
    - [6.4.4. Applications User Flow Diagrams](#644-applications-user-flow-diagrams)
  - [6.5. Applications Prototyping](#65-applications-prototyping)
- [Capítulo VII: Product Implementation, Validation & Deployment](#capítulo-vii-product-implementation-validation--deployment)
  - [7.1. Software Configuration Management](#71-software-configuration-management)
    - [7.1.1. Software Development Environment Configuration](#711-software-development-environment-configuration)
    - [7.1.2. Source Code Management](#712-source-code-management)
    - [7.1.3. Source Code Style Guide & Conventions](#713-source-code-style-guide--conventions)
    - [7.1.4. Software Deployment Configuration](#714-software-deployment-configuration)
  - [7.2. Solution Implementation](#72-solution-implementation)
    - [7.2.1. Sprint 1](#721-sprint-1)
      - [7.2.1.1. Sprint Planning 1.](#7211-sprint-planning-1)
      - [7.2.1.2. Sprint Backlog 1.](#7212-sprint-backlog-1)
      - [7.2.1.3. Development Evidence for Sprint Review.](#7213-development-evidence-for-sprint-review)
      - [7.2.1.4. Testing Suite Evidence for Sprint Review.](#7214-testing-suite-evidence-for-sprint-review)
      - [7.2.1.5. Execution Evidence for Sprint Review.](#7215-execution-evidence-for-sprint-review)
      - [7.2.1.6. Services Documentation Evidence for Sprint Review.](#7216-services-documentation-evidence-for-sprint-review)
      - [7.2.1.7. Software Deployment Evidence for Sprint Review.](#7217-software-deployment-evidence-for-sprint-review)
      - [7.2.1.8. Team Collaboration Insights during Sprint.](#7218-team-collaboration-insights-during-sprint)
  - [7.3. Validation Interviews](#73-validation-interviews)
    - [7.3.1. Diseño de Entrevistas](#731-diseño-de-entrevistas)
    - [7.3.2. Registro de Entrevistas](#732-registro-de-entrevistas)
    - [7.3.3. Evaluaciones según heurísticas](#733-evaluaciones-según-heurísticas)
  - [7.4. Video About-the-Product](#74-video-about-the-product)
- [Avance de Conclusiones](#avance-de-conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
  - [Anexo A. Videos de Exposiciones](#anexo-a-videos-de-exposiciones)

<div style="page-break-after: always;"></div>

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 3**

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones                                                                                                                                                                                                                                                                                                                                                               |
|---|---|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.** | Quiroz Zambrano, Fabrizio Javier<br><br>Contribuí a la preparación y exposición oral de la parte correspondiente del proyecto, comunicando de forma clara y objetiva los resultados obtenidos ante un público con distintos niveles de familiaridad con el tema, adaptando el lenguaje técnico según la audiencia.<br><br>Angulo, Juan Carlos<br><br>*Expuse el problema que motiva a LatiFi y la solución que el equipo propone: la dificultad de los emprendedores no bancarizados para acceder a un microcrédito y cómo una billetera con préstamos sobre blockchain reduce esa barrera. Adapté el nivel de detalle técnico al público, usando ejemplos cotidianos con quienes no conocen blockchain y términos más precisos con quienes sí.*<br><br>*TB2: Produje el video About-the-Product de 1:42, dirigido a visitantes de la landing page sin formación técnica. También preparé la exposición del avance con el producto ya funcionando: la aplicación Android, la API con su Swagger y los contratos en Polygon Amoy. Ajusté el contenido a cada oyente: arquitectura y pruebas para la evaluación técnica, y el recorrido del prestatario, con montos en soles, para quien no conoce blockchain.*<br><br>Burga Loarte, Anaely<br><br>*Presenté y defendí de manera síncrona la arquitectura de dominios, el mapeo estratégico y los flujos asíncronos on-chain/off-chain de LatiFi frente al equipo de proyecto, traduciendo diagramas de EventStorming y acoplamientos (U/D ACL, Conformist) a lenguaje de negocio para evaluadores técnicos y de producto.* | Quiroz Zambrano, Fabrizio Javier<br><br> La exposición oral me permitió reforzar mi capacidad de transmitir resultados de forma clara y objetiva a audiencias diversas, ajustando el nivel de detalle técnico según el público.<br><br>Angulo, Juan Carlos<br>*Exponer el problema completo me obligó a explicarlo con claridad y sin rodeos, y a reconocer qué conceptos de blockchain necesitan más contexto según quién escucha. Concluyo que comunicar bien el porqué de la solución es tan importante como describir cómo funciona.*<br><br>*TB2: Hacer el video para alguien sin conocimientos de blockchain me mostró que el producto funcionando explica el valor más rápido que un diagrama: basta ver a un prestatario pedir un préstamo y leer su cuota en soles. Concluyo que una exposición debe seguir el recorrido de cada audiencia y no la estructura interna del sistema.*<br><br>Burga Loarte, Anaely<br>*Sustentar la topología de Bounded Contexts y los flujos cross-boundary permitió alinear la visión táctica/estratégica del equipo, validando que las restricciones Web3 (Polygon Amoy) se comuniquen sin ruido conceptual a perfiles no especializados en blockchain* |
| **Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.** | Quiroz Zambrano, Fabrizio Javier<br><br>Participé en la redacción de secciones del informe, cuidando que el contenido fuera claro, objetivo y comprensible para lectores con diferentes niveles de conocimiento técnico del proyecto.<br><br>Angulo, Juan Carlos<br><br>*Redacté las secciones del informe que me correspondieron: Startup Profile, Solution Profile con el proceso Lean UX, segmentos objetivo, análisis de competidores y diseño de entrevistas. Escribí cada apartado para que lo entienda tanto un lector técnico como uno de negocio, y mantuve el repositorio con GitFlow para que los aportes del equipo queden ordenados y trazables.*<br><br>*TB2: Desarrollé la aplicación Android de LatiFi y sus pruebas automatizadas, y redacté las secciones del informe que documentan ese trabajo: implementación y despliegue del Sprint 1 (7.2.1.7 y 7.2.1.8), wireflows (6.4.2), mock-ups (6.4.3) y prototipo (6.5). Cada URL y cada cifra del informe se puede comprobar. Además integré los aportes de mis compañeros en un solo documento y corregí una cifra mía que no coincidía con el backlog.*<br><br>Burga Loarte, Anaely<br><br>*Redacté y estructuré formalmente en Markdown los apartados del Capítulo IV (arquitectura de dominio, modelado estratégico/táctico, justificación start-with-value de los 5 bounded contexts y especificación de flujos de mensajes), integrando especificaciones técnicas rigurosas legibles por perfiles de ingeniería y stakeholders.* | Quiroz Zambrano, Fabrizio Javier<br><br>La redacción de estas secciones contribuyó a fortalecer mi habilidad de comunicar resultados por escrito de manera clara y objetiva, adaptando el lenguaje a distintos tipos de lector.<br><br>Angulo, Juan Carlos<br>*Redactar mi parte del informe me mostró que un documento técnico funciona cuando cada afirmación se sustenta y el lenguaje se ajusta al lector. Concluyo que una redacción ordenada y consistente facilita que el equipo y los evaluadores sigan el razonamiento del proyecto.*<br><br>*TB2: Redactar la evidencia de despliegue me enseñó a escribir solo lo que puedo comprobar: cada URL y cada cifra del informe sale de una verificación que otra persona puede repetir. Concluyo que un informe técnico gana credibilidad cuando separa con claridad lo que está hecho de lo que sigue pendiente.*<br><br>Burga Loarte, Anaely<br>*La estructuración del documento técnico con rigor formal consolidó la trazabilidad entre los drivers de arquitectura (DR-01) y la modelación de dominios, facilitando la auditoría y replicabilidad del diseño del sistema LatiFi.* |
<div style="page-break-after: always;"></div>

## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

LatiFi es una startup peruana de base tecnológica orientada a cerrar la brecha de acceso al crédito que enfrentan los emprendedores e independientes no bancarizados de la región, mediante una plataforma de microcréditos peer-to-peer (P2P) construida sobre tecnología blockchain. A diferencia de una fintech de crédito tradicional, LatiFi no actúa como intermediario financiero centralizado: conecta directamente a prestamistas con capital ocioso y prestatarios sin historial crediticio formal a través de Smart Contracts desplegados en una red pública, de modo que las condiciones del préstamo (monto, tasa de interés, plazo, liberación de fondos) se ejecutan de forma automática e inmutable, sin que LatiFi custodie el dinero ni las llaves privadas de sus usuarios en ningún momento del proceso.

El producto insignia de LatiFi es LatiFi Wallet, una aplicación móvil nativa que permite a un prestatario publicar una solicitud de préstamo en una stablecoin y a un prestamista revisar esa solicitud junto con la reputación on-chain y off-chain del solicitante antes de decidir si la fondea. La plataforma se completa con LatiFi API, un backend propio que no participa en la lógica de otorgamiento ni cobro del préstamo, ya que esa responsabilidad vive exclusivamente en el Smart Contract, pero que sí gestiona el perfil ligero del usuario, el historial de reputación y la conversión del monto del préstamo a moneda local, de forma que un prestatario que nunca ha usado criptomonedas pueda entender cuánto debe y cuánto le prestan en soles y no solo en una unidad de stablecoin. Un Landing Page institucional explica el modelo de negocio y dirige a ambos segmentos hacia la descarga de la aplicación.

La motivación de LatiFi nace de una observación simple: la banca tradicional evalúa el riesgo de un solicitante a partir de historial crediticio formal, planillas y garantías, lo que excluye por diseño a quien trabaja de manera informal o independiente, aun cuando esa persona pague puntualmente sus compromisos cotidianos. LatiFi reemplaza esa exigencia por un modelo de reputación que combina el comportamiento de repago verificable en la blockchain con señales complementarias registradas en su propio backend, sin exigir colateral bloqueado como sí lo hacen los protocolos DeFi de sobrecolateralización, que por definición excluyen a quien no tiene activos cripto que dejar en garantía.

El alcance de LatiFi en este informe es acotado: se trata del proyecto final del curso SI728 Arquitecturas de Software Emergentes de la UPC, por lo que no existe un modelo de ingresos real ni manejo de dinero efectivo. Todo el flujo de solicitud, fondeo, ejecución del Smart Contract, repago y actualización de reputación se demuestra de principio a fin sobre la testnet Polygon Amoy, utilizando una stablecoin de prueba sin valor monetario real. El objetivo del equipo no es validar la viabilidad comercial de LatiFi como negocio, sino demostrar competencias de arquitectura de software emergente, es decir, Domain-Driven Design estratégico y táctico, diagramas C4, Lean UX y prácticas ágiles, aplicadas a un dominio de producto con problemática real y verificable.

#### 1.1.2. Perfiles de integrantes del equipo

| Miembro                                                                                                                                     | Descripción|
|---------------------------------------------------------------------------------------------------------------------------------------------|---|
| <img src="docs/assets/members/juan-angulo.jpg" alt="Foto de Juan Carlos Angulo" width="110"/><br>**Angulo, Juan Carlos - U202317692**       | Estudiante de Ingeniería de Software en séptimo ciclo. Le apasiona aprender tecnologías nuevas y construir soluciones aplicadas a problemas reales, y en este curso le entusiasma especialmente trabajar con blockchain. |
| <img src="docs/assets/members/fabrizio.jpg" alt="Foto de FabrizioQuiroz" width="110"/><br>**Quiroz Zambrano, Fabrizio Javier - U202213406** | Estudiante de Ingeniería de Software, con interés en el desarrollo de aplicaciones móviles y en arquitectura de software. Contribuye al proyecto en el desarrollo técnico y la documentación del informe. |
| **Burga Loarte, Anaely - U202118264**                                                                                                       | Estudiante de Ingeniería de Software enfocado en la experiencia de usuario y la lógica de negocio en la interfaz. Contribuye en la interfaz de usuario y la coordinación general de la app. |
| **Vilca Valverde, Fiorella Angela - U20211e417**                                                                                            | Estudiante de Ingeniería de Software, con interés en el análisis de datos. Contribuye al proyecto en el desarrollo técnico y la documentación del informe. |

### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática

##### Antecedentes

El acceso al crédito formal en el Perú continúa siendo un privilegio de quien ya está dentro del sistema financiero. Según cifras de inclusión financiera elaboradas a partir de datos del INEI y el BCRP, en el segundo trimestre de 2025 el 61.6% de la población adulta contaba con al menos una cuenta en el sistema financiero (ahorro, sueldo, corriente o plazo fijo), un avance de 2.4 puntos porcentuales respecto al mismo trimestre de 2024 (Gan@Más, 2025). Ese mismo dato, leído en negativo, significa que cerca de cuatro de cada diez peruanos permanece fuera del sistema financiero formal (Gestión/INEI, s.f.), y la brecha se agrava fuertemente por zona geográfica: mientras el 65.5% de la población adulta urbana tiene acceso a una cuenta, en el ámbito rural la cifra cae a 41.8% (Gan@Más, 2025). El Global Findex 2025 del Banco Mundial, que encuestó a más de 145,000 adultos en 141 economías durante 2024, confirma la magnitud del problema a escala global: 1,300 millones de adultos en el mundo aún no tienen una cuenta financiera, aunque el reporte no permite aislar con precisión la cifra específica de no bancarizados para Perú a partir de las fuentes consultadas para este informe (World Bank Global Findex, 2025).

Este vacío de acceso convive con un mercado laboral donde la informalidad es la norma, no la excepción. De acuerdo con la Encuesta Permanente de Empleo Nacional del INEI, entre abril de 2024 y marzo de 2025 el 70.7% de la población ocupada del país tenía un empleo informal (INEI, 2025), y el 45% de los ocupados corresponde a trabajadores independientes o familiares no remunerados, proporción que sube a 50.2% entre las mujeres (INEI, 2025). Dentro del universo empresarial, el desajuste es todavía más marcado: según ComexPerú, en el Perú operan 6.1 millones de micro y pequeñas empresas, el 99.7% del total de empresas del país, de las cuales el 86.8% no está registrada ante la SUNAT (ComexPerú, 2024), lo que las deja, en la práctica, sin historial tributario ni bancario que un evaluador de crédito tradicional pueda revisar. Es precisamente este universo de emprendedores e independientes, con ingresos reales pero sin el papel que un banco exige, el que LatiFi busca atender.

Una población amplia sin acceso al crédito formal, un mercado laboral mayoritariamente informal y una adopción cripto que ya empieza a pesar: sobre esos tres puntos LatiFi construye su propuesta. Perú superó el millón de usuarios de criptomonedas y escaló al puesto 42 del ranking mundial de adopción cripto según el Global Crypto Adoption Index 2024 de Chainalysis, avanzando al puesto 34 en la edición 2025 (Infobae, 2025); el 3.7% de los peruanos ya utiliza criptomonedas (Infobae, 2025), y a nivel regional las stablecoins concentran cerca del 90% del volumen de transacciones cripto, con los usuarios peruanos inclinándose de forma particular hacia stablecoins denominadas en dólares (Forbes Perú, 2026).

##### Aplicación de la técnica 5W + 2H

| Pregunta | Respuesta |
|--|--|
| **Who** <br> (¿Quién?) | Emprendedores e independientes no bancarizados del Perú que necesitan un microcrédito para su actividad económica, y personas con capital ocioso dispuestas a prestarlo bajo un modelo P2P sin intermediario bancario. |
| **What** <br> (¿Qué?) | Ausencia de un mecanismo de crédito accesible para quien no tiene historial crediticio formal ni activos que dejar en garantía, dado que la banca tradicional exige planilla, historial en centrales de riesgo o colateral, y los protocolos DeFi existentes exigen sobrecolateralización que este segmento no puede cumplir. |
| **Where** <br> (¿Dónde?) | Perú, con foco inicial en emprendedores e independientes urbanos y periurbanos que ya cuentan con un teléfono inteligente, dado que la brecha de inclusión financiera es más aguda en zonas rurales (41.8% de acceso a cuenta financiera) que en zonas urbanas (65.5%) (Gan@Más, 2025). |
| **When** <br> (¿Cuándo?) | El problema es estructural y persiste pese a la mejora reciente en indicadores de inclusión financiera: la tasa de informalidad laboral solo cayó poco más de tres puntos porcentuales entre 2022 y 2024-2025 (INEI, 2025), mientras que la adopción de criptoactivos en el país crece de forma acelerada en el mismo periodo (Infobae, 2025). |
| **Why** <br> (¿Por qué?) | Porque el modelo de evaluación crediticia tradicional está diseñado para quien ya tiene historial formal, excluyendo por defecto a quien trabaja de manera independiente o informal aunque cumpla puntualmente sus compromisos de pago, y porque las alternativas DeFi de crédito descentralizado existentes (Aave, Compound) exigen colateral bloqueado que este segmento, por definición, no posee. |
| **How** <br> (¿Cómo?) | A través de una app móvil nativa (LatiFi Wallet) que conecta al prestatario con prestamistas P2P mediante un Smart Contract que ejecuta de forma inmutable el fondeo y el repago del préstamo, respaldado por un modelo de reputación híbrido on-chain/off-chain gestionado por un backend propio (LatiFi API) que también expone el monto del préstamo en moneda local. |
| **How Much** <br> (¿Cuánto?) | El costo de no resolver el problema se traduce en un universo amplio de emprendedores e independientes, el 45% de la población ocupada del país (INEI, 2025), sin acceso a capital de trabajo formal, empujados hacia prestamistas informales o hacia la descapitalización de su propio negocio; a nivel académico, el costo de no resolverlo es no demostrar un flujo Web3 completo y auditable dentro de las 15 semanas del curso. |

##### Problemática

Los emprendedores e independientes no bancarizados del Perú, un segmento que representa cerca del 45% de la población ocupada del país y que en buena parte opera dentro de micro y pequeñas empresas no registradas ante la SUNAT, enfrentan una exclusión estructural del crédito formal, porque los criterios de evaluación bancaria dependen de historial crediticio y planilla que este segmento no posee, mientras que las alternativas de crédito descentralizado (DeFi) existentes exigen sobrecolateralización en criptoactivos que tampoco están a su alcance. El resultado es que un emprendedor con capacidad real de pago, pero sin papel que lo respalde, queda fuera tanto del sistema financiero tradicional como de las soluciones cripto actuales, mientras que del otro lado existen personas con capital ocioso dispuestas a prestarlo de forma directa si contaran con una señal de riesgo confiable y un mecanismo que garantice el cumplimiento de las condiciones pactadas sin depender de la palabra de un desconocido.

##### Puntos más importantes a resolver

> Autenticación no custodial del usuario mediante su propia billetera digital, sin que LatiFi almacene ni gestione las llaves privadas del prestatario o del prestamista.

> Publicación de solicitudes de préstamo por parte del prestatario (monto, tasa de interés, plazo) en una stablecoin, sin exigir colateral bloqueado como condición de acceso.

> Visibilidad de la reputación del solicitante para el prestamista, como sustituto de la central de riesgo bancaria que este segmento no tiene, combinando señales on-chain (historial de repago verificable en el Smart Contract) con señales off-chain (perfil registrado en LatiFi API).

> Ejecución inmutable del fondeo y del repago del préstamo mediante Smart Contract, de modo que ni LatiFi ni ninguna de las partes pueda alterar unilateralmente las condiciones pactadas.

> Actualización automática y gradual de la reputación del prestatario tras cada resultado de préstamo (pagado a tiempo, tardío o incumplido), evitando un esquema binario que no refleje comportamientos de pago parcial.

> Visualización del monto del préstamo y de las cuotas en moneda local además de en stablecoin, para que un usuario sin experiencia previa en criptoactivos comprenda en todo momento cuánto debe o cuánto va a recibir.

> Un onboarding progresivo y en lenguaje simple, sin jerga cripto, dado que el segmento objetivo no tiene por qué tener experiencia previa con billeteras digitales.

##### Objetivos

- Demostrar un flujo completo de microcrédito P2P (solicitud → fondeo → ejecución del Smart Contract → repago → actualización de reputación) ejecutado de principio a fin sobre la testnet Polygon Amoy.
- Sustituir el colateral bloqueado como mecanismo de mitigación de riesgo por un modelo de reputación híbrido on-chain/off-chain, sin recurrir a KYC documental pesado que contradiga la premisa de servir a usuarios no bancarizados.
- Ofrecer a un prestatario sin historial crediticio formal un canal de acceso a capital de trabajo directo, mediado por un Smart Contract y no por una entidad financiera centralizada.
- Ofrecer a un prestamista con capital ocioso una señal de riesgo confiable (reputación) antes de decidir fondear una solicitud, y la garantía de que las condiciones pactadas se ejecutan de forma automática.
- Aplicar de manera consistente las prácticas de arquitectura de software emergente exigidas por el curso (DDD estratégico y táctico, diagramas C4, Lean UX, Scrum) sobre un dominio de problema real y verificable con datos públicos.

##### Restricciones

- El desarrollo se limita a un despliegue sobre la testnet Polygon Amoy; queda fuera de alcance cualquier manejo de dinero real o despliegue en mainnet.
- El modelo de riesgo del MVP se basa exclusivamente en reputación on-chain/off-chain; no se implementa colateral ni garantías bloqueadas, para no diluir la tesis diferenciadora del proyecto ni duplicar la complejidad del Smart Contract.
- LatiFi no ejerce custodia de las llaves privadas de sus usuarios; la autenticación y firma de transacciones se realiza mediante una billetera no custodial (WalletConnect/Metamask SDK equivalente) integrada a la app.
- La aplicación móvil se desarrolla en tecnología nativa y el equipo la construye solo para Android con Kotlin; Swift para iOS queda como trabajo futuro. El enunciado del curso prohíbe explícitamente el uso de frameworks híbridos.
- La lógica de negocio del préstamo (matching, fondeo, repago, default) vive exclusivamente en el Smart Contract; LatiFi API se limita a exponer perfil de usuario, historial de reputación y tasas de cambio, sin duplicar ni re-decidir el estado del préstamo.
- El proceso de verificación de identidad se limita a un registro de perfil ligero (KYC-lite: nombre y contacto) como base mínima de resistencia a ataques Sybil; queda fuera de alcance el KYC documental basado en escaneo de identidad y verificación de vida, por ser desproporcionado para una demo académica y contradictorio con la premisa de servir a usuarios sin documentación formal.
- El backend REST se construye únicamente con los frameworks permitidos por el curso (Spring Boot, ASP.NET Core o NestJS), y el desarrollo debe seguir GitFlow y Conventional Commits para su calificación.

#### 1.2.2. Lean UX Process

El Lean UX Process de Jeff Gothelf y Josh Seiden convierte la problemática descrita en la sección anterior en creencias explícitas (assumptions) sobre el negocio y los usuarios de LatiFi, y esas creencias en hypothesis statements verificables mediante experimentos concretos. El análisis cubre el dominio completo del problema, el microcrédito P2P descentralizado para no bancarizados, y no un segmento por separado, siguiendo el template del curso para una iniciativa nueva (brand new initiative).

##### 1.2.2.1. Lean UX Problem Statements

LatiFi tiene un único Problem Statement, que agrupa a los dos segmentos identificados (prestatarios y prestamistas). El template exigido por el curso para una iniciativa nueva se completa en inglés, tal como aparece en el enunciado del proyecto:

> The current state of **access to microcredit for unbanked entrepreneurs and independent workers in Peru** has focused mainly on **traditional banks that require formal credit history, payroll records, or physical collateral before granting a loan, leaving out anyone who works informally or independently, even when that person reliably meets their day-to-day payment obligations**.
>
> What existing products/services fail to address is **the gap between a large population of creditworthy, hardworking entrepreneurs and independent workers with no formal credit history or collateral to offer, and the credit products available to them, since both traditional banks and existing decentralized (DeFi) lending protocols require documentation or over-collateralization that this segment cannot provide**.
>
> Our product/service will address this gap by **connecting borrowers directly with peer-to-peer lenders through a non-custodial mobile wallet, using a hybrid on-chain/off-chain reputation model instead of collateral, with loan terms funded, disbursed, and repaid automatically and immutably through a Smart Contract**.
>
> Our initial focus will be **unbanked or underbanked entrepreneurs and independent workers in Peru who need short-term working capital, and individuals with idle capital willing to lend it directly on a peer-to-peer basis**.
>
> We'll know we are successful when we see **a complete loan cycle (request, funding, Smart Contract execution, repayment, and reputation update) demonstrated end-to-end on the Polygon Amoy testnet, with borrowers able to understand their loan terms in local currency and lenders able to make a funding decision based on a visible reputation score**.

En español, el mismo Problem Statement dice lo siguiente. Hoy el acceso al microcrédito para emprendedores e independientes no bancarizados en el Perú descansa en bancos tradicionales que exigen historial crediticio formal, planilla o garantías físicas antes de prestar, dejando fuera a cualquiera que trabaje de manera informal o independiente, aun si cumple puntualmente sus obligaciones de pago cotidianas. Lo que el mercado no resuelve es la brecha entre una población amplia de emprendedores e independientes solventes, sin historial crediticio formal ni colateral que ofrecer, y los productos de crédito disponibles para ellos, ya que tanto la banca tradicional como los protocolos DeFi existentes exigen documentación o sobrecolateralización que este segmento no puede cumplir. LatiFi cierra esa brecha conectando directamente a prestatarios con prestamistas P2P a través de una billetera móvil no custodial, usando un modelo de reputación híbrido on-chain/off-chain en lugar de colateral, con condiciones de préstamo fondeadas, desembolsadas y repagadas de forma automática e inmutable mediante un Smart Contract. El foco inicial son emprendedores e independientes no bancarizados o subatendidos del Perú que necesitan capital de trabajo de corto plazo, y personas con capital ocioso dispuestas a prestarlo de forma directa. El éxito se mide en un ciclo completo de préstamo demostrado de punta a punta en la testnet Polygon Amoy, con prestatarios capaces de entender las condiciones de su préstamo en moneda local y prestamistas capaces de decidir el fondeo con base en una reputación visible.

##### 1.2.2.2. Lean UX Assumptions

El curso pide organizar los assumptions en 5 tipos. Cada uno se redacta como una creencia afirmativa, no como la pregunta que la originó.

**Business Assumptions**

- LatiFi puede demostrar de forma creíble, dentro del alcance académico del curso, un modelo de crédito P2P alternativo al de la banca tradicional y al de los protocolos DeFi sobrecolateralizados.
- Un modelo de reputación híbrido on-chain/off-chain es suficiente para mitigar el riesgo de impago sin necesidad de exigir colateral, incluso frente a usuarios sin historial previo en blockchain.
- El equipo cuenta con las capacidades técnicas (Solidity, desarrollo móvil nativo, arquitectura de backend REST) necesarias para construir el flujo completo sin depender de un tercero crítico fuera del curso.
- Separar la lógica de préstamo (en el Smart Contract) del backend propio (perfil, reputación, tasas de cambio) es suficiente para cumplir el requisito del curso de tener tanto una solución Web3 no custodial como un RESTful API de elaboración interna.
- Un KYC-lite (nombre y contacto) es suficiente resistencia a ataques Sybil para efectos de la demo, sin necesidad de verificación documental pesada.

**Business Outcome Assumptions**

- El flujo completo de préstamo (solicitud, fondeo, Smart Contract, repago, actualización de reputación) puede ejecutarse de punta a punta en la testnet Polygon Amoy dentro del cronograma de 15 semanas del curso.
- El número de solicitudes de préstamo fondeadas durante la demo aumenta conforme los prestamistas de prueba ganan confianza en la señal de reputación mostrada.
- La cantidad de préstamos que llegan a un ciclo de repago completo (y no solo de fondeo) es suficiente para poblar el modelo de reputación con datos reales antes de la entrega final.
- El equipo logra evidenciar, ante la rúbrica del curso, que la lógica de préstamo vive exclusivamente en el Smart Contract y no fue duplicada en el backend propio.

**User Assumptions**

- El prestatario principal es un emprendedor o independiente no bancarizado, con poca o ninguna experiencia previa con billeteras cripto, que necesita capital de trabajo de corto plazo para su actividad económica.
- El prestamista principal es una persona con algo de capital ocioso, más familiarizada con conceptos financieros o cripto que el prestatario promedio, dispuesta a prestar de forma directa a cambio de un interés y motivada por la señal de reputación antes de decidir.
- La mayoría de la interacción del prestatario ocurre desde el celular, en momentos puntuales (solicitar el préstamo, revisar su reputación, pagar la cuota), no como uso recurrente diario.
- El prestamista revisa el feed de solicitudes de forma más deliberada, comparando reputación, monto e interés antes de fondear, similar a cómo un inversionista evalúa una oportunidad.
- Ninguno de los dos segmentos tiene experiencia previa gestionando una billetera no custodial ni una frase semilla, por lo que ambos requieren un onboarding guiado y en lenguaje simple.

**User Outcome and Benefit Assumptions**

- El prestatario obtiene acceso a capital de trabajo que la banca tradicional le habría negado por falta de historial crediticio formal.
- El prestatario no necesita bloquear ningún activo como garantía, a diferencia de lo que exigiría un protocolo DeFi sobrecolateralizado.
- El prestamista cuenta con una señal de riesgo (reputación) antes de fondear, en lugar de prestar a ciegas a un desconocido.
- Ambos usuarios confían en que las condiciones pactadas (monto, interés, plazo, liberación de fondos) se cumplen automáticamente, sin depender de la buena fe de la otra parte ni de la gestión manual de LatiFi.
- El prestatario entiende en todo momento cuánto debe en su propia moneda local, no solo en una unidad de stablecoin que le resulta ajena.

**Feature Assumptions**

- Una autenticación no custodial mediante billetera digital (WalletConnect/Metamask SDK equivalente) permite que el usuario controle sus propios fondos y firme transacciones sin que LatiFi custodie su llave privada.
- Un módulo de publicación de solicitudes de préstamo (monto, interés, plazo) le da al prestatario un canal directo para expresar su necesidad de capital, sin pasar por la evaluación de un oficial de crédito bancario.
- Un feed de solicitudes que muestra la reputación del solicitante le permite al prestamista decidir a quién fondear con una señal de riesgo visible, replicando el rol de una central de riesgo que este segmento no tiene.
- Un flujo de fondeo ejecutado por el Smart Contract transfiere los fondos del prestamista al prestatario y registra las condiciones de forma inmutable, sin intermediación humana ni margen de alteración posterior.
- Un flujo de repago ejecutado por el Smart Contract libera capital e interés al prestamista de forma automática apenas el prestatario paga, cerrando el ciclo del préstamo sin gestión manual.
- Un motor de reputación híbrido, que combina eventos on-chain del Smart Contract con señales off-chain del perfil en LatiFi API, actualiza el puntaje del prestatario tras cada resultado de préstamo.
- Una pantalla que muestra el monto del préstamo y las cuotas en moneda local, además de en stablecoin, usando la API de tasas de cambio de LatiFi API, permite que el usuario entienda su compromiso de pago sin necesidad de convertir manualmente.

##### 1.2.2.3. Lean UX Hypothesis Statements

Cada Feature Assumption tiene su hypothesis statement correspondiente, siguiendo el template del curso (también en inglés):

> **HS-01: Autenticación no custodial con billetera digital**
> We believe we will achieve **an increase in the number of borrowers and lenders who complete onboarding and remain active in the platform**
> If **unbanked entrepreneurs and idle-capital lenders**
> Attain **full control over their own funds and private keys, without depending on LatiFi as a custodian**
> With **a non-custodial wallet authentication module (WalletConnect/Metamask SDK equivalent) integrated into the mobile app**.
>
> *Creemos que lograremos más prestatarios y prestamistas que completan el onboarding y permanecen activos en la plataforma si los emprendedores no bancarizados y los prestamistas con capital ocioso obtienen control total de sus propios fondos y llaves privadas, sin depender de LatiFi como custodio, con un módulo de autenticación no custodial mediante billetera digital integrado a la app móvil.*

> **HS-02: Publicación de solicitudes de préstamo**
> We believe we will achieve **an increase in the number of loan requests published on the platform**
> If **unbanked entrepreneurs and independent workers**
> Attain **a direct channel to request working capital without going through a bank's credit evaluation process**
> With **a loan request creation module where the borrower specifies amount, interest rate, and term in a stablecoin**.
>
> *Creemos que lograremos más solicitudes de préstamo publicadas en la plataforma si los emprendedores e independientes no bancarizados obtienen un canal directo para solicitar capital de trabajo sin pasar por la evaluación crediticia de un banco, con un módulo de publicación de solicitudes donde el prestatario especifica monto, tasa de interés y plazo en una stablecoin.*

> **HS-03: Feed de prestamistas con reputación visible**
> We believe we will achieve **an increase in the number of loan requests funded per active lender**
> If **lenders with idle capital**
> Attain **a visible, trustworthy risk signal about each borrower before deciding to fund a request**
> With **a lender feed that surfaces each open loan request together with the requester's on-chain/off-chain reputation score**.
>
> *Creemos que lograremos más solicitudes fondeadas por cada prestamista activo si los prestamistas con capital ocioso obtienen una señal de riesgo visible y confiable sobre cada prestatario antes de decidir fondear, con un feed que muestra cada solicitud abierta junto con la reputación on-chain/off-chain del solicitante.*

> **HS-04: Flujo de fondeo vía Smart Contract**
> We believe we will achieve **an increase in lender trust and repeat funding behavior**
> If **lenders**
> Attain **certainty that funds are transferred to the borrower and loan terms are recorded immutably, with no possibility of manual alteration**
> With **a Smart Contract funding flow that escrows and disburses funds automatically once a lender funds a request**.
>
> *Creemos que lograremos mayor confianza del prestamista y más fondeos recurrentes si los prestamistas obtienen certeza de que los fondos se transfieren al prestatario y las condiciones del préstamo quedan registradas de forma inmutable, sin posibilidad de alteración manual, con un flujo de fondeo ejecutado por el Smart Contract que transfiere los fondos automáticamente.*

> **HS-05: Flujo de repago vía Smart Contract**
> We believe we will achieve **an increase in the number of loans that reach a completed repayment cycle**
> If **borrowers and lenders**
> Attain **an automatic release of capital and interest to the lender as soon as the borrower repays, without manual reconciliation**
> With **a Smart Contract repayment flow triggered directly from the borrower's mobile app**.
>
> *Creemos que lograremos más préstamos que llegan a un ciclo de repago completo si prestatarios y prestamistas obtienen la liberación automática de capital e interés al prestamista apenas el prestatario paga, sin conciliación manual, con un flujo de repago ejecutado por el Smart Contract directamente desde la app móvil del prestatario.*

> **HS-06: Motor de reputación híbrido**
> We believe we will achieve **an increase in the accuracy and trustworthiness of the reputation score shown to lenders**
> If **borrowers with little or no prior on-chain history**
> Attain **a reputation score that reflects both their on-chain repayment behavior and off-chain profile signals, instead of relying on wallet activity alone**
> With **a hybrid on-chain/off-chain reputation engine that updates the borrower's score after every loan outcome**.
>
> *Creemos que lograremos una reputación más precisa y confiable para los prestamistas si los prestatarios con poco o ningún historial on-chain previo obtienen un puntaje que refleja tanto su comportamiento de repago on-chain como señales de su perfil off-chain, en lugar de depender solo de su actividad en la billetera, con un motor de reputación híbrido que actualiza el puntaje tras cada resultado de préstamo.*

> **HS-07: Visualización en moneda local**
> We believe we will achieve **an increase in the number of borrowers who understand their loan terms correctly before accepting them**
> If **unbanked borrowers unfamiliar with cryptocurrency units**
> Attain **a clear view of the loan amount and installments in their own local currency, alongside the stablecoin amount**
> With **a local-currency display screen powered by the LatiFi API exchange-rate endpoint**.
>
> *Creemos que lograremos más prestatarios que entienden correctamente las condiciones de su préstamo antes de aceptarlas si los prestatarios no bancarizados, poco familiarizados con unidades cripto, obtienen una vista clara del monto y las cuotas en su propia moneda local junto al monto en stablecoin, con una pantalla de visualización en moneda local alimentada por el endpoint de tasas de cambio de LatiFi API.*

##### 1.2.2.4. Lean UX Canvas

| Elemento | Contenido |
|---|---|
| **1. Business Problem** <br> (Problema de negocio) | Los emprendedores e independientes no bancarizados del Perú, cerca del 45% de la población ocupada del país (INEI, 2025), quedan excluidos tanto del crédito bancario tradicional, que exige historial formal y planilla, como de los protocolos DeFi de crédito descentralizado, que exigen colateral bloqueado que este segmento no posee. |
| **2. Business Outcomes** <br> (Resultados de negocio) | Demostración end-to-end del flujo de préstamo en Polygon Amoy dentro del cronograma del curso; aumento en el número de solicitudes fondeadas y en préstamos que completan su ciclo de repago; evidencia clara de que la lógica de préstamo vive únicamente en el Smart Contract. |
| **3. Users** <br> (Usuarios) | Prestatario: emprendedor o independiente no bancarizado que solicita el microcrédito (usuario principal). Prestamista: persona con capital ocioso que fondea solicitudes P2P (usuario principal del lado de la oferta). |
| **4. User Outcomes & Benefits** <br> (Resultados y beneficios para el usuario) | El prestatario accede a capital de trabajo sin colateral ni historial crediticio formal, y entiende su deuda en moneda local; el prestamista decide con una señal de riesgo visible (reputación) y confía en que el Smart Contract hace cumplir lo pactado sin intermediación humana. |
| **5. Solutions** <br> (Soluciones / Features) | Autenticación no custodial; publicación de solicitudes de préstamo; feed de prestamistas con reputación visible; flujo de fondeo vía Smart Contract; flujo de repago vía Smart Contract; motor de reputación híbrido on-chain/off-chain; visualización en moneda local vía LatiFi API. |
| **6. Hypotheses** <br> (Hipótesis) | HS-01 a HS-07 (ver sección 1.2.2.3), una por cada Feature Assumption identificada. |
| **7. What's the most important thing we need to learn first?** <br> (Lo más importante que aprender primero) | Si un prestamista confía lo suficiente en un puntaje de reputación calculado por un modelo híbrido on-chain/off-chain como para fondear a un desconocido sin colateral de por medio, y si un prestatario sin experiencia previa en cripto logra completar el flujo de autenticación no custodial y de solicitud de préstamo sin abandonar en el camino. |
| **8. What's the least amount of work we can do to learn the next most important thing?** <br> (El experimento mínimo viable) | Un prototipo del ciclo completo billetera → Smart Contract → LatiFi API → app móvil, con una sola stablecoin de prueba en Polygon Amoy, presentado a un grupo reducido de prestatarios y prestamistas simulados (compañeros o usuarios de prueba sin experiencia cripto previa) para validar la confianza en la reputación y la comprensión del monto en moneda local, sin necesidad de desplegar la totalidad de las funcionalidades de v1.x. |

### 1.3. Segmentos objetivo

Los segmentos objetivo de LatiFi se derivan directamente de los User Assumptions definidos en el Lean UX Canvas (ver sección 1.2.2.2): dos roles distintos interactúan con la plataforma desde extremos opuestos del mismo Smart Contract, y a ellos se dirigirá el proceso de Needfinding y la construcción posterior de los User Persona (Capítulo II). Cada segmento se describe a continuación considerando sus características demográficas y la información estadística que sustenta su relevancia dentro del dominio del problema.

#### Segmento 1: Prestatario, Emprendedor o Independiente No Bancarizado (segmento principal)

**Descripción.** Es la persona que solicita el microcrédito a través de LatiFi Wallet para financiar capital de trabajo de su actividad económica (compra de mercadería, insumos, herramientas de trabajo). Trabaja de manera informal o independiente, por lo que no cuenta con planilla ni historial crediticio formal que un banco tradicional pueda evaluar, y tampoco dispone de activos cripto para dejar en garantía en un protocolo DeFi sobrecolateralizado. Publica su solicitud especificando monto, interés y plazo, y su reputación, construida a partir de su historial de repago y de su perfil en LatiFi API, es lo que determina si un prestamista decide fondearlo.

**Características demográficas.** Adultos entre 20 y 55 años, con educación secundaria completa como mínimo y, en muchos casos, sin estudios superiores culminados; ocupación como comerciante ambulante o de mercado, transportista independiente, trabajador de delivery, artesano o microempresario de subsistencia. Se ubican principalmente en zonas urbanas y periurbanas del Perú con acceso a un teléfono inteligente y conexión a internet móvil, dado que sin ese requisito mínimo no pueden acceder a la app; la brecha de inclusión financiera es más severa en el ámbito rural (41.8% de acceso a cuenta financiera) que en el urbano (65.5%) (Gan@Más, 2025), lo que orienta el foco inicial de validación hacia el segundo.

**Información estadística de sustento.** Según la Encuesta Permanente de Empleo Nacional del INEI, entre abril de 2024 y marzo de 2025 el 70.7% de la población ocupada del Perú tenía un empleo informal, y el 45% de los ocupados corresponde a trabajadores independientes o familiares no remunerados, proporción que llega a 50.2% entre las mujeres (INEI, 2025). A nivel empresarial, ComexPerú reporta que el país cuenta con 6.1 millones de micro y pequeñas empresas, el 99.7% del total de empresas del Perú, de las cuales el 86.8% no está registrada ante la SUNAT (ComexPerú, 2024), lo que confirma que el universo de potenciales prestatarios sin historial crediticio formal es amplio y estructural, no una excepción del mercado. A esto se suma que, en el segundo trimestre de 2025, cerca de cuatro de cada diez adultos peruanos permanecía fuera del sistema financiero formal (Gestión/INEI, s.f.; Gan@Más, 2025), lo que evidencia el vacío de acceso al crédito que LatiFi busca cubrir para este segmento.

#### Segmento 2: Prestamista, Persona con Capital Ocioso (segmento secundario, lado de la oferta)

**Descripción.** Es quien revisa el feed de solicitudes de préstamo dentro de LatiFi Wallet y decide fondear una o varias de ellas a cambio de un interés, basándose principalmente en la reputación mostrada del solicitante. A diferencia del prestatario, suele tener mayor familiaridad con conceptos financieros o con criptoactivos, y su motivación combina un componente de retorno económico con un interés genuino en modelos de finanzas descentralizadas o de impacto social sobre población no bancarizada.

**Características demográficas.** Adultos entre 25 y 50 años, con estudios superiores técnicos o universitarios, ocupación formal o independiente con cierta estabilidad de ingresos que le permite disponer de un excedente de capital para prestar; usuarios que ya tienen o están dispuestos a crear una billetera digital no custodial, por lo que su nivel de alfabetización digital y financiera es mayor al del prestatario promedio. Su interacción con la app ocurre de forma más deliberada, revisando el feed de solicitudes desde el celular en momentos puntuales antes de decidir un fondeo.

**Información estadística de sustento.** El universo de potenciales prestamistas se apoya en la adopción cripto ya medible en el país: Perú superó el millón de usuarios de criptomonedas y escaló al puesto 42 del ranking mundial de adopción cripto según el Global Crypto Adoption Index 2024 de Chainalysis, avanzando al puesto 34 en la edición 2025 (Infobae, 2025), y el 3.7% de los peruanos ya utiliza criptomonedas (Infobae, 2025). A nivel regional, las stablecoins concentran cerca del 90% del volumen de transacciones cripto, con los usuarios peruanos mostrando una preferencia particular por stablecoins denominadas en dólares (Forbes Perú, 2026), lo que sustenta que existe ya una base de usuarios familiarizados con este tipo de activo digital y en condiciones de operar como prestamistas dentro de un modelo P2P como el de LatiFi. No se encontró, dentro de las fuentes consultadas para este informe, una cifra pública y verificable que segmente específicamente cuántos de esos usuarios cripto peruanos tendrían capital disponible para prestar en un esquema P2P; ese dato deberá explorarse durante el proceso de Needfinding del Capítulo II mediante entrevistas directas.

Estos dos segmentos son la base sobre la que se construirán, en el Capítulo II, los User Persona, el User Task Matrix, los User Journey Map y los Empathy Map correspondientes.

<div style="page-break-after: always;"></div>

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

El microcrédito P2P descentralizado no es un espacio vacío ni nuevo: desde 2020 existen protocolos DeFi que intentan resolver el mismo problema de fondo que LatiFi, es decir, prestar sin colateral bloqueado a personas o negocios sin historial crediticio bancario tradicional, cada uno con un modelo de riesgo distinto. Se seleccionaron tres competidores que representan los tres enfoques dominantes de underwriting sin colateral pleno en DeFi: Goldfinch (reputación off-chain validada por terceros), RociFi (score on-chain algorítmico) y Aave Credit Delegation (delegación de crédito entre partes de confianza previa). Los tres son competidores indirectos en el sentido estricto, ya que ninguno opera de forma nativa en Perú ni en soles, pero compiten directamente por la misma tesis de producto: sustituir el colateral por una señal de confianza distinta.

#### 2.1.1. Análisis competitivo

**Goldfinch.** Protocolo de crédito privado on-chain fundado en 2020 por Mike Sall y Blake West, ex-empleados de Coinbase, pensado explícitamente para llevar capital cripto a negocios de mercados emergentes sin exigirles colateral cripto que, por definición, no tienen (Gemini, s.f.). Su mecanismo de "trust through consensus" delega la evaluación crediticia en "backers" y "auditors" humanos en vez de en un algoritmo de scoring. El propio protocolo reportó haber colocado más de 100 millones de dólares en préstamos hacia mercados emergentes (Goldfinch Foundation, Medium, s.f.). Sin embargo, en 2026 Goldfinch inició su cierre de operaciones tras un tercer incumplimiento de un prestatario (Lend East), lo que expuso las dificultades reales de dar underwriting a crédito en mercados emergentes solo con verificación humana fuera de cadena (DL News, 2026; BitKE, 2026).

**RociFi.** Protocolo de crédito on-chain lanzado en Polygon en 2022, tras levantar 2.7 millones de dólares en una ronda liderada por inversionistas cripto (CoinDesk, 2022). Su pieza central es el Non-Fungible Credit Score (NFCS), un token ERC-721 que el propio prestatario acuña y que resume su score de 1 (muy confiable) a 10 (no confiable) a partir de actividad on-chain, machine learning y señales de identidad descentralizada (cuentas de Twitter/GitHub, participación en DAOs, tenencia de NFT), permitiendo préstamos en stablecoins con un colateral reducido de hasta el 75% del monto, nunca cero (Mad Devs, s.f.; CryptoTotem, s.f.). Quemar el NFCS para escapar de un mal score implica perder todo el historial acumulado, lo que introduce una consecuencia reputacional real ante el default.

**Aave: Credit Delegation.** Aave, uno de los protocolos de lending DeFi más grandes por liquidez total, ofrece desde su versión 2 una función llamada Credit Delegation: un depositante que ya tiene fondos en el protocolo puede delegar su capacidad de préstamo a una contraparte de confianza, que así puede pedir prestado sin transferir colateral propio (Aave, documentación oficial, s.f.; Messari, s.f.). En 2026 el uso de esta función sigue siendo limitado pero creciente, y la propia hoja de ruta de Aave V4 (arquitectura hub-and-spoke) apunta a ampliar los casos de uso de crédito sin colateral pleno, apostando a que proyectos de identidad descentralizada (Worldcoin, Gitcoin Passport, Polygon ID) terminen de construir la capa de reputación que este modelo necesita (Yellow.com, 2026).

##### Competitive Analysis Landscape

| | LatiFi | Goldfinch | RociFi | Aave (Credit Delegation) |
|---|---|---|---|---|
| **Overview** | dApp + wallet móvil nativa para microcrédito P2P entre no bancarizados de LATAM, sin colateral, con reputación híbrida on-chain/off-chain gestionada por una API propia. | Protocolo de crédito privado on-chain para negocios de mercados emergentes, evaluados por "backers" y "auditors" humanos, sin colateral cripto. | Protocolo de crédito on-chain en Polygon con score algorítmico (NFCS) basado en actividad de wallet e identidad descentralizada, colateral reducido pero no nulo. | Función de un protocolo de lending mayor que permite a un depositante delegar su capacidad de préstamo a una contraparte de confianza previa, sin transferencia de colateral. |
| **Ventaja competitiva** | Modelo híbrido pensado para el "cold start" del usuario sin ninguna huella on-chain previa, con onboarding pensado para no nativos cripto y montos expresados en moneda local. | "Trust through consensus": due diligence humana de nivel casi-inversionista sobre negocios reales en mercados emergentes. | Score cuantitativo, automático y portable (NFT) sin depender de un comité humano; menor fricción que Goldfinch para el prestatario. | Aprovecha la liquidez y reputación ya construidas de uno de los protocolos DeFi más grandes y auditados del mercado. |
| **Mercado objetivo** | Emprendedores e independientes no bancarizados de LATAM sin historial crediticio formal ni actividad cripto previa. | Negocios y fintechs de mercados emergentes (África, Asia, LATAM) con cierto nivel de formalización previa. | Usuarios cripto-nativos con billeteras que ya acumulan actividad on-chain suficiente para ser scoreadas. | Usuarios cripto-nativos que ya tienen una relación de confianza previa y verificable con quien les delega crédito. |
| **Estrategias de marketing** | Proyecto académico: demo funcional sobre testnet, sin estrategia comercial real. | Posicionamiento como infraestructura de "impacto" para banking the unbanked, comunicación dirigida a inversionistas institucionales cripto. | Comunicación técnica dirigida a la comunidad DeFi y a integraciones (Chainlink Ecosystem), no al usuario final no bancarizado. | Comunicación como feature dentro del ecosistema Aave, no como producto independiente; depende de la marca ya construida del protocolo. |
| **Productos & Servicios** | LatiFi Wallet (Kotlin, Android), Smart Contract de préstamo en Solidity sobre Polygon Amoy, LatiFi API (perfil, reputación, tipo de cambio). | Pools de crédito on-chain, gobernanza y staking del token GFI, proceso de due diligence off-chain. | Token NFCS (ERC-721), pools de préstamo en stablecoins con colateral reducido, integración con oráculos Chainlink. | Función de delegación de crédito dentro del protocolo Aave V3/V4, sobre pools de liquidez ya existentes. |
| **Precios & Costos** | No aplica (demo académica sin dinero real). | Retornos e intereses variables según pool; sin tarifa pública fija reportada en las fuentes consultadas. | Colateral mínimo de 75% del monto del préstamo, más tasas de interés variables según nivel de NFCS (a menor score de riesgo, mejores condiciones) (Mad Devs, s.f.). | Costos de gas de la red más la tasa de interés variable del pool de Aave sobre el que se delega; sin tarifa adicional publicada específica para Credit Delegation. |
| **Canales de distribución** | App móvil nativa (Android) + landing institucional. | Interfaz web del protocolo, dirigida a "backers" (inversionistas) y originadores de crédito ("Senior Pools"). | Interfaz web del protocolo, integraciones con wallets y con el ecosistema Chainlink. | Interfaz web/dApp de Aave; requiere ya ser usuario del protocolo. |
| **Fortalezas** | Diseñado desde cero para el "cold start" del usuario no bancarizado; moneda local visible; alineado a un solo modelo de riesgo coherente (reputación, sin colateral). | Track record de haber colocado más de US$100M en préstamos reales a mercados emergentes (Goldfinch Foundation, Medium, s.f.). | Score automatizado y portable, sin depender de un comité humano por cada préstamo; ya integrado a Polygon y Chainlink. | Liquidez y seguridad de uno de los protocolos DeFi más auditados y grandes del mercado. |
| **Debilidades** | Sin trayectoria, sin usuarios reales, sin dinero real (alcance académico sobre testnet). | En 2026 inició su cierre de operaciones tras un tercer default de un prestatario (Lend East), lo que evidenció el riesgo de underwriting solo con verificación humana en mercados emergentes (DL News, 2026). | Su score depende de actividad on-chain previa (Twitter, GitHub, DAOs, NFT), por lo que no resuelve el "cold start" de un usuario genuinamente nuevo en cripto, justo el perfil del no bancarizado. | Requiere una relación de confianza previa ya establecida entre delegante y delegado; no sirve para conectar a dos desconocidos, que es exactamente el escenario P2P que LatiFi busca resolver. |
| **Oportunidades** | Ningún competidor revisado atiende bien al usuario sin ninguna huella on-chain previa ni resuelve el "cold start" combinando señales on-chain y off-chain. | Podría redirigir su infraestructura de due diligence hacia individuos en vez de solo negocios formales. | Podría añadir una capa de señales off-chain (como hace LatiFi) para atender a usuarios sin historial on-chain. | El desarrollo de infraestructura de identidad descentralizada (Worldcoin, Gitcoin Passport, Polygon ID) podría permitirle extender Credit Delegation a partes que no se conocen previamente (Yellow.com, 2026). |
| **Amenazas** | Que el propio caso Goldfinch (tercer default, wind-down) refuerce la percepción de que el crédito sin colateral en mercados emergentes es estructuralmente riesgoso, dificultando la aceptación de cualquier modelo similar, incluido el de LatiFi. | Pérdida de confianza del mercado tras el wind-down, que golpea la credibilidad de todo el modelo de "trust through consensus" frente a alternativas algorítmicas. | Que su dependencia de señales cripto-nativas (Twitter, GitHub, NFT) lo deje fuera de cualquier expansión hacia mercados con baja penetración cripto, como el segmento no bancarizado de LATAM. | Que protocolos nuevos y más simples ataquen directamente el segmento de usuarios sin relación de confianza previa, que Aave hoy no puede atender con Credit Delegation. |

Las cifras de financiamiento, montos colocados y condiciones de colateral de los tres competidores provienen de fuentes públicas (comunicados de los propios protocolos, prensa especializada en cripto y documentación oficial) y deben leerse como señales de mercado, no como estados financieros auditados; se indica la fecha o el contexto de cada cifra cuando la fuente lo permite.

#### 2.1.2. Estrategias y tácticas frente a competidores

Frente a **Goldfinch**, la fortaleza a reconocer es su track record real de más de US$100 millones colocados en mercados emergentes y su modelo de due diligence humana, que genera confianza en el prestamista institucional. Su debilidad, expuesta por su propio wind-down en 2026 tras un tercer default, es que la verificación humana de negocios en mercados emergentes es costosa, lenta y no escala a microcréditos individuales de montos pequeños: Goldfinch nunca fue pensado para prestarle a una persona no bancarizada, sino a negocios y fintechs ya formalizados. LatiFi no compite por replicar ese comité de "backers" y "auditors" para cada préstamo pequeño, lo cual sería inviable operativamente para un microcrédito, sino por automatizar la señal de confianza a través de una reputación híbrida on-chain/off-chain que no depende de que un tercero humano audite cada caso.

Frente a **RociFi**, la fortaleza a reconocer es contar con un score automatizado, portable y ya probado sobre Polygon; la debilidad a explotar es que ese score depende enteramente de actividad on-chain previa (billeteras con historial, cuentas de redes sociales, tenencia de NFT), lo que excluye exactamente al perfil de usuario que LatiFi busca atender: alguien sin ninguna huella cripto previa. La táctica es doble: comunicar con claridad que el modelo de LatiFi resuelve el "cold start" que RociFi no puede resolver, y diseñar el flujo de onboarding de forma que el primer préstamo de un usuario nuevo no dependa de una reputación on-chain que todavía no existe, sino de las señales off-chain capturadas por la LatiFi API.

Frente a **Aave Credit Delegation**, la fortaleza a reconocer es la liquidez, seguridad y reputación de marca de uno de los protocolos DeFi más grandes y auditados. Su debilidad estructural es que Credit Delegation exige una relación de confianza previa entre quien delega el crédito y quien lo recibe, por lo que no conecta a dos desconocidos, que es justamente el escenario P2P que LatiFi habilita entre un prestamista con capital ocioso y un prestatario que nunca conoció antes. La táctica frente a Aave es de posicionamiento más que de competencia directa por usuario: mientras la infraestructura de identidad descentralizada que Aave necesita para extender Credit Delegation a extraños (Worldcoin, Gitcoin Passport, Polygon ID) sigue en construcción, LatiFi puede validar en un entorno académico controlado (testnet, segmento acotado) una versión funcional de ese mismo problema, prestar entre desconocidos sin colateral, a una escala mucho más pequeña pero end-to-end demostrable.

### 2.2. Entrevistas

El presente apartado documenta el proceso de investigación cualitativa dirigido a los segmentos objetivo de LatiFi (prestatarios no bancarizados y prestamistas con capital ocioso), con el propósito de comprender sus necesidades, comportamientos, objetivos y frustraciones frente al microcrédito y al ahorro/inversión informal, antes de diseñar cualquier artefacto de Needfinding. Esta sección presenta el diseño de las entrevistas, es decir, las preguntas aplicadas, y el registro de las entrevistas realizadas a un representante de cada segmento.

#### 2.2.1. Diseño de entrevistas

Se diseñarán entrevistas semiestructuradas dirigidas a dos segmentos:

- **Prestatario no bancarizado:** emprendedor o trabajador independiente sin historial crediticio formal, que hoy financia su actividad con ahorro propio, préstamos informales (familiares, "juntas", prestamistas informales) o no logra financiarse en absoluto.
- **Prestamista con capital ocioso:** persona con algún nivel de alfabetización financiera y/o cripto, dispuesta a prestar montos pequeños a cambio de un interés, hoy canalizando ese capital hacia ahorro bancario tradicional, cripto especulativo o círculos de préstamo informal.

Cada entrevista se orientará primero a entender la situación actual del participante y solo después presentará la propuesta de LatiFi, para no condicionar sus respuestas. Antes de las preguntas específicas se recogerán datos generales del entrevistado (nombre, edad, género, distrito, ocupación, nivel de bancarización y de familiaridad con billeteras digitales/criptomonedas).

**Preguntas principales: Segmento Prestatario no bancarizado**

1. ¿Cómo financia hoy sus gastos o su actividad económica cuando necesita dinero que no tiene disponible?
2. ¿Ha intentado alguna vez acceder a un préstamo formal (banco, financiera, caja)? ¿Qué pasó?
3. ¿A quién le pide dinero prestado hoy (familia, conocidos, prestamista informal, "junta")? ¿Bajo qué condiciones?
4. ¿Qué tan predecibles son sus ingresos mes a mes?
5. ¿Usa algún tipo de billetera digital o aplicación financiera hoy? ¿Cuál y para qué?
6. ¿Qué tan familiarizado está con el concepto de criptomonedas o stablecoins?
7. ¿Qué le preocuparía más de pedir un préstamo a través de una app sin un banco de por medio?
8. Si pudiera demostrar que "es de fiar" sin tener historial bancario, ¿cómo cree que podría demostrarlo?

**Preguntas principales: Segmento Prestamista con capital ocioso**

1. ¿Qué hace hoy con el dinero que no necesita usar de inmediato (ahorro, inversión, cripto, nada)?
2. ¿Alguna vez ha prestado dinero a alguien fuera de su círculo cercano a cambio de un interés? ¿Cómo le fue?
3. ¿Qué tan cómodo se siente usando billeteras digitales o aplicaciones cripto?
4. ¿Qué información necesitaría ver de un desconocido antes de decidir prestarle dinero?
5. ¿Qué nivel de riesgo de no pago estaría dispuesto a aceptar a cambio de qué tasa de interés?
6. ¿Qué le generaría más desconfianza en una plataforma de préstamos entre desconocidos sin banco de por medio?
7. ¿Preferiría que existiera algún tipo de garantía o colateral, o le basta con una reputación verificable del prestatario?

**Preguntas complementarias (ambos segmentos)**

- ¿Puede describir la última vez que tuvo un problema de dinero relacionado con esto? ¿Qué hizo?
- ¿Qué tendría que pasar para que confiara en una aplicación nueva para este propósito?
- ¿Qué es lo que más valoraría de una solución así, y qué es lo que la haría descartarla de inmediato?

#### 2.2.2. Registro de entrevistas

##### Tabla resumen de entrevistas: segmento Prestatario no bancarizado

| # | Entrevistado | Edad | Ocupación             | Bancarización | Fecha     | Video |
|---|---|---|-----------------------|---|-----------|---|
| 1 | Joseph Falcón | 21 | Ingeniero de Software | Cuenta bancaria, crédito limitado | 18/09/2026 | [Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213406_upc_edu_pe/IQCHK_iltITcS6NM7HjVMQ2YAbWi4_rouRZw5XHK93iajko?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=J79Rt5) |
| 2 | Rafael Chui | 24 | Repartidor independiente (delivery) | Cuenta de ahorros en caja, crédito limitado | 4/10/2026 | [Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213406_upc_edu_pe/IQAV70dTUnwjTb6dBn95hr5iAXZVc30kSbCMiMb09Yx5PSQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=I2NLfL) |
| 3 | Gonzalo Contreras | 22 | Comerciante de mercado | Sin cuenta bancaria, solo Yape | 4/10/2026  | [Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213406_upc_edu_pe/IQC0ybY5Ls4pQ6Qw5eC4GupXAWf9-JjDwupdcTAFsZYLOjQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=iv4HO3) |
---

##### Entrevista 1: Joseph Falcón

**Ficha del entrevistado**

| Campo | Detalle                                                                                                |
|---|--------------------------------------------------------------------------------------------------------|
| Nombre | Joseph Falcón                                                                                          |
| Edad | 21 años                                                                                                |
| Distrito | Villa Maria del Triunfo                                                                                |
| Ocupación | Ingeniero de Software                                                                                   |
| Nivel de bancarización | Cuenta de ahorros en banco; acceso limitado a crédito formal (montos bajos, tasas altas)               |
| Familiaridad con billeteras digitales/cripto | Baja: usa app de su banco y Yape, sin experiencia en criptomonedas                                    |
| Video | [Ver grabación](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213406_upc_edu_pe/IQCHK_iltITcS6NM7HjVMQ2YAbWi4_rouRZw5XHK93iajko?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=J79Rt5) |

**Screenshot de la entrevista**

![Entrevista Joseph Falcón](resources/Cap1/Interviews-Caps/JosephInterview.png)

**Resumen**

Joseph financia sus gastos principalmente con ahorros propios y, cuando necesita un monto mayor, recurre a un préstamo bancario, aunque señala que el banco le otorga montos bajos y tasas altas por no contar con boletas de pago formales. Cuando el banco demora en aprobar una solicitud, recurre a préstamos familiares o a una junta con otros vendedores. Sus ingresos son variables según la temporada. Usa la app de su banco para pagar el préstamo y Yape para cobrar a sus clientes, pero tiene poca o ninguna familiaridad con criptomonedas o stablecoins. Le preocupa que una app sin banco de por medio no sea tan clara como su banco actual respecto a las condiciones del préstamo, y considera que podría demostrar ser "de fiar" mostrando que paga su préstamo bancario a tiempo o mediante referencias de su entorno de trabajo. Valoraría una solución más rápida que el banco y con montos ajustados a lo que realmente vende, pero la descartaría si la percibe menos segura o menos transparente que su banco.

**Transcripción completa**

| # | Pregunta | Respuesta |
|---|---|---|
| 1 | ¿Cómo financia hoy sus gastos o su actividad económica cuando necesita dinero que no tiene disponible? | "Si es poco, uso mis ahorros. Si necesito más, a veces saco un préstamo en mi banco, aunque no siempre me dan el monto que pido." |
| 2 | ¿Ha intentado alguna vez acceder a un préstamo formal (banco, financiera, caja)? ¿Qué pasó? | "Sí, tengo cuenta de ahorros en el banco y una vez pedí un préstamo, pero me lo dieron con un monto bajo y una tasa alta porque no tengo boletas de pago, solo mis ventas." |
| 3 | ¿A quién le pide dinero prestado hoy (familia, conocidos, prestamista informal, "junta")? ¿Bajo qué condiciones? | "Primero intento con el banco, pero si no me alcanza o me demoran, le pido a mi familia o entro a una junta con otras vendedoras." |
| 4 | ¿Qué tan predecibles son sus ingresos mes a mes? | "Varían harto, hay semanas buenas y otras flojas, depende de la temporada." |
| 5 | ¿Usa algún tipo de billetera digital o aplicación financiera hoy? ¿Cuál y para qué? | "Uso la app de mi banco para ver mis movimientos y pagar el préstamo, y Yape para cobrarles a mis clientes." |
| 6 | ¿Qué tan familiarizado está con el concepto de criptomonedas o stablecoins? | "Casi nada, he escuchado de bitcoin en las noticias pero no sé bien cómo funciona." |
| 7 | ¿Qué le preocuparía más de pedir un préstamo a través de una app sin un banco de por medio? | "Que las condiciones no sean tan claras como en el banco, donde ya sé cuánto pago cada mes y a quién reclamarle si hay un problema." |
| 8 | Si pudiera demostrar que "es de fiar" sin tener historial bancario, ¿cómo cree que podría demostrarlo? | "Mostrando que pago mi préstamo del banco a tiempo, o con referencias de la gente con la que trabajo en el mercado." |
| 9 | ¿Puede describir la última vez que tuvo un problema de dinero relacionado con esto? ¿Qué hizo? | "Una vez necesité dinero rápido y el banco se demoró en aprobarme el préstamo, así que mientras tanto le pedí prestado a una vecina." |
| 10 | ¿Qué tendría que pasar para que confiara en una aplicación nueva para este propósito? | "Que me expliquen bien cómo funciona sin palabras raras, y que sea tan clara como mi banco en mostrarme cuánto debo." |
| 11 | ¿Qué es lo que más valoraría de una solución así, y qué es lo que la haría descartarla de inmediato? | "Valoraría que sea más rápida que el banco y que me den un monto justo según lo que vendo. La descartaría si siento que es menos segura o menos clara que mi banco." |

---

##### Entrevista 2: Rafael Chui

**Ficha del entrevistado**

| Campo | Detalle |
|---|---|
| Nombre | Rafael Chui |
| Edad | 24 años |
| Distrito | San Borja |
| Ocupación | Repartidor independiente (delivery) |
| Nivel de bancarización | Cuenta de ahorros en caja municipal; acceso limitado a crédito formal (montos bajos por ingresos no fijos) |
| Familiaridad con billeteras digitales/cripto | Baja: usa Yape, Plin y la app de su caja; conoce las criptomonedas solo por redes sociales, sin experiencia de uso |
| Video | [Ver grabación](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213406_upc_edu_pe/IQAV70dTUnwjTb6dBn95hr5iAXZVc30kSbCMiMb09Yx5PSQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=I2NLfL) |

**Screenshot de la entrevista**

![Entrevista Rafael Chui](resources/Cap1/Interviews-Caps/RafaelInterview.png)

**Resumen**

Rafael financia sus gastos con lo que gana durante la semana y, ante un gasto grande como la reparación de su moto, recurre a su familia o a amigos, y ocasionalmente a una junta. Intentó acceder a un préstamo en la caja donde tiene su cuenta, pero por no tener ingresos fijos ni boletas solo le ofrecían un monto muy bajo, por lo que no lo tomó. Sus ingresos son medianamente predecibles: mejoran los fines de semana y a fin de mes, pero bajan con la lluvia o con fallas de las aplicaciones de reparto. Usa Yape y Plin para sus pagos diarios, y tiene muy poca familiaridad con las criptomonedas, que conoce solo por videos y comentarios de amigos. Le preocupa que una app sin banco de por medio le cobre condiciones no informadas al inicio o que no haya a quién reclamar si algo falla. Considera que podría demostrar ser "de fiar" mostrando su historial de pedidos, sus calificaciones en las apps de delivery y sus movimientos de Yape. Valoraría una solución rápida y fácil de usar desde el celular, pero la descartaría si le piden mucha información personal sin explicar el motivo o si las condiciones cambian después.

**Transcripción completa**

| # | Pregunta | Respuesta |
|---|---|---|
| 1 | ¿Cómo financia hoy sus gastos o su actividad económica cuando necesita dinero que no tiene disponible? | "Con lo que gano en la semana. Si se me presenta un gasto grande, como arreglar la moto, le pido a mis papás o a un amigo." |
| 2 | ¿Ha intentado alguna vez acceder a un préstamo formal (banco, financiera, caja)? ¿Qué pasó? | "Sí, fui a la caja donde tengo mi cuenta. Me dijeron que como mis ingresos no son fijos ni tengo boletas, solo me podían dar un monto muy chico. Al final no lo tomé porque no me servía para lo que necesitaba." |
| 3 | ¿A quién le pide dinero prestado hoy (familia, conocidos, prestamista informal, "junta")? ¿Bajo qué condiciones? | "A mi familia sobre todo, sin interés, pero siento que no puedo abusar. A veces entro a una junta con amigos, aunque con eso no puedo escoger cuándo me toca el dinero." |
| 4 | ¿Qué tan predecibles son sus ingresos mes a mes? | "Más o menos. Los fines de semana y a fin de mes hay más pedidos, pero si llueve o si falla la aplicación, la semana baja bastante." |
| 5 | ¿Usa algún tipo de billetera digital o aplicación financiera hoy? ¿Cuál y para qué? | "Uso Yape y Plin para recibir pagos y pagar mis cosas del día a día. También tengo la app de la caja, pero casi solo para ver mi saldo." |
| 6 | ¿Qué tan familiarizado está con el concepto de criptomonedas o stablecoins? | "Poquito. He visto videos en TikTok y mis amigos hablan de bitcoin, pero nunca he comprado nada y no sé cómo se usa para algo real como un préstamo." |
| 7 | ¿Qué le preocuparía más de pedir un préstamo a través de una app sin un banco de por medio? | "Que se pierda mi plata o que me cobren cosas que no me dijeron al inicio. Y que si hay un problema no haya nadie a quien llamar." |
| 8 | Si pudiera demostrar que "es de fiar" sin tener historial bancario, ¿cómo cree que podría demostrarlo? | "Mostrando mi historial de pedidos y mis calificaciones en las apps de delivery, que ahí se ve que trabajo constante. También con mis movimientos de Yape." |
| 9 | ¿Puede describir la última vez que tuvo un problema de dinero relacionado con esto? ¿Qué hizo? | "Hace poco se me malogró la moto y no podía trabajar mientras tanto. Le pedí prestado a mi tío y se lo fui devolviendo en cuotas pequeñas durante dos meses." |
| 10 | ¿Qué tendría que pasar para que confiara en una aplicación nueva para este propósito? | "Que la recomienden personas que conozco, que tenga buenas opiniones y que me muestre claramente cuánto voy a pagar en total antes de aceptar." |
| 11 | ¿Qué es lo que más valoraría de una solución así, y qué es lo que la haría descartarla de inmediato? | "Valoraría que sea rápida y que sea fácil de usar desde el celular, sin tantos trámites. La descartaría si me piden mucha información personal sin explicar para qué o si veo que las condiciones cambian después." |

---

##### Entrevista 3: Gonzalo Contreras

**Ficha del entrevistado**

| Campo | Detalle |
|---|---|
| Nombre | Gonzalo Contreras |
| Edad | 22 años |
| Distrito | Villa María del Triunfo |
| Ocupación | Comerciante de mercado (puesto propio) |
| Nivel de bancarización | Sin cuenta bancaria; sin acceso a crédito formal (le exigieron boletas, aval y documentos que no posee) |
| Familiaridad con billeteras digitales/cripto | Muy baja: solo usa Yape con el número de su celular; no conoce las criptomonedas |
| Video | [Ver grabación](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213406_upc_edu_pe/IQC0ybY5Ls4pQ6Qw5eC4GupXAWf9-JjDwupdcTAFsZYLOjQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=ptaozv) |

**Screenshot de la entrevista**

![Entrevista Gonzalo Contreras](resources/Cap1/Interviews-Caps/GonzaloInterview.png)

**Resumen**

Gonzalo financia su actividad con lo que va juntando de las ventas de su puesto y, cuando necesita más capital para comprar mercadería, recurre a conocidos o a una junta. Intentó acceder a un préstamo en una caja, pero le exigieron boletas, un aval y otros documentos que no posee, por lo que no continuó el trámite. Pide dinero prestado a su hermana o a una amiga del mercado y, solo cuando no tiene otra salida, a un prestamista del barrio que le cobra cerca de 10% semanal. Sus ingresos no son predecibles: mejoran en fechas como Navidad o el Día de la Madre y caen en otros meses. No tiene cuenta bancaria y su único medio digital es Yape, que usa para cobrar a sus clientes y pagar a sus proveedores. No está familiarizado con las criptomonedas y las percibe como algo complejo y poco seguro. Le preocupa ser estafado o no tener a quién reclamar si algo sale mal con una app. Considera que podría demostrar ser "de fiar" mediante el testimonio de sus clientes y proveedores, que lo conocen hace años. Valoraría un préstamo con menos trámites y menor interés que el del prestamista informal, pero lo descartaría si le piden dinero por adelantado o si no entiende bien las condiciones.

**Transcripción completa**

| # | Pregunta | Respuesta |
|---|---|---|
| 1 | ¿Cómo financia hoy sus gastos o su actividad económica cuando necesita dinero que no tiene disponible? | "Casi siempre con lo que voy juntando de las ventas. Si necesito más para comprar mercadería, le pido a algún conocido o entro a una junta." |
| 2 | ¿Ha intentado alguna vez acceder a un préstamo formal (banco, financiera, caja)? ¿Qué pasó? | "Fui una vez a una caja, pero me pidieron boletas, un aval y varios papeles que no tengo. Me dijeron que volviera cuando tuviera todo y ya no volví." |
| 3 | ¿A quién le pide dinero prestado hoy (familia, conocidos, prestamista informal, "junta")? ¿Bajo qué condiciones? | "A mi hermana o a una amiga del mercado. Con un prestamista del barrio también he sacado, pero cobra mucho interés, como 10% por semana, y solo lo hago si no hay otra salida." |
| 4 | ¿Qué tan predecibles son sus ingresos mes a mes? | "Nada predecibles. En fechas como Navidad o el Día de la Madre vendo bien, pero en otros meses cae bastante y a veces apenas me alcanza." |
| 5 | ¿Usa algún tipo de billetera digital o aplicación financiera hoy? ¿Cuál y para qué? | "Solo Yape, para cobrar a mis clientes y pagar a mis proveedores. No tengo cuenta en ningún banco, solo uso el número de mi celular." |
| 6 | ¿Qué tan familiarizado está con el concepto de criptomonedas o stablecoins? | "Nada. He escuchado que es dinero por internet, pero me suena a algo para gente que sabe de computadoras, no sé cómo funciona ni si es seguro." |
| 7 | ¿Qué le preocuparía más de pedir un préstamo a través de una app sin un banco de por medio? | "Que me estafen o que no tenga a quién reclamar. Con alguien del barrio al menos sé dónde encontrarlo, con una app no sé quién está detrás." |
| 8 | Si pudiera demostrar que "es de fiar" sin tener historial bancario, ¿cómo cree que podría demostrarlo? | "Con que mis clientes y mis proveedores digan que siempre pago. Llevo años en el mismo puesto y todos me conocen." |
| 9 | ¿Puede describir la última vez que tuvo un problema de dinero relacionado con esto? ¿Qué hizo? | "Hace unos meses se me malogró el refrigerador del puesto y necesitaba dinero urgente. No me alcanzó con lo que tenía, así que le pedí al prestamista del barrio y me salió caro." |
| 10 | ¿Qué tendría que pasar para que confiara en una aplicación nueva para este propósito? | "Que alguien de confianza ya la haya usado y me cuente que le funcionó. Y que me expliquen todo clarito, cuánto pago y cuándo, sin letras chiquitas." |
| 11 | ¿Qué es lo que más valoraría de una solución así, y qué es lo que la haría descartarla de inmediato? | "Valoraría que no me pidan tantos papeles y que me presten sin tanto interés como el prestamista. La descartaría si me piden dinero por adelantado o si no entiendo bien las condiciones." |

---

##### Tabla resumen de entrevistas: segmento Prestamista con capital ocioso

| # | Entrevistado | Edad | Ocupación | Bancarización | Fecha |
|---|---|---|---|---|---|
| 1 | Renso Julca | 21 | Ingeniero de Software | Intermedio-alto, usa stablecoins | 18/09/2026 |

---

##### Entrevista 1: Renso Julca

**Ficha del entrevistado**

| Campo | Detalle                                                                                                |
|---|--------------------------------------------------------------------------------------------------------|
| Nombre | Renso Julca                                                                                          |
| Edad | 21 años                                                                                                |
| Distrito | Carabayllo                                                                                |
| Ocupación | Ingeniero de Software                                                                                   |
| Nivel de bancarización | Intermedio-alto; maneja billeteras digitales cotidianas y posee nociones operativas en stablecoins (USDT) |
| Familiaridad con billeteras digitales/cripto | Alta: usa billeteras móviles a diario y aplicaciones cripto sin dificultad técnica |
| Práctica de préstamo actual | Coloca excedentes de liquidez en micropréstamos a conocidos o referidos, con una tasa base desde el 5% mensual por montos mínimos, para rotar su dinero con rapidez |

**Screenshot de la entrevista**

![Entrevista Renso Julca](resources/Cap1/Interviews-Caps/Renso_Interview.jpeg)

**Resumen**

Renso Julca, estudiante de 21 años e independiente en servicios digitales en Lima, rota activamente su excedente de capital prestando montos mínimos a conocidos con una tasa base del 5% mensual y ahorrando en stablecoins (USDT) para evitar la pérdida de valor adquisitivo frente a los bajos rendimientos bancarios. Aunque se siente cómodo con el uso de billeteras y herramientas cripto, sus principales fricciones son el desgaste de realizar cobros manuales, la falta de un historial confiable para medir el riesgo de impago sin garantías y la desconfianza hacia plataformas intermediarias centralizadas. Por ello, adoptaría una solución como LatiFi siempre que opere bajo una arquitectura no custodial, muestre un puntaje de reputación visible y transparente del prestatario, asegure la liquidación automática de capital e intereses mediante Smart Contracts y cuente con filtros de verificación mínimos que impidan la evasión mediante cuentas duplicadas.

**Transcripción completa**

| # | Pregunta | Respuesta |
|---|---|---|
| 1 | ¿Qué hace hoy con el dinero que no necesita usar de inmediato (ahorro, inversión, cripto, nada)? | Mantengo una parte pequeña como fondo de reserva en cuentas bancarias convencionales, pero la mayor parte de mi excedente la roto prestando montos chicos a personas que necesitan liquidez inmediata o compro stablecoins (USDT) en exchanges para evitar que pierda valor frente a la inflación. No lo dejo quieto en el banco porque las tasas que dan por ahorro no rinden nada. |
| 2 | ¿Alguna vez ha prestado dinero a alguien fuera de su círculo cercano a cambio de un interés? ¿Cómo le fue? | Sí, he prestado a amigos de conocidos o personas recomendadas cobrando un 5% de interés mensual sobre montos mínimos. En la mayoría de los casos me han pagado puntual porque sabían que si fallaban no les volvía a prestar, pero en un par de ocasiones tuve que estar insistiendo bastante para que completen la cuota. El cobro manual y estar escribiendo para recordar pagos es lo más desgastante. |
| 3 | ¿Qué tan cómodo se siente usando billeteras digitales o aplicaciones cripto? | Me siento bastante cómodo. Uso billeteras móviles a diario y también aplicaciones cripto sin problemas técnicos. Entiendo conceptos de transferencias directas y manejo de fondos, así que operar una app que se conecte con wallet no me resulta difícil. |
| 4 | ¿Qué información necesitaría ver de un desconocido antes de decidir prestarle dinero? | Si no lo conozco de nada, necesito ver mínimamente cuántos préstamos anteriores ha pedido, si los ha pagado a tiempo y un puntaje o indicador claro de cumplimiento. También saber a qué se dedica su negocio o en qué va a usar el dinero para saber si tendrá flujo de ingresos para devolverlo. |
| 5 | ¿Qué nivel de riesgo de no pago estaría dispuesto a aceptar a cambio de qué tasa de interés? | Por montos pequeños suelo manejar una tasa mínima del 5%. Estaría dispuesto a asumir un riesgo moderado con personas que recién empiezan a construir su reputación siempre que el monto inicial prestado sea bajo y la tasa compense ese margen. Si el riesgo percibido es muy alto o no hay ningún antecedente, no arriesgaría mi capital. |
| 6 | ¿Qué le generaría más desconfianza en una plataforma de préstamos entre desconocidos sin banco de por medio? | Me daría mucha desconfianza que la aplicación sea la que retenga o controle el dinero, o que el solicitante pueda crearse una cuenta falsa, pedir dinero, no pagar y desaparecer sin ninguna consecuencia. Necesito saber que el sistema asegura la devolución automática de lo cobrado sin intermediarios que demoren los retiros. |
| 7 | ¿Preferiría que existiera algún tipo de garantía o colateral, o le basta con una reputación verificable del prestatario? | En DeFi tradicional piden dejar el doble en garantía, pero entiendo que un pequeño emprendedor del día a día no tiene criptomonedas guardadas para dejar empeñadas. Para montos mínimos de microcrédito me basta con una reputación sólida y comprobable donde se vea que el usuario cuida su historial para no perder acceso a montos mayores. |
| 8 | ¿Puede describir la última vez que tuvo un problema de dinero relacionado con esto? ¿Qué hizo? | Le presté un monto pequeño a un conocido con la condición de devolverlo en 15 días con un extra. Pasó el mes y no me respondía los mensajes de WhatsApp; tuve que buscarlo directamente para acordar un pago fraccionado. Desde ahí decidí que no presto si no hay un compromiso muy claro o un historial que respalde a la persona. |
| 9 | ¿Qué tendría que pasar para que confiara en una aplicación nueva para este propósito? | Debe quedar clarísimo que la plataforma no se queda con mis llaves ni custodia mis fondos de forma opaca. Además, la ejecución del desembolso y el cobro debe ser automática e inmediata apenas el prestatario paga, sin cobros ocultos ni retrasos manuales. |
| 10 | ¿Qué es lo que más valoraría de una solución así, y qué es lo que la haría descartarla de inmediato? | Lo que más valoraría es ver un historial de pagos real y automatizado que me permita diversificar mi excedente en varios microcréditos de forma transparente. La descartaría de inmediato si me cobran comisiones abusivas por operar o si la plataforma permite cuentas fantasmas sin un filtro mínimo de verificación. |

---

#### 2.2.3. Análisis de entrevistas

El equipo analiza las cuatro entrevistas registradas en 2.2.2: tres del segmento prestatario (Joseph Falcón, Rafael Chui y Gonzalo Contreras) y una del segmento prestamista (Renso Julca). Cada hallazgo cita a quienes lo sustentan y se traduce en una decisión de producto trazable a una historia de usuario.

##### Hallazgos del segmento prestatario

| # | Hallazgo | Evidencia | Decisión de producto |
|---|---|---|---|
| H1 | El crédito formal les ofrece montos bajos o los excluye por no tener boletas ni ingresos fijos. | Joseph recibió un monto bajo con tasa alta; Rafael recibió un monto tan chico que no lo tomó; a Gonzalo le exigieron boletas, aval y documentos y abandonó el trámite. | Evaluar al solicitante por reputación y no por documentos formales (US-REP-01, US-REP-02). |
| H2 | Cuando necesitan dinero recurren a familiares, amigos, juntas o prestamistas informales, y el costo de este último es alto. | Los tres citan a su familia o a conocidos; Joseph y Rafael mencionan las juntas; Gonzalo cuenta que el prestamista del barrio le cobra cerca de 10% semanal. | Ofrecer una alternativa con tasa y plazo visibles desde la solicitud (US-LEND-01). |
| H3 | Sus ingresos varían según la temporada, el clima o el día de la semana. | Joseph describe semanas buenas y flojas, Rafael habla de lluvia y fallas de las aplicaciones de reparto, y Gonzalo menciona Navidad y el Día de la Madre. | Mostrar siempre la cuota y la fecha de vencimiento, y no exigir un monto fijo mensual (US-LEND-05). |
| H4 | Usan Yape o Plin a diario, pero casi no conocen las criptomonedas. | Los tres usan Yape; Rafael añade Plin; ninguno ha usado criptomonedas y Gonzalo dice que le suenan a algo "para gente que sabe de computadoras". | Onboarding en lenguaje simple y montos en soles junto al monto en stablecoin (US-AUTH-03, US-LEND-06). |
| H5 | Temen la falta de claridad en las condiciones y no tener a quién reclamar. | Joseph quiere saber cuánto paga cada mes; Rafael teme cobros no informados; Gonzalo teme una estafa porque no sabe quién está detrás de la aplicación. | Mostrar el costo total antes de aceptar y confirmar cada operación con un comprobante (US-AUTH-04, US-LEND-05). |
| H6 | Creen que pueden demostrar que son de fiar con señales ajenas al banco. | Joseph propone sus pagos puntuales y referencias del mercado; Rafael, su historial y calificaciones en las aplicaciones de reparto; Gonzalo, el testimonio de sus clientes y proveedores. | Combinar eventos on-chain con señales off-chain del perfil en la reputación (US-REP-02). |
| H7 | La confianza en una aplicación nueva depende de recomendaciones y de una explicación sin tecnicismos. | Rafael y Gonzalo piden que alguien conocido ya la haya usado; Joseph, Rafael y Gonzalo piden que les expliquen cuánto pagan y cuándo, sin palabras raras ni letras chiquitas. | Landing y onboarding con lenguaje sencillo y una sección de seguridad visible (US-LAND-01, US-AUTH-03). |

##### Hallazgos del segmento prestamista

| # | Hallazgo | Evidencia | Decisión de producto |
|---|---|---|---|
| H8 | Presta excedentes a conocidos con una tasa base desde 5% mensual y el cobro manual lo desgasta. | Renso rota su capital en préstamos pequeños y señala que recordar los pagos es lo más desgastante. | Automatizar el desembolso y el cobro con el Smart Contract (US-LEND-03, US-LEND-04). |
| H9 | Necesita ver el historial de pagos del solicitante antes de prestar a un desconocido. | Renso pide cuántos préstamos anteriores tiene, si los pagó a tiempo y un indicador claro de cumplimiento. | Feed con reputación visible y ordenable (US-LEND-02, US-REP-03). |
| H10 | Rechaza que la plataforma custodie los fondos y teme las cuentas falsas. | Renso descarta una aplicación que retenga el dinero y las cuentas fantasmas sin filtro mínimo de verificación. | Modelo no custodial y registro de perfil ligero (US-AUTH-02, US-IDEN-01). |
| H11 | Para montos pequeños le basta una reputación comprobable en lugar de un colateral. | Renso entiende que un pequeño emprendedor no tiene criptomonedas para dejar en garantía. | Descartar el colateral bloqueado en el alcance del producto. |

##### Limitaciones

Cuatro entrevistas no permiten generalizar y el segmento prestamista cuenta con una sola. El equipo agregará entrevistas de ese segmento y revisará estos hallazgos con cada nuevo registro.

### 2.3. Needfinding

El proceso de Needfinding de LatiFi se apoya en los hallazgos reales de las entrevistas de la sección 2.2. Cada artefacto indica la herramienta empleada y los datos de campo en los que se basa.

#### 2.3.1. User Personas

**Persona: Prestatario no bancarizado**

| Campo | Detalle |
|---|---|
| Herramienta | UXPressia |
| Basado en | Entrevista 1, sección 2.2.2 |
| Segmento | Prestatario no bancarizado/subatendido |

![User Persona - Prestatario](resources/Cap1/UserPersona/JosephUserPersona.png)

El Persona del prestatario fue construido en UXPressia a partir de los datos demográficos, objetivos, frustraciones y comportamientos recogidos en la entrevista 1 del segmento, representando a un prestatario con acceso limitado a crédito formal, ingresos variables y baja familiaridad con criptoactivos.

**Persona: Prestamista con capital ocioso**

| Campo | Detalle |
|---|---|
| Herramienta | UXPressia |
| Basado en | Entrevista 1, sección 2.2.2 |
| Segmento | Prestamista con capital ocioso |

![User Persona - Prestamista](resources/Cap2/User_Persona/Renso%20Julca.png)

El Persona del prestamista fue construido en UXPressia a partir de la entrevista 1 de su segmento, representando a un prestamista con excedente de liquidez, comodidad con billeteras digitales y stablecoins, y la necesidad de una señal clara de cumplimiento antes de prestar a desconocidos.

#### 2.3.2. User Task Matrix

La matriz cruza a los dos User Persona con las tareas que realizan hoy para cumplir sus objetivos financieros, con independencia de cualquier solución de software. Los segmentos considerados son el Prestatario no bancarizado, representado por Joseph Falcón, y el Prestamista con capital ocioso, representado por Renso Julca.

| Tarea | Prestatario: Frecuencia | Prestatario: Importancia | Prestamista: Frecuencia | Prestamista: Importancia |
|---|---|---|---|---|
| Financiar gastos o actividad con ahorros propios | Alta | Alta | No aplica | No aplica |
| Pedir un préstamo al banco cuando el ahorro no alcanza | Ocasional | Alta | No aplica | No aplica |
| Pedir dinero a conocidos cuando el banco demora | Ocasional | Media | No aplica | No aplica |
| Cobrar a sus clientes por Yape | Alta | Alta | No aplica | No aplica |
| Pagar las cuotas del préstamo y revisar movimientos en la app del banco | Mensual | Crítica | No aplica | No aplica |
| Demostrar que es de fiar sin historial bancario (pagos puntuales, referencias) | Ocasional | Alta | No aplica | No aplica |
| Mantener un fondo de reserva en cuenta bancaria | No aplica | No aplica | Baja | Media |
| Prestar excedentes a conocidos o referidos con interés | No aplica | No aplica | Alta | Alta |
| Comprar y guardar stablecoins (USDT) para conservar el valor del excedente | No aplica | No aplica | Alta | Alta |
| Evaluar si confiar en un solicitante desconocido (préstamos previos, cumplimiento, uso del dinero) | No aplica | No aplica | Antes de cada préstamo | Crítica |
| Fijar la tasa según el monto y el riesgo del solicitante | No aplica | No aplica | Por préstamo | Alta |
| Cobrar cuotas vencidas y acordar pagos fraccionados | No aplica | No aplica | Ocasional | Alta |

La frecuencia y la importancia se infieren de la entrevista 1 de cada segmento, por lo que se ajustarán al ampliar el registro de entrevistas.

Las tareas de mayor frecuencia e importancia del prestatario giran en torno a conseguir liquidez y pagarla a tiempo: financiarse con ahorros, recurrir al banco cuando no alcanza y cobrar a sus clientes. Para el prestamista, las tareas críticas son rotar su excedente prestando y decidir en quién confiar. La diferencia principal entre ambos es que el prestatario busca acceso y condiciones claras, mientras que el prestamista busca señales verificables de cumplimiento. Coinciden en la desconfianza hacia esquemas poco transparentes y en el valor de un historial de pagos: el prestatario lo necesita para demostrar que es de fiar y el prestamista para decidir a quién prestar.

#### 2.3.3. Empathy Mapping

**Empathy Map: Prestatario no bancarizado**

| Campo | Detalle |
|---|---|
| Herramienta | UXPressia |
| Basado en | Entrevista 1, sección 2.2.2 |
| Segmento | Prestatario no bancarizado/subatendido|

![Empathy Map - Prestatario](resources/Cap1/EmpathyMap/EmpathyMapping.png)

El Empathy Map fue construido en UXPressia a partir de los hallazgos de la entrevista 1 de la sección 2.2.2, documentando lo que el Prestatario dice, piensa, hace y siente frente al acceso al crédito.

**Empathy Map: Prestamista con capital ocioso**

| Campo | Detalle |
|---|---|
| Herramienta | UXPressia |
| Basado en | Entrevista 1, sección 2.2.2 |
| Segmento | Prestamista con capital ocioso |

**¿Qué piensa y siente?**

- **Pensamientos centrales:** "Dejar el dinero quieto en el banco hace que pierda valor frente a la inflación; prefiero rotarlo activamente prestando o comprando stablecoins". "No puedo prestar a desconocidos a ciegas si no tengo una señal clara de que la persona cuida su historial y pagará a tiempo".
- **Sentimientos:** frustración e incomodidad ante las cobranzas manuales y ante perseguir a quien se retrasa; seguridad y confianza si el retorno de su dinero queda programado de forma automática e inmutable en código.

**¿Qué ve?**

- En el entorno financiero: tasas bancarias tradicionales que no rinden y protocolos DeFi que exigen un sobrecolateral que los microemprendedores peruanos no tienen.
- En su entorno social y digital: contactos y conocidos que buscan liquidez inmediata y que pagan tasas sobre el 5% mensual para financiar compras o proyectos de corto plazo.
- En la plataforma LatiFi: un feed estructurado con solicitudes abiertas, tasas propuestas, plazos de pago y el indicador de reputación visible de cada solicitante.

**¿Qué oye?**

- A amigos y colegas hablar sobre billeteras móviles, adopción de stablecoins y plataformas Web3.
- Comentarios recurrentes sobre la falta de garantías en préstamos de confianza y el riesgo de que personas conocidas terminen incumpliendo sus pagos.
- Discusiones sobre la necesidad de plataformas transparentes donde intermediarios centralizados no bloqueen los retiros.

**¿Qué dice y hace?**

- **Dice:** "Presto con una tasa mínima del 5% mensual sobre montos pequeños para que mi dinero no pierda valor". "Para prestarle a alguien que no conozco, necesito ver cuántos préstamos ya pagó a tiempo y a qué se dedica".
- **Hace:** utiliza billeteras digitales cotidianas y mantiene ahorros en stablecoins (USDT); evalúa el perfil de riesgo antes de comprometer fondos y prioriza montos pequeños y de rápida rotación.

**Esfuerzos y frustraciones (Pains)**

- El desgaste de cobrar manualmente por mensajes cuando una cuota se vence.
- El riesgo de default total o de que usuarios malintencionados creen billeteras nuevas para huir de sus deudas (ataque Sybil).
- Plataformas que cobran comisiones abusivas o que retienen fondos sin permitir retiros directos.

**Deseos y necesidades (Gains)**

- Rentabilidad predecible y superior a la banca tradicional a través de micropréstamos en stablecoins.
- Desembolso y cobro 100% automatizado mediante Smart Contracts directamente a su wallet personal.

#### 2.3.4. As-is Scenario Mapping

Se documentará el escenario actual ("as-is") de cada segmento, es decir, cómo un prestatario no bancarizado consigue dinero hoy sin LatiFi y cómo un prestamista coloca su capital ocioso hoy sin LatiFi, como línea base para contrastar contra el escenario futuro ("to-be") que la plataforma habilitará. Este mapeo se trabajará en sesión de equipo sobre **Miro** o **LucidChart**, en paralelo al Big Picture EventStorming del dominio.

El presente diagrama modela el flujo operacional actual (*AS-IS*) de una solicitud de préstamo con garantía bajo esquemas tradicionales, caracterizado por una alta dependencia de la intervención humana, transferencia física de expedientes y baja trazabilidad en tiempo real.

![As-Is scenario mapping](resources/Cap1/As-Is%20scenario%20mapping.png)

##### Carriles de Responsabilidad (Swimlanes)
* **USER / BORROWER**: Prestatario que inicia la petición y aporta documentación de respaldo.
* **LOAN OFFICER / FRONT DESK**: Mesón de atención y primer filtro de recepción documental.
* **CREDIT RISK DEPARTMENT**: Área analítica encargada de evaluar la viabilidad de riesgo del crédito.
* **FINANCE / OPERATIONS**: Instancia final de emisión de vouchers, validación de firmas y desembolso de fondos.

##### Descripción Secuencial del Flujo
1. **Initiate Loan Application [Manual]**: El usuario completa y entrega la solicitud inicial del crédito.
2. **Submit Required Documents?**: Verificación de presencia de requisitos mínimos adjuntos.
   * *No*: El proceso se detiene o retorna para la recolección de faltantes.
   * *Yes*: Avanza a recepción formal.
3. **Receive & Review Application Package [Manual Verification]**: El Front Desk valida preliminarmente el paquete documental.
4. **Perform Initial Eligibility Check [Manual]**: Evaluación rápida de cumplimiento de políticas de entrada.
5. **Application Complete & Eligible?**: Validación de pase a siguiente fase.
   * *No* → **6. Notify Applicant of Rejection / Missing Info**.
   * *Yes* → **7. Assign Loan Officer & Create Physical File**.
8. **Forward File to Credit Dept**: Traslado físico o digital básico del expediente al departamento de riesgos.
9. **Conduct Credit Risk Assessment [Manual]**: Análisis manual del perfil de riesgo y capacidad de pago.
10. **Risk Acceptable?**:
    * *No* → Fin del proceso por rechazo de riesgo.
    * *Yes* → **12. Approve Loan Terms & Conditions**.
13. **Generate Loan Agreement [Manual]**: Confección e impresión física del contrato legal.
14. **Notify Loan Officer of Approval**: Aviso interno de viabilidad aprobada.
15. **Schedule Loan Closing Appointment**: Coordinación de cita presencial con el cliente.
16. **Prepare Disbursement Voucher [Manual]**: Elaboración del documento de orden de pago.
17. **Obtain Authorized Signatures [Manual]**: Firma física gerencial/financiera requerida.
18. **Disburse Funds [Check / Cash / Wire Transfer]**: Emisión efectiva del capital al usuario mediante medios tradicionales.

##### Puntos de Dolor Identificados (Pain Points)
* **Latencia elevada**: Tiempos muertos significativos en los traspasos de expedientes físicos/digitales entre el *Loan Officer*, *Credit Dept* y *Finance* (pasos 7, 8, 14, 15).
* **Fricción presencial**: Dependencia de citas presenciales obligatorias para firma de contratos y gestión de desembolsos (pasos 15-18).
* **Riesgo operativo**: Propensión a errores de transcripción manual en la evaluación de riesgos y pérdida o degradación de expedientes en físico.
* **Cero visibilidad en tiempo real**: El usuario no cuenta con un panel de autogestión para auditar en qué sub-paso de revisión se encuentra su expediente (bloque 9-13).
  
### 2.4. Ubiquitous Language

El siguiente glosario recoge los términos de negocio del dominio de microcrédito P2P descentralizado que el equipo usará de forma consistente en el resto del informe, en el modelo de dominio y en el código, siguiendo la práctica de Ubiquitous Language de Domain-Driven Design. Se excluyen términos puramente técnicos de ingeniería de software (framework, endpoint, repositorio, etc.) que no forman parte del lenguaje de negocio del dominio.

| Term | Definición |
|---|---|
| **Borrower** (Prestatario) | Persona no bancarizada que solicita un microcrédito en stablecoins a través de LatiFi Wallet, respaldado por su reputación y no por colateral bloqueado. |
| **Lender** (Prestamista) | Persona con capital ocioso que financia una o más solicitudes de préstamo publicadas por prestatarios, a cambio de un interés pactado. |
| **Loan Request** (Solicitud de préstamo) | Publicación de un prestatario que especifica el monto solicitado en stablecoin, la tasa de interés propuesta y el plazo de devolución, visible en el feed de prestamistas. |
| **Loan Agreement** (Contrato de préstamo) | Instancia del Smart Contract que representa un préstamo ya fondeado, con sus condiciones (monto, interés, plazo, estado) registradas de forma inmutable en blockchain. |
| **Collateral** (Colateral/Garantía) | Activo bloqueado por el prestatario como respaldo del préstamo. Explícitamente fuera del modelo de riesgo de LatiFi, que sustituye el colateral por reputación. |
| **Reputation Score** (Puntaje de reputación) | Medida cuantitativa de la confiabilidad de un prestatario, calculada de forma híbrida a partir de su historial de pagos on-chain y de señales de perfil off-chain gestionadas por la LatiFi API. |
| **Cold Start** (Arranque en frío) | Situación de un usuario nuevo sin ningún historial on-chain previo, para quien un modelo de reputación puramente on-chain no puede generar un puntaje confiable. |
| **KYC-lite** (Verificación de identidad liviana) | Captura mínima de datos de identidad (nombre, contacto, información autodeclarada) suficiente para disuadir ataques Sybil, sin llegar al nivel de un KYC documental regulatorio. |
| **Sybil Attack** (Ataque Sybil) | Estrategia en la que una misma persona crea múltiples billeteras para simular varias identidades y falsear artificialmente un historial de reputación limpio. |
| **Stablecoin** | Criptomoneda cuyo valor está anclado a una moneda fiduciaria (usualmente el dólar), usada para denominar los préstamos y evitar que la volatilidad de una criptomoneda nativa distorsione el monto adeudado. |
| **Wallet** (Billetera digital) | Aplicación o componente que custodia las claves criptográficas del usuario y le permite firmar transacciones; en LatiFi es no custodial, es decir, el usuario controla sus propias claves. |
| **Smart Contract** (Contrato inteligente) | Programa desplegado en blockchain que ejecuta de forma automática e inmutable las condiciones del préstamo: recepción de fondos, desembolso, liberación del pago y registro del vencimiento. |
| **Escrow** (Custodia temporal) | Función del Smart Contract mediante la cual los fondos del prestamista quedan retenidos por el contrato hasta que se cumplen las condiciones para desembolsarlos al prestatario. |
| **Default** (Incumplimiento) | Situación en la que el prestatario no devuelve el capital y/o el interés pactado dentro del plazo establecido, con impacto negativo en su puntaje de reputación. |
| **Repayment** (Devolución/Pago) | Acción del prestatario de devolver el capital más el interés pactado, liberando automáticamente los fondos correspondientes al prestamista a través del Smart Contract. |
| **On-chain / Off-chain** (En cadena / fuera de cadena) | Distinción entre los datos y la lógica que residen de forma inmutable en la blockchain (on-chain, ej. el estado del préstamo) y los que residen en un sistema tradicional fuera de ella (off-chain, ej. el perfil del usuario en la LatiFi API). |
| **Testnet** (Red de prueba) | Red blockchain paralela a la red principal (mainnet), usada para desplegar y probar el Smart Contract sin mover dinero real; LatiFi opera sobre la testnet Polygon Amoy. |
| **Exchange Rate** (Tipo de cambio) | Tasa de conversión entre el valor de la stablecoin del préstamo y la moneda local del usuario, consumida por la app para mostrar montos y cuotas en la moneda que el usuario entiende. |
| **Unbanked / Underbanked** (No bancarizado / subatendido) | Persona sin acceso a una cuenta bancaria formal o con acceso muy limitado a productos financieros formales, segmento objetivo primario de LatiFi. |

<div style="page-break-after: always;"></div>

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

El modelo **TO-BE** rediseña el préstamo entre personas sin garantía: la reputación on-chain reemplaza al colateral y un contrato inteligente (*smart contract*) ejecuta cada paso sin intermediarios. El usuario crea o importa su propia billetera non-custodial en la app, y la moneda local aparece solo como referencia en pantalla, sin llegar nunca al contrato.

```mermaid
flowchart LR
    subgraph PRE["Prestatario"]
        B3["3. Solicita el préstamo: monto, tasa, plazo y cuotas de 1 a 6"]
        B7["7. Paga cada cuota"]
    end
    subgraph LEN["Prestamista"]
        L5["5. Revisa el feed ordenado por reputación"]
        L6["6. Firma el fondeo"]
    end
    subgraph WAL["Identity / Wallet"]
        W1["1. Crea o importa su billetera y confirma la frase de recuperación"]
        W2["2. Inicia sesión firmando un desafío y completa el perfil ligero"]
    end
    subgraph SC["Lending Smart Contract"]
        C3["3. Guarda la solicitud y emite LoanRequested"]
        C6["6. Pasa la stablecoin al prestatario, fija los términos y emite LoanFunded"]
        C7["7. Registra la cuota y emite LoanRepaid con onTime"]
        C9["9a. Vencido el plazo, cualquiera marca el incumplimiento y se emite LoanDefaulted"]
    end
    subgraph IDX["Event Indexer y Reputation"]
        I8["8. Lee los eventos y actualiza el feed y la reputación"]
        R9A["9a. La reputación baja de forma gradual"]
        R9B["9b. La última cuota salda el préstamo y la reputación se recupera"]
    end
    subgraph FX["Exchange Rate"]
        X4["4. Convierte los montos a moneda local solo para mostrarlos"]
    end
    W1 --> W2 --> B3 --> C3
    C3 --> L5
    C3 -.-> X4
    X4 -.-> L5
    L5 --> L6 --> C6 --> B7 --> C7
    C6 -->|vence sin pago completo| C9
    C7 --> I8
    C9 --> I8
    I8 -->|LoanDefaulted| R9A
    I8 -->|última cuota de LoanRepaid| R9B
```

El diagrama sigue los nueve pasos de la lista y usa solo los cuatro eventos del ABI v0. Las líneas punteadas marcan la conversión a moneda local, que solo se muestra y nunca viaja en una transacción.

#### Carriles de Arquitectura / Capas (Swimlanes / Bounded Context Layers)
* **PRESTATARIO**: Persona no bancarizada que solicita el préstamo y paga las cuotas desde su propia billetera.
* **PRESTAMISTA**: Persona con capital ocioso que revisa el feed y fondea la solicitud que elige.
* **IDENTITY / WALLET CONTEXT**: Creación o importación de la billetera, firma de un desafío para iniciar sesión y perfil ligero.
* **LENDING SMART CONTRACT**: Guarda la solicitud, mueve la stablecoin de prueba, registra las cuotas y marca el incumplimiento. Emite `LoanRequested`, `LoanFunded`, `LoanRepaid` y `LoanDefaulted`.
* **EVENT INDEXER Y REPUTATION CONTEXT**: Lee los eventos de la cadena, mantiene el feed y recalcula la reputación de forma gradual.
* **EXCHANGE RATE CONTEXT**: Convierte los montos a moneda local solo para mostrarlos. La conversión ocurre en la API y ningún evento ni transacción lleva un precio.

#### Descripción Secuencial del Flujo (TO-BE Steps)
1. **Create or Import Non-Custodial Wallet [Action]**: El usuario crea una billetera en la app, o importa la que ya tiene con su frase de recuperación, y confirma que la guardó. La frase se muestra una sola vez y nunca sale del dispositivo.
2. **Sign In and Complete Light Profile [Action]**: El usuario inicia sesión firmando un desafío con su billetera y completa su perfil ligero.
3. **Request Loan [Trigger]**: El prestatario define monto, tasa, plazo y cuotas de 1 a 6. El contrato guarda la solicitud. → *Event: `LoanRequested`*.
4. **Show Local Currency [Display]**: Prestatario y prestamista ven los montos en stablecoin y en moneda local. La conversión es solo informativa.
5. **Review Feed by Reputation [Logic]**: El prestamista revisa el feed ordenado por la reputación de cada solicitante.
6. **Fund Loan [Funds Transfer]**: El prestamista firma el fondeo, la stablecoin pasa al prestatario y los términos quedan fijos. → *Event: `LoanFunded`*.
7. **Repay Installments [Funds Transfer]**: El prestatario paga cada cuota y el contrato registra si el pago llegó a tiempo. → *Event: `LoanRepaid`*, con el indicador `onTime` por pago.
8. **Index Events and Update Reputation [Logic]**: El indexador lee los eventos y la reputación cambia de forma gradual, sin saltos a cero.
   * **9a. Mark Default [Action]**: Vencido el plazo sin el pago completo, cualquier persona marca el préstamo como incumplido y la reputación baja. → *Event: `LoanDefaulted`*.
   * **9b. Settle Loan [Action]**: Con la última cuota el préstamo queda saldado y la reputación se recupera. → *Event: `LoanRepaid`*.

#### Ventajas Clave / Mejora frente al AS-IS (Value Proposition)
* **Latencia instantánea**: De días o semanas a segundos o minutos, porque el contrato ejecuta la solicitud, el fondeo y el pago de forma determinista (pasos 3, 6 y 7).
* **Desintermediación y Autogestión**: Sin oficial de crédito, mesones físicos, mesas de riesgo manuales ni vouchers de papel.
* **Reputación en lugar de garantía**: El historial de pago verificable sustituye al colateral, así que el prestatario no necesita capital previo para acceder a crédito.
* **Trazabilidad total on-chain**: Solicitudes, fondeos, pagos e incumplimientos son eventos públicos y auditables en tiempo real, y la reputación se calcula a partir de ellos.

---

#### Tabla Comparativa Resumen: AS-IS vs. TO-BE
| Dimensión | Enfoque AS-IS (Tradicional) | Enfoque TO-BE (Web3 / Descentralizado) |
| :--- | :--- | :--- |
| **Tiempo de Procesamiento** | Varios días por los traspasos manuales entre áreas | Segundos a minutos (automático on-chain) |
| **Intermediarios** | Front Desk, Oficial de Crédito, Riesgos, Finanzas | Ninguno (Smart Contract e indexador de eventos) |
| **Garantía** | Físico / Documental / Legal tradicional | Ninguna: la reputación on-chain reemplaza a la garantía |
| **Evaluación de Riesgo** | Subjetiva / Manual / Formularios impresos | Algorítmica (reputación on-chain y señales del perfil) |
| **Disponibilidad / Canal** | Horario de oficina / Presencial en sucursal | 24/7 / Autogestión desde la app con billetera propia |

El propósito de esta sección es contrastar, mediante un To-Be Scenario Map, la secuencia de actividades que hoy ejecuta un prestatario o prestamista no bancarizado para acceder a crédito informal (fiado, prestamistas gota a gota, préstamos familiares) contra la secuencia propuesta una vez que LatiFi Wallet media el flujo mediante Smart Contracts y reputación descentralizada. Ese contraste se apoya en el As-Is construido a partir de entrevistas reales a los segmentos objetivo (prestatario no bancarizado y prestamista con capital ocioso), documentado en la sección de Needfinding del Capítulo II.

### 3.2. User Stories

Los 21 requisitos v1 definidos para el proyecto se traducen a continuación en User Stories agrupadas por Epic. Cada Epic corresponde a uno de los bounded contexts o frentes funcionales del proyecto (Auth, Identity, Lending, Reputation, API, Landing Page). Se agregan tres Technical Stories con rol "Developer" para cubrir aspectos de la RESTful API sin interacción directa de usuario final, principalmente el indexado de eventos on-chain, exigidos por la arquitectura pero invisibles para prestatario y prestamista.

| Epic/User Story ID | Título | Descripción | Criterios de Aceptación (Gherkin) | Relacionado con (Epic ID) |
|---|---|---|---|---|
| **EPIC-AUTH** | Autenticación con billetera | - | - | - |
| US-AUTH-01 | Creación o importación de billetera digital | Como prestatario o prestamista, deseo crear una billetera non-custodial en la app móvil, o importar una que ya tengo con mi frase de recuperación, para autenticarme sin crear usuario y contraseña. | **Given** que soy un usuario nuevo o recurrente de LatiFi Wallet, **When** selecciono "Crear billetera" y confirmo que guardé mi frase de recuperación, o selecciono "Importar billetera" e ingreso mi frase, **Then** la app reconoce mi dirección on-chain como mi identidad y me redirige a la pantalla principal según mi rol. | EPIC-AUTH |
| US-AUTH-02 | Firma no custodial de transacciones | Como usuario de LatiFi Wallet, deseo firmar mis transacciones desde mi propia billetera sin que LatiFi gestione mi llave privada, para conservar control total de mis fondos. | **Given** que inicio una acción que requiere una transacción on-chain (fondear, pagar), **When** la app construye la transacción y la envía a mi wallet para firma, **Then** la llave privada nunca sale de mi dispositivo ni es almacenada por LatiFi, y la transacción solo se envía a la red tras mi aprobación explícita. | EPIC-AUTH |
| US-AUTH-03 | Onboarding progresivo en lenguaje simple | Como usuario no familiarizado con criptomonedas, deseo completar un onboarding progresivo en lenguaje simple antes de conectar mi billetera por primera vez, para entender el flujo sin necesitar conocimiento técnico previo. | **Given** que abro LatiFi Wallet por primera vez, **When** avanzo por las pantallas de onboarding, **Then** cada paso explica el flujo de préstamo (solicitar, fondear, pagar, reputación) sin jerga cripto, y solo al final se me solicita conectar la billetera. | EPIC-AUTH |
| US-AUTH-04 | Retroalimentación de estado de transacción | Como usuario de LatiFi Wallet, deseo ver el estado de mi transacción (pendiente, confirmando, confirmada, fallida), para saber si mi acción se ejecutó sin necesidad de consultar un explorador de bloques. | **Given** que envié una transacción (fondeo o pago), **When** la transacción está en la mempool o siendo minada, **Then** la app muestra un estado "pendiente/confirmando" y actualiza a "confirmada" o "fallida" apenas la red Polygon Amoy confirma o rechaza el bloque correspondiente. | EPIC-AUTH |
| **EPIC-IDEN** | Identidad y perfil ligero | - | - | - |
| US-IDEN-01 | Registro de perfil ligero | Como usuario nuevo, deseo completar un registro de perfil ligero (nombre, contacto) antes de publicar o fondear una solicitud, para que el sistema tenga una base mínima de resistencia a Sybil. | **Given** que conecté mi billetera por primera vez, **When** intento publicar o fondear una solicitud de préstamo, **Then** el sistema me exige completar nombre y contacto antes de habilitar la acción, y vincula ese perfil a mi dirección on-chain. | EPIC-IDEN |
| US-IDEN-02 | Exposición de perfil vía API propia | Como usuario de LatiFi Wallet, deseo que mi perfil quede almacenado y accesible vía la LatiFi API, para que la app pueda mostrarlo de forma consistente en cualquier pantalla. | **Given** que completé mi registro de perfil, **When** la app solicita `GET /profiles/{address}` a LatiFi API, **Then** la API responde con los datos de perfil vinculados a mi dirección on-chain, sin exponer datos de otros usuarios. | EPIC-IDEN |
| **EPIC-LEND** | Ciclo de préstamo on-chain | - | - | - |
| US-LEND-01 | Publicación de solicitud de préstamo | Como prestatario, deseo publicar una solicitud de préstamo especificando monto, tasa de interés y plazo en una stablecoin de prueba, para que prestamistas interesados puedan evaluarla y fondearla. | **Given** que completé mi perfil, **When** ingreso monto, tasa y plazo y confirmo la publicación, **Then** la solicitud queda registrada (on-chain y/o reflejada en el feed off-chain) y visible para los prestamistas con estado "abierta". | EPIC-LEND |
| US-LEND-02 | Feed de solicitudes con reputación visible | Como prestamista, deseo ver un feed de solicitudes abiertas con la reputación de cada solicitante, para decidir a quién fondear con base en su historial de repago. | **Given** que existen solicitudes abiertas, **When** accedo a la pantalla de feed, **Then** cada tarjeta de solicitud muestra monto, tasa, plazo y el score de reputación del prestatario correspondiente. | EPIC-LEND, EPIC-REP |
| US-LEND-03 | Fondeo de solicitud vía Smart Contract | Como prestamista, deseo fondear una solicitud que dispare una transacción al Smart Contract, para que los fondos se transfieran al prestatario y las condiciones/vencimiento queden registrados de forma inmutable. | **Given** que selecciono una solicitud abierta y confirmo el fondeo, **When** firmo la transacción desde mi wallet, **Then** el Smart Contract transfiere los fondos al prestatario, registra monto/tasa/vencimiento de forma inmutable y emite el evento `LoanFunded`. | EPIC-LEND |
| US-LEND-04 | Pago de préstamo desde la app | Como prestatario, deseo pagar mi préstamo (capital + interés) desde la app, para liberar los fondos al prestamista automáticamente vía el Smart Contract. | **Given** que tengo un préstamo activo y fondos suficientes en mi wallet, **When** confirmo el pago de capital + interés, **Then** el Smart Contract transfiere los fondos al prestamista, marca el préstamo como pagado y emite el evento `LoanRepaid` con indicador de puntualidad. | EPIC-LEND |
| US-LEND-05 | Consulta de estado del préstamo | Como prestamista o prestatario, deseo ver el estado de mis préstamos (activo, pagado, vencido/default) en todo momento, para hacer seguimiento sin depender de que otra parte me informe. | **Given** que tengo al menos un préstamo activo o histórico, **When** accedo a "Mis préstamos", **Then** la app lista cada préstamo con su estado actual, derivado del Smart Contract o de su reflejo indexado en LatiFi API. | EPIC-LEND |
| US-LEND-06 | Visualización en moneda local | Como prestatario o prestamista, deseo ver el monto del préstamo y las cuotas en moneda local además de en stablecoin, para entender el compromiso económico real sin hacer la conversión manualmente. | **Given** que estoy viendo el detalle de una solicitud o préstamo, **When** la pantalla carga los montos, **Then** se muestra el valor en stablecoin y su equivalente en moneda local, calculado con la tasa de cambio expuesta por LatiFi API. | EPIC-LEND, EPIC-API |
| **EPIC-REP** | Sistema de reputación | - | - | - |
| US-REP-01 | Actualización automática de reputación | Como prestatario, deseo que mi reputación se actualice automáticamente tras cada resultado de préstamo (pagado a tiempo, tardío, incumplido), para que mi historial refleje mi comportamiento real sin intervención manual. | **Given** que un préstamo cambia de estado (repagado o default), **When** el evento correspondiente es indexado, **Then** el score de reputación del prestatario se recalcula y queda disponible vía API sin acción manual del usuario. | EPIC-REP |
| US-REP-02 | Reputación híbrida on-chain/off-chain | Como prestamista, deseo que la reputación combine eventos on-chain (repago vía Smart Contract) con señales off-chain (perfil en LatiFi API), para evaluar también a solicitantes sin historial on-chain previo. | **Given** que un prestatario tiene perfil off-chain pero aún ningún préstamo on-chain, **When** consulto su reputación, **Then** el sistema muestra un score inicial basado en señales off-chain disponibles, que se ajusta con cada evento on-chain posterior. | EPIC-REP, EPIC-IDEN |
| US-REP-03 | Feed ordenado/destacado por reputación | Como prestamista, deseo que el feed ordene o destaque las solicitudes según el nivel de reputación del solicitante, para priorizar mi revisión hacia los perfiles de menor riesgo. | **Given** que el feed contiene múltiples solicitudes abiertas, **When** aplico el orden por defecto o el filtro de reputación, **Then** las solicitudes de prestatarios con mayor score aparecen primero o con una insignia visual distintiva. | EPIC-REP, EPIC-LEND |
| US-REP-04 | Decaimiento/recuperación gradual de reputación | Como prestatario, deseo que mi reputación decaiga o se recupere de forma gradual ante pagos parciales o tardíos, para que un solo incidente no me clasifique de forma binaria como "incumplido". | **Given** que registro un pago tardío o parcial, **When** el sistema recalcula mi score, **Then** el ajuste es proporcional a la severidad del incidente (no un salto a cero), y se recupera gradualmente con pagos puntuales posteriores. | EPIC-REP |
| **EPIC-API** | RESTful API propia (LatiFi API) | - | - | - |
| US-API-01 | Endpoint de historial de reputación | Como prestamista, deseo consultar el historial de reputación de un prestatario desde la app, para revisar el detalle detrás de su score antes de fondear. | **Given** que estoy en el detalle de una solicitud, **When** solicito ver el historial de reputación del prestatario, **Then** la app consume `GET /reputation/{address}/history` de LatiFi API y muestra los eventos que compusieron el score actual. | EPIC-API, EPIC-REP |
| US-API-02 | Conversión a moneda local vía API propia | Como usuario de LatiFi Wallet, deseo que la app obtenga la conversión a moneda local desde un endpoint propio de LatiFi API, para ver montos coherentes sin que la app dependa directamente de una API externa de terceros. | **Given** que la app necesita mostrar un monto en moneda local, **When** invoca `GET /exchange-rate/convert`, **Then** LatiFi API responde con el valor convertido usando su caché de tasas oficiales, sin exponer la API externa directamente al cliente móvil. | EPIC-API |
| TS-API-03 (Technical Story) | Indexado de eventos on-chain del Smart Contract | Como Developer, deseo que un servicio indexador escuche los eventos `LoanRequested`, `LoanFunded`, `LoanRepaid` y `LoanDefaulted` emitidos por el Smart Contract vía RPC, para que LatiFi API disponga de un espejo consultable del estado on-chain sin que la app consulte la blockchain en cada pantalla. | **Given** que el Smart Contract emite un evento de ciclo de vida de préstamo, **When** el indexador procesa el bloque correspondiente vía `eth_getLogs`/`ethLogFlowable`, **Then** el evento se traduce a un registro en la base de datos de LatiFi API dentro de una ventana de segundos, de forma idempotente (sin duplicar eventos ya procesados). | EPIC-API |
| TS-API-04 (Technical Story) | Checkpoint de último bloque procesado | Como Developer, deseo que el indexador mantenga un checkpoint del último bloque procesado, para reanudar la indexación tras una caída sin perder ni duplicar eventos. | **Given** que el proceso indexador se reinicia tras una falla, **When** vuelve a arrancar, **Then** retoma la lectura de eventos desde el último bloque confirmado como procesado, sin reprocesar el historial completo ni omitir bloques intermedios. | EPIC-API |
| TS-API-05 (Technical Story) | Autenticación de solicitudes REST por firma de wallet | Como Developer, deseo validar en LatiFi API que cada solicitud autenticada proviene de quien controla la dirección declarada, mediante verificación de firma sobre un desafío (nonce), para evitar suplantación de dirección en los endpoints REST. | **Given** que un cliente solicita un token de sesión, **When** firma el nonce entregado por la API con su wallet, **Then** la API verifica la firma contra la dirección declarada antes de emitir el JWT de sesión, rechazando cualquier firma inválida. | EPIC-API, EPIC-AUTH |
| **EPIC-LAND** | Landing Page institucional | - | - | - |
| US-LAND-01 | Landing page orientada a segmentos | Como visitante (prestatario o prestamista potencial), deseo entender el modelo de negocio de LatiFi desde la landing page, para decidir si quiero descargar o acceder a la app. | **Given** que un visitante llega a la landing page, **When** navega por las secciones de propuesta de valor, **Then** encuentra contenido diferenciado para el segmento prestatario y prestamista, con un llamado a la acción claro hacia la descarga/acceso de la app. | EPIC-LAND |
| US-LAND-02 | SEO, i18n y accesibilidad básica | Como visitante hispanohablante o angloparlante con o sin discapacidad, deseo navegar la landing page en mi idioma y con soporte de accesibilidad, para acceder al contenido sin barreras. | **Given** que un visitante accede a la landing page, **When** el navegador solicita el contenido, **Then** la página expone meta tags SEO básicos, soporta en_US/es_419 y cumple criterios ARIA verificables con un lector de pantalla. | EPIC-LAND |

### 3.3. Impact Mapping

El Impact Map traduce los Business Goals académicos del proyecto (no metas de negocio de producción real, dado el alcance de demo sobre testnet) en Actors, Impacts deseados y Deliverables, estos últimos trazables directamente a los User Stories de la sección 3.2.

**Business Goal (SMART):** Demostrar, ante el jurado del curso SI728, el ciclo completo de microcrédito P2P (solicitud → fondeo → ejecución en Smart Contract → repago → actualización de reputación) ejecutado end-to-end sobre Polygon Amoy, en una sesión de demo en vivo no mayor a 10 minutos, durante la entrega TF1 (semana 15).

**Business Goal secundario (SMART):** Evidenciar, para la semana 12 (TB2), un modelo de reputación híbrido on-chain/off-chain funcional que actualice el score de al menos un prestatario tras un ciclo de préstamo completo, sustentando la tesis diferenciadora del proyecto frente al modelo de colateral tradicional.

```
Business Goal: Demostrar el ciclo completo de préstamo end-to-end en Polygon Amoy (TF1, semana 15)
│
├── Actor: Prestatario (no bancarizado)
│   ├── Impact: Puede solicitar y recibir un microcrédito sin colateral ni historial bancario previo
│   │   └── Deliverable: US-AUTH-01, US-AUTH-03, US-IDEN-01, US-LEND-01, US-LEND-04, US-LEND-06
│   └── Impact: Confía en que el sistema refleja su comportamiento de pago de forma justa y gradual
│       └── Deliverable: US-REP-01, US-REP-02, US-REP-04
│
├── Actor: Prestamista (con capital ocioso)
│   ├── Impact: Puede evaluar el riesgo de un prestatario sin conocerlo, basado en reputación verificable
│   │   └── Deliverable: US-LEND-02, US-REP-03, US-API-01
│   └── Impact: Confía en que sus fondos se ejecutan de forma inmutable, sin depender de un intermediario centralizado
│       └── Deliverable: US-AUTH-02, US-AUTH-04, US-LEND-03, US-LEND-05
│
├── Actor: Jurado del curso SI728 (evaluador académico)
│   └── Impact: Verifica que el equipo aplicó correctamente DDD estratégico/táctico, Attribute-Driven Design y arquitectura Web3 híbrida
│       └── Deliverable: TS-API-03, TS-API-04, TS-API-05, Capítulo IV completo
│
└── Actor: Visitante web (prestatario/prestamista potencial, fuera de la demo técnica)
    └── Impact: Comprende la propuesta de valor y accede al canal de descarga de la app
        └── Deliverable: US-LAND-01, US-LAND-02
```

### 3.4. Product Backlog

El backlog prioriza primero el núcleo Auth + Identity + Lending que permite demostrar el préstamo end-to-end (condición de éxito explícita del proyecto), a continuación Reputation (que depende de al menos un ciclo de repago completo para tener datos que mostrar) y finalmente API/Landing Page en los aspectos que no bloquean el flujo core. La autenticación y el modelo no-custodial se ubican en las primeras posiciones, nunca al final, conforme lo exige el enunciado del curso. El Landing Page se incorpora desde el primer sprint como workstream paralelo, dado que no tiene dependencia técnica con el resto del sistema.

| # Orden | User Story ID | Título | Descripción | Story Points |
|---|---|---|---|---|
| 1 | US-AUTH-01 | Creación o importación de billetera digital | Billetera non-custodial creada en la app o importada con la frase de recuperación; la dirección es la identidad | 5 |
| 2 | US-AUTH-02 | Firma no custodial de transacciones | Firma de transacciones desde la wallet del usuario, sin custodia de llaves | 5 |
| 3 | TS-API-05 | Autenticación de solicitudes REST por firma de wallet | Verificación de firma sobre nonce para autenticar llamadas REST | 5 |
| 4 | US-IDEN-01 | Registro de perfil ligero | Captura de nombre/contacto como base de resistencia a Sybil | 2 |
| 5 | US-IDEN-02 | Exposición de perfil vía API propia | Endpoint REST de perfil vinculado a dirección on-chain | 3 |
| 6 | US-LAND-01 | Landing page orientada a segmentos | Estructura y contenido base de la landing (paralelo, sprint 1) | 3 |
| 7 | US-AUTH-03 | Onboarding progresivo en lenguaje simple | Flujo de onboarding sin jerga cripto previo a conectar wallet | 5 |
| 8 | US-LEND-01 | Publicación de solicitud de préstamo | Registro de monto, tasa e interés de una solicitud | 5 |
| 9 | US-LEND-03 | Fondeo de solicitud vía Smart Contract | Transacción de fondeo, escrow y transferencia al prestatario | 8 |
| 10 | US-AUTH-04 | Retroalimentación de estado de transacción | Estados pendiente/confirmando/confirmada/fallida en UI | 3 |
| 11 | TS-API-03 | Indexado de eventos on-chain del Smart Contract | Servicio indexador de `LoanRequested`/`LoanFunded`/`LoanRepaid`/`LoanDefaulted` | 8 |
| 12 | TS-API-04 | Checkpoint de último bloque procesado | Reanudación idempotente del indexador tras una caída | 3 |
| 13 | US-LEND-02 | Feed de solicitudes con reputación visible | Listado de solicitudes abiertas con score del solicitante | 5 |
| 14 | US-LEND-04 | Pago de préstamo desde la app | Repago de capital + interés vía Smart Contract | 8 |
| 15 | US-LEND-05 | Consulta de estado del préstamo | Vista de estado activo/pagado/vencido para ambas partes | 3 |
| 16 | US-LAND-02 | SEO, i18n y accesibilidad básica | Meta tags, en_US/es_419 y cumplimiento ARIA de la landing | 3 |
| 17 | US-API-02 | Conversión a moneda local vía API propia | Endpoint propio de conversión, consumiendo una API externa de FX | 3 |
| 18 | US-LEND-06 | Visualización en moneda local | Presentación de montos en stablecoin y moneda local en la UI | 2 |
| 19 | US-REP-01 | Actualización automática de reputación | Recalculo de score tras cada resultado de préstamo indexado | 5 |
| 20 | US-REP-02 | Reputación híbrida on-chain/off-chain | Combinación de señales off-chain (perfil) y on-chain (repago) | 8 |
| 21 | US-API-01 | Endpoint de historial de reputación | Exposición del detalle de eventos detrás del score | 3 |
| 22 | US-REP-03 | Feed ordenado/destacado por reputación | Orden u badge de reputación sobre el feed existente | 3 |
| 23 | US-REP-04 | Decaimiento/recuperación gradual de reputación | Ajuste proporcional de score ante pagos parciales/tardíos | 5 |

<div style="page-break-after: always;"></div>

## Capítulo IV: Strategic-Level Software Design

### 4.1. Strategic-Level Attribute-Driven Design

#### Design Purpose

El propósito de este diseño estratégico es resolver, a nivel arquitectónico, la tensión central de LatiFi: ofrecer microcrédito a personas no bancarizadas sin colateral y sin un backend centralizado que decida sobre el dinero, sustituyendo ambos mecanismos por un Smart Contract inmutable como fuente de verdad del ciclo de préstamo y por un modelo de reputación híbrido on-chain/off-chain que resuelve el problema de "cold start" de usuarios sin historial crediticio previo (segmento Prestatario) ni historial on-chain previo (segmento Prestamista evaluando riesgo). El diseño debe, por tanto, garantizar simultáneamente que la lógica de fondeo/repago nunca se duplique fuera del contrato y que la experiencia de usuario sea viable para personas sin familiaridad cripto previa, dos atributos de calidad en tensión que el Attribute-Driven Design (ADD) hace explícitos antes de comprometerse con una estructura de componentes.

#### Attribute-Driven Design Inputs

**Primary Functionality**

Las siguientes User Stories de la sección 3.2 concentran el mayor impacto arquitectónico, por requerir coordinación entre Smart Contract, indexador y LatiFi API, y por sostener el Core Value del proyecto:

| Epic/User Story ID | Título | Descripción | Criterios de Aceptación (Gherkin) | Relacionado con (Epic ID) |
|---|---|---|---|---|
| US-LEND-03 | Fondeo de solicitud vía Smart Contract | Como prestamista, deseo fondear una solicitud que dispare una transacción al Smart Contract, para que los fondos se transfieran al prestatario y las condiciones/vencimiento queden registrados de forma inmutable. | **Given** que selecciono una solicitud abierta y confirmo el fondeo, **When** firmo la transacción desde mi wallet, **Then** el Smart Contract transfiere los fondos al prestatario, registra monto/tasa/vencimiento de forma inmutable y emite el evento `LoanFunded`. | EPIC-LEND |
| US-LEND-04 | Pago de préstamo desde la app | Como prestatario, deseo pagar mi préstamo (capital + interés) desde la app, para liberar los fondos al prestamista automáticamente vía el Smart Contract. | **Given** que tengo un préstamo activo y fondos suficientes, **When** confirmo el pago, **Then** el Smart Contract transfiere los fondos al prestamista, marca el préstamo como pagado y emite `LoanRepaid` con indicador de puntualidad. | EPIC-LEND |
| US-REP-02 | Reputación híbrida on-chain/off-chain | Como prestamista, deseo que la reputación combine eventos on-chain con señales off-chain, para evaluar también a solicitantes sin historial on-chain previo. | **Given** que un prestatario tiene perfil off-chain pero aún ningún préstamo on-chain, **When** consulto su reputación, **Then** el sistema muestra un score inicial off-chain que se ajusta con cada evento on-chain posterior. | EPIC-REP, EPIC-IDEN |

**Quality Attribute Scenarios**

| Atributo | Fuente | Estímulo | Artefacto | Entorno | Respuesta | Medida |
|---|---|---|---|---|---|---|
| Seguridad | Usuario malicioso (contrato atacante) | Intenta explotar una función de repago/fondeo mediante un patrón de reentrancy (callback recursivo antes de actualizar el estado) | Smart Contract `LoanAgreement` | Producción de demo en Polygon Amoy testnet | El contrato revierte la transacción de reentrada y preserva el estado consistente del préstamo | 0 fondos drenados en pruebas de reentrancy (Foundry); función protegida con `nonReentrant` de OpenZeppelin verificada en el 100% de las funciones que mueven fondos |
| Disponibilidad | Proveedor de RPC (Alchemy/Infura/público) | El endpoint RPC de Polygon Amoy utilizado por el indexador y la app deja de responder o excede el rate limit durante la demo | Event Indexer, LatiFi Wallet | Demo en vivo ante el jurado | El sistema reintenta con backoff y, si el indexador queda desactualizado, la app puede reconciliar el estado leyendo directamente del contrato ante una acción crítica (fondeo/pago) | Tiempo de recuperación del indexador menor a 60 segundos tras restablecerse el RPC; 0 pantallas de "loan feed" bloqueadas indefinidamente durante la demo |
| Usabilidad | Prestatario no bancarizado, no-cripto-nativo | Abre la app por primera vez sin haber usado nunca una wallet | LatiFi Wallet (flujo de onboarding) | Primer uso, dispositivo Android de gama media (iOS queda como trabajo futuro) | El usuario completa el onboarding y conecta su wallet exitosamente sin abandonar el flujo por confusión con jerga cripto | Tasa de finalización del onboarding superior al 80% en pruebas de usabilidad con usuarios no técnicos (n≥5); cero términos técnicos sin explicación en pantalla (seed phrase, gas, nonce) |
| Rendimiento (tiempo de confirmación de transacción) | Prestamista o prestatario | Envía una transacción de fondeo o repago desde la app | Smart Contract + red Polygon Amoy | Testnet Polygon Amoy, condiciones normales de red | La app refleja el estado "confirmada" apenas el bloque que contiene la transacción alcanza el número de confirmaciones definido como seguro para la demo | Confirmación visible en la UI en menos de 15 segundos desde el envío, bajo condiciones normales de la testnet (chain ID 80002) |
| Integridad de datos (consistencia on-chain/off-chain) | Evento emitido por el Smart Contract | El contrato emite `LoanRepaid` tras un pago exitoso | Event Indexer, LatiFi API/DB | Operación normal, sin caída de RPC | El indexador procesa el evento de forma idempotente y actualiza el estado reflejado en LatiFi API sin duplicar ni perder el evento | Job de indexado con checkpoint de último bloque procesado; 0 eventos duplicados o perdidos en pruebas de reinicio forzado del indexador |

**Constraints**

| Technical Story | Restricción | Origen |
|---|---|---|
| TC-01 | El despliegue de los Smart Contracts se realiza exclusivamente sobre Polygon Amoy (testnet, chain ID 80002); no se contempla mainnet ni dinero real en ningún momento del proyecto. | Restricciones y alcance definidos para el proyecto |
| TC-02 | LatiFi no debe custodiar llaves privadas de los usuarios bajo ninguna circunstancia; el modelo de autenticación es estrictamente no-custodial (wallet-based). | Restricciones y alcance definidos para el proyecto |
| TC-03 | La aplicación móvil debe construirse en tecnología nativa y están explícitamente prohibidos los frameworks híbridos (React Native, Flutter, Ionic). El equipo construye solo la versión Android con Kotlin; Swift para iOS queda como trabajo futuro. | Restricciones de stack tecnológico móvil definidas para el proyecto |
| TC-04 | El backend REST propio debe implementarse en Spring Boot, ASP.NET Core o NestJS (Java/C#/TypeScript), sin excepción a esas tres opciones. | Restricciones de stack tecnológico backend definidas para el proyecto |
| TC-05 | Toda la lógica de matching, fondeo, repago y determinación de default debe vivir en el Smart Contract; queda prohibido un backend centralizado que re-decida el estado del préstamo. | Alcance definido para el proyecto; identificado como anti-patrón durante el análisis de arquitectura |
| TC-06 | El control de versiones debe seguir GitFlow con Conventional Commits sobre GitHub, requisito de calificación del curso. | Restricciones definidas para el proyecto |
| TC-07 | La Landing Page y las aplicaciones Web/Frontend deben cumplir i18n (en_US, es_419) y accesibilidad (ARIA). | Restricciones definidas para el proyecto |

**Architectural Drivers Backlog**

| Driver ID | Título | Descripción | Importancia para Stakeholders | Impacto en Architecture Technical Complexity |
|---|---|---|---|---|
| DR-01 | Inmutabilidad y no-duplicación de la lógica de préstamo | El ciclo de vida del préstamo (fondeo, escrow, repago, default) debe residir únicamente en el Smart Contract, sin una copia de la lógica en el backend | Alta: es el Core Value del proyecto y una restricción explícita del curso | Alta: exige diseñar LatiFi API como consumidor puro de eventos, nunca como fuente de verdad alternativa |
| DR-02 | Seguridad del Smart Contract ante reentrancy | El contrato mueve fondos de terceros; una vulnerabilidad de reentrancy comprometería la integridad de todo el sistema | Alta: riesgo ético/profesional explícitamente evaluado por la rúbrica del curso | Alta: requiere patrón checks-effects-interactions, `ReentrancyGuard` y suite de pruebas de ataque dedicada |
| DR-03 | Reputación híbrida on-chain/off-chain | La reputación debe combinar señales on-chain y off-chain para resolver el cold-start de usuarios sin historial previo | Alta: es el diferenciador competitivo declarado frente a modelos puramente on-chain (RociFi) | Alta: exige un modelo de dominio en Reputation Context capaz de fusionar dos fuentes de eventos con distinta cadencia y confiabilidad |
| DR-04 | Usabilidad del onboarding para no-cripto-nativos | El segmento objetivo (no bancarizado) no tiene experiencia previa con wallets, gas o firmas | Alta: sin este atributo el sistema es inutilizable para el segmento objetivo, independientemente de su corrección técnica | Media: impacta principalmente el diseño de UI/UX y la secuencia de pantallas, con bajo acoplamiento a la arquitectura backend |
| DR-05 | Disponibilidad ante caída del RPC de Polygon Amoy | El indexador y la app dependen de un proveedor RPC externo fuera del control del equipo | Media-Alta: riesgo concreto de falla en vivo durante la demo ante el jurado | Media: exige estrategia de reintentos/backoff y reconciliación de lectura directa al contrato, sin rediseño estructural |
| DR-06 | Tiempo de confirmación de transacción perceptible por el usuario | Las transacciones blockchain no son instantáneas; el usuario necesita saber en qué estado está su acción | Media: afecta la percepción de confiabilidad del sistema durante la demo | Media: exige manejo de estados asíncronos en la UI y polling/subscripción al estado de la transacción |
| DR-07 | Restricción de stack (mobile nativo, backend acotado, solo testnet) | El curso fija de antemano tecnologías y entorno de despliegue permitidos | Alta: no negociable, condiciona toda decisión de stack | Baja-Media: no añade complejidad de diseño per se, pero elimina alternativas (p. ej. cross-platform) que simplificarían el desarrollo |
| DR-08 | No-custodia de llaves privadas | Ninguna llave privada de usuario puede residir ni transitar por servidores de LatiFi | Alta: es un requisito ético/regulatorio y arquitectónico explícito | Media: exige delegar completamente la firma a SDKs de wallet (Reown/WalletConnect) sin puntos intermedios de custodia |

#### Architectural Design Decisions

Las siguientes decisiones, ya adoptadas por el equipo durante el diseño técnico, se presentan como matrices de evaluación de patrones candidatos (Candidate Pattern Evaluation Matrix), documentando explícitamente el trade-off considerado.

**Decisión 1: Modelo de riesgo (reputación híbrida on/off-chain vs. sobrecolateralización vs. reputación puramente on-chain)**

| Patrón candidato | Pro | Con |
|---|---|---|
| Sobrecolateralización (estilo Aave/Compound) | Patrón de DeFi más probado y documentado; menor riesgo de diseño de dominio nuevo | Contradice la premisa de servir a no bancarizados, que por definición no tienen activos cripto que bloquear; duplica complejidad de Smart Contract sin beneficio para la rúbrica del curso |
| Reputación puramente on-chain (estilo RociFi) | Modelo simple de implementar; toda la fuente de verdad vive en un solo lugar (el contrato) | Falla exactamente para el segmento objetivo: un usuario nuevo sin wallet con historial previo no tiene señal on-chain que evaluar (cold-start), lo que deja a la mayoría de prestatarios reales sin score útil |
| **Reputación híbrida on-chain/off-chain (seleccionada)** | Resuelve el cold-start combinando perfil off-chain (LatiFi API) con historial de repago on-chain (Smart Contract vía indexador); es el diferenciador competitivo explícito del proyecto frente a Goldfinch/RociFi/Aave | Introduce una fuente adicional de complejidad de dominio (fusionar dos tipos de señal con distinta confiabilidad) y depende de que el indexador mantenga sincronía razonable entre ambas fuentes |

**Decisión 2: Traducción de eventos on-chain (indexer custom vs. subgraph de The Graph)**

| Patrón candidato | Pro | Con |
|---|---|---|
| Subgraph (The Graph) | Solución estándar de la industria DeFi para indexado de eventos; infraestructura de queries GraphQL ya resuelta y probada en producción | Curva de aprendizaje y setup adicional (definición de manifest, despliegue en un nodo de indexado) desproporcionados para una demo académica de 15 semanas sobre testnet; agrega una dependencia de infraestructura externa no exigida por el curso |
| **Indexer custom embebido en LatiFi API (seleccionado)** | Control total sobre el formato del evento consumido por Reputation/Profile; reutiliza el mismo proceso/stack que el resto del backend (Spring Boot/NestJS/ASP.NET Core), sin infraestructura adicional; suficiente para el volumen de eventos de una demo | Requiere implementar manualmente el manejo de checkpoint de bloque, reintentos y (en teoría) reorgs, responsabilidad que un servicio como The Graph resolvería de fábrica |
| Polling directo desde la app móvil (sin indexador) | Cero infraestructura adicional | Explícitamente descartado como anti-patrón durante el análisis de arquitectura (Anti-Pattern 2 y 3): lento, costoso en batería/datos y no escala más allá de un puñado de préstamos; bloquea la construcción del feed de solicitudes |

**Decisión 3: Toolchain de contratos (Foundry vs. Hardhat como framework primario)**

| Patrón candidato | Pro | Con |
|---|---|---|
| Hardhat como framework primario | Ecosistema JavaScript/TypeScript más amplio; facilita compartir tooling con un eventual landing page en JS | Ciclo de compilación/test más lento que Foundry (hasta 20x); indirección de un test runner externo sobre Solidity |
| **Foundry como framework primario (seleccionado)** | Tests nativos en Solidity sin indirección de un runner JS; ciclos de compilación/test 2-20x más rápidos, crítico para 15 semanas de curso; es el toolchain que usan flujos de estilo auditoría de seguridad, alineado con el Driver DR-02 (reentrancy) | Menor integración nativa con un stack TypeScript compartido; el equipo debe mantener Hardhat como secundario solo para scripts de despliegue/verificación si necesita tooling JS puntual |

#### Quality Attribute Scenario Refinements

**Refinamiento 1: Seguridad del Smart Contract ante reentrancy**

- **Scenario:** Un actor malicioso despliega un contrato receptor que, al recibir la transferencia de fondos de una llamada a `repayLoan()` o `fundLoan()`, invoca recursivamente la misma función antes de que el `LoanAgreement` actualice su estado interno, con el objetivo de drenar fondos del contrato.
- **Business Goals:** Preservar la integridad de los fondos de los prestamistas dentro del Smart Contract, condición sin la cual el flujo completo de préstamo no puede demostrarse ni evaluarse éticamente frente al jurado.
- **Relevant Quality Attributes:** Seguridad; en menor medida, Fiabilidad (el estado del préstamo debe permanecer consistente tras el intento de ataque).
- **Stimulus Source:** Un usuario o contrato malicioso que interactúa con `LoanAgreement` desde una dirección arbitraria en Polygon Amoy.
- **Environment:** Entorno de testnet Polygon Amoy, en cualquier momento de operación del contrato (no solo durante la demo).
- **Artifact:** Las funciones del Smart Contract `LoanAgreement` que mueven fondos (`fundLoan`, `repayLoan`, cualquier función de liberación de escrow).
- **Response:** La función revierte la transacción de reentrada mediante el modificador `nonReentrant` de OpenZeppelin y el patrón checks-effects-interactions (el estado se actualiza antes de la transferencia externa), de modo que ningún fondo adicional se transfiere en la llamada recursiva.
- **Response Measure:** 0 fondos drenados en la suite de pruebas de reentrancy (Foundry, con un contrato atacante de prueba); 100% de las funciones que mueven fondos cubiertas por `nonReentrant` y por al menos un test que simula un receptor malicioso.
- **Questions:** ¿El equipo dispone de tiempo en el cronograma (semanas 4-7, fase de contratos) para escribir contratos atacantes de prueba, no solo tests de camino feliz? ¿OpenZeppelin 5.x cubre todas las funciones críticas o se requiere un guard adicional en alguna ruta no estándar (p. ej. default/timeout)?
- **Issues:** El nivel de rigor de testing de seguridad exigido por la rúbrica del curso no está cuantificado en la documentación del proyecto; se recomienda validar con el profesor si se espera una auditoría formal o basta con la suite de tests de reentrancy/overflow ya planificada.

**Refinamiento 2: Usabilidad del onboarding para no-cripto-nativos**

- **Scenario:** Un prestatario potencial, adulto no bancarizado sin experiencia previa con billeteras digitales, instala LatiFi Wallet por primera vez y debe completar el onboarding y conectar su wallet antes de poder solicitar un préstamo.
- **Business Goals:** Validar, dentro del alcance académico, que el modelo "reputación en vez de colateral" es utilizable por el segmento objetivo real y no solo por usuarios cripto-nativos del propio equipo, sustentando la sección de Lean UX/UX Research de la rúbrica.
- **Relevant Quality Attributes:** Usabilidad; secundariamente, Accesibilidad (i18n es_419/en_US aplicado también dentro de la app, no solo en la landing page).
- **Stimulus Source:** Un usuario final representativo del segmento Prestatario (no bancarizado, primer contacto con cripto), en una sesión de prueba de usabilidad o en la demo en vivo.
- **Environment:** Primer uso de la app, en un dispositivo Android de gama media, sin conocimiento previo de conceptos como seed phrase, gas o dirección on-chain.
- **Artifact:** El flujo de onboarding de LatiFi Wallet (pantallas previas a "Conectar billetera") y el propio flujo de conexión de wallet vía Reown WalletKit/AppKit.
- **Response:** El usuario completa cada paso del onboarding en lenguaje simple (sin jerga cripto), entiende qué implica conectar su wallet antes de hacerlo, y logra conectar exitosamente su billetera sin abandonar el flujo por confusión.
- **Response Measure:** Tasa de finalización del onboarding superior al 80% en una prueba de usabilidad con al menos 5 usuarios no técnicos representativos del segmento; cero abandonos atribuibles a terminología no explicada, verificado en la sesión de validación.
- **Questions:** ¿Las entrevistas de validación del Capítulo II incluirán participantes genuinamente no bancarizados, o solo compañeros de clase con perfil técnico? ¿Qué tan realista es medir "abandono por confusión" sin una sesión moderada de usabilidad grabada?
- **Issues:** Esta métrica depende de datos de validación que hoy no existen; el equipo debe programar al menos una ronda de prueba de usabilidad con usuarios no técnicos antes de TB2, no dejarla para después de construida la app completa.

### 4.2. Strategic-Level Domain-Driven Design

#### Bounded Contexts

Se adoptan los cinco bounded contexts identificados durante la investigación de arquitectura como propuesta de partida para el diseño estratégico de LatiFi:

- **Lending Context.** Dueño del ciclo de vida completo del préstamo: solicitud de términos, fondeo, escrow, repago y determinación de default. Vive enteramente on-chain, en el Smart Contract `LoanAgreement`/`LoanFactory`. Es la fuente de verdad del sistema y no depende de ningún otro contexto para operar.
- **Identity/Wallet Context.** Responsable de la conexión de wallet, la vinculación de una dirección on-chain a un perfil de usuario y la verificación de firmas que autentican llamadas a la LatiFi API. Vive parcialmente en el cliente móvil (SDK de wallet) y parcialmente como una porción delgada de verificación dentro de LatiFi API.
- **Reputation Context.** Responsable de calcular y exponer el score de reputación híbrido, a partir de eventos on-chain indexados (repago, default) y señales off-chain (perfil). Vive en LatiFi API + base de datos, alimentado por el Event Indexer.
- **Exchange Rate Context.** Responsable de obtener, cachear y exponer tasas de cambio de stablecoin a moneda local. Vive en LatiFi API + base de datos, sin dependencia de ningún otro contexto salvo el proveedor externo de FX.
- **Marketing/Landing Context.** Responsable del sitio institucional público: propuesta de valor, SEO, i18n y accesibilidad. Vive como sitio estático completamente desacoplado del resto del sistema.

#### EventStorming

![EventStorming](resources/Cap1/eventstorming.png)

Los Domain Events identificados a partir del flujo de dominio son los siguientes:

- `ProfileCreated`: se registra un perfil ligero vinculado a una dirección on-chain (Identity/Wallet Context).
- `LoanRequested`: un prestatario publica una solicitud de préstamo con monto, tasa y plazo (Lending Context; decisión pendiente sobre si se emite como evento on-chain o se origina off-chain, ver Domain Message Flows más abajo).
- `LoanFunded`: un prestamista fondea una solicitud y el Smart Contract transfiere los fondos al prestatario (Lending Context).
- `LoanRepaid`: el prestatario repaga capital + interés y el contrato libera los fondos al prestamista (Lending Context).
- `LoanDefaulted`: el préstamo supera su plazo de vencimiento sin ser repagado (Lending Context).
- `ReputationUpdated`: el Reputation Context recalcula el score de un prestatario tras un evento de repago o default indexado (Reputation Context).
- `ExchangeRateRefreshed`: el Exchange Rate Context actualiza su caché de tasas desde el proveedor externo (Exchange Rate Context).

![End to end lending flow](resources/Cap1/end%20to%20end%20lending%20flow.png)  

#### Candidate Context Discovery

Aplicando el razonamiento start-with-value a la problemática de LatiFi, los cinco bounded contexts anteriores se justifican de la siguiente manera:

El **Lending Context** se aísla primero porque concentra el valor central del negocio (el Core Value del proyecto depende exclusivamente de que este ciclo funcione) y porque, al vivir on-chain, tiene un ciclo de vida de desarrollo y despliegue completamente distinto (Solidity/Foundry, deploy a Polygon Amoy) del resto del sistema (REST y Kotlin, con Swift para iOS como trabajo futuro). Separarlo temprano evita que su lógica se filtre o duplique hacia otros contextos, riesgo que la investigación de arquitectura señala explícitamente como anti-patrón.

El **Identity/Wallet Context** se separa porque resuelve un problema de negocio distinto (quién es el usuario) del que resuelve Lending (qué puede hacer ese usuario con dinero). Aunque físicamente es delgado (una porción vive en el cliente, otra en la API), su valor de negocio es autónomo: sin identidad verificable no hay resistencia a Sybil, precondición de todo el modelo de reputación.

El **Reputation Context** se separa de Identity porque, aunque ambos giran en torno al mismo usuario, cada uno entrega un valor de negocio distinto y con una tasa de cambio distinta: Identity cambia poco (una vez creado el perfil, rara vez se actualiza), mientras que Reputation cambia con cada evento de préstamo. Fusionarlos generaría un modelo que mezcla datos de baja y alta cadencia de cambio, dificultando su evolución independiente. Este es precisamente el diferenciador competitivo del proyecto (reputación híbrida), por lo que merece su propio contexto con reglas de negocio propias.

El **Exchange Rate Context** se separa por tener una razón de cambio y una fuente de datos completamente ajena al resto del dominio (un proveedor externo de FX, sin relación con préstamos ni reputación); acoplarlo a Reputation o Lending introduciría una dependencia espuria y, peor aún, el riesgo de que una tasa de cambio termine influyendo (aunque sea indirectamente) en la lógica de negocio del contrato, riesgo que la investigación de arquitectura señala como pitfall de "oracle manipulation".

El **Marketing/Landing Context** se separa porque no comparte modelo de dominio, usuarios autenticados ni ciclo de despliegue con ningún otro contexto; es, en términos de DDD estratégico, un "Generic Subdomain" que aporta valor de adquisición pero no valor transaccional, y su total independencia técnica permite que un sub-equipo lo desarrolle en paralelo desde la semana 1 sin coordinarse con el resto.

![Strategic Context Map](resources/Cap1/strategic%20context%20map.png)

#### Domain Message Flows Modeling

El flujo de mensajes del happy path entre bounded contexts es el siguiente. El **Prestatario**, tras haber sido dado de alta por el **Identity/Wallet Context** (evento `ProfileCreated`), publica una solicitud de préstamo; esta acción origina un mensaje que el **Lending Context** registra como los términos de una solicitud abierta (evento `LoanRequested`, con la decisión pendiente sobre si nace on-chain o como estado off-chain reflejado luego on-chain). El **Prestamista**, al navegar el feed servido por LatiFi API, consulta al **Reputation Context** el score del solicitante antes de decidir fondear; si decide fondear, envía un comando que el **Lending Context** ejecuta on-chain, transfiriendo fondos al prestatario y emitiendo el evento `LoanFunded`. Este evento cruza la frontera on-chain/off-chain a través del Event Indexer, que actúa como traductor (anti-corruption layer) hacia el **Reputation Context**, el cual aún no actualiza el score en este punto (el fondeo no es, por sí mismo, una señal de comportamiento de pago). Cuando el prestatario repaga el préstamo, el **Lending Context** emite `LoanRepaid`; nuevamente el indexador traduce este evento y esta vez sí dispara en el **Reputation Context** el recálculo del score (evento `ReputationUpdated`), combinando esta señal on-chain con las señales off-chain ya existentes en el perfil del **Identity/Wallet Context**. En paralelo, y sin relación causal con el ciclo de préstamo, el **Exchange Rate Context** refresca periódicamente su caché de tasas para que tanto el feed del Lending Context como las pantallas de detalle del prestatario puedan mostrar montos en moneda local en cualquier punto del flujo.

![Domain Storytelling](resources/Cap1/Domein%20story%20telling%20.png)

#### Bounded Context Canvases

**Especificación Táctica de Fronteras:** La acotación formal de contratos internos, invariantes y subyacentes se consolida mediante canvases tácticos individuales.

![Bounded Context Canvases](resources/Cap1/Bounded%20Conext%20Canvases.png)

#### Context Mapping

**Topología de Interacción y Contratos:** Las relaciones entre los cinco bounded contexts, en términos de los patrones estratégicos de DDD, se formalizan de la siguiente manera:

- **Lending Context → Identity/Wallet Context y Reputation Context: Upstream/Downstream con Anti-Corruption Layer.** Lending es upstream puro: no depende de ningún otro contexto para funcionar (el contrato no consulta perfiles ni scores para ejecutar fondeo o repago). Reputation e Identity/Wallet son downstream, y consumen los eventos de Lending exclusivamente a través del Event Indexer, que actúa como Anti-Corruption Layer: traduce logs crudos de blockchain (topics, valores hex-encoded, números de bloque) en eventos de dominio legibles (`BorrowerRepaidOnTime`, por ejemplo) antes de que lleguen a Reputation. Esto protege a Reputation de cualquier cambio en la forma del ABI o del esquema de eventos del contrato.
- **Reputation Context respecto de Lending Context: Conformist.** Reputation no negocia ni influye en qué eventos emite el contrato; se adapta enteramente a lo que Lending decide emitir. Esta relación es deliberada: es la única forma de preservar la garantía de que la lógica de préstamo vive exclusivamente on-chain (Driver DR-01).
- **Reputation Context ↔ Identity/Wallet Context: Customer/Supplier.** Reputation es cliente de Identity/Wallet en el sentido de que necesita el perfil (señales off-chain) como insumo para calcular el score híbrido; Identity/Wallet, como proveedor, expone ese perfil vía un contrato de datos estable (el perfil vinculado a una dirección), sin conocer ni depender de cómo Reputation lo usa internamente.
- **Exchange Rate Context: Separate Ways respecto de todos los demás.** No comparte modelo de dominio con ningún otro contexto ni depende de ellos; su única relación externa es con el proveedor de FX de terceros. Esta independencia es intencional: evita que una fluctuación o falla de la tasa de cambio contamine la lógica de negocio de Lending o Reputation.
- **Marketing/Landing Context: Separate Ways respecto de todos los demás.** Al igual que Exchange Rate, no comparte modelo ni tiene dependencias técnicas con el resto del sistema; en términos de Context Mapping es un contexto aislado por diseño, lo que le permite desarrollarse y desplegarse de forma completamente independiente.
- **LatiFi API como Shared Kernel interno (a nivel de infraestructura, no de dominio).** Aunque Identity/Wallet, Reputation y Exchange Rate son bounded contexts distintos a nivel de dominio, para el alcance del curso se co-despliegan dentro del mismo proceso de LatiFi API (Spring Boot/NestJS/ASP.NET Core), compartiendo infraestructura transversal (autenticación, configuración, acceso a base de datos) mediante un módulo `shared`. Este acoplamiento es explícitamente de infraestructura, no de modelo de dominio: cada contexto mantiene sus propios agregados y lenguaje ubicuo dentro de su paquete, de modo que la separación lógica exigida por la rúbrica de DDD se preserva aun cuando el despliegue físico esté unificado por restricciones de alcance académico.

### 4.3. Software Architecture

#### 4.3.1. Software Architecture System Landscape and Context Level Diagrams

**System Landscape Diagram (C4)**

El panorama de sistemas reúne todo lo que el equipo construye y todo lo que LatiFi usa sin construirlo. Cuatro sistemas propios sirven a tres tipos de persona: la aplicación LatiFi Wallet para el prestatario y el prestamista, la LatiFi API que guarda perfiles, reputación y tasas, los Smart Contracts LoanBook y MockStablecoin que ejecutan el préstamo, y la Landing Page que atiende al visitante. Cinco sistemas externos completan el panorama: la red Polygon Amoy, donde viven los contratos; el proveedor de tasas de cambio (open.er-api.com, de ExchangeRate-API); la billetera propia del usuario, que puede ser MetaMask u otra compatible con WalletConnect; el relay de Reown, que lleva las solicitudes de firma; y Firebase App Distribution, el canal por el que la app Android llega a los testers.

La app no guarda ninguna llave privada. Cada firma se pide a la billetera del usuario a través de Reown, y la billetera firma y envía la transacción a Polygon Amoy. Esta decisión reemplaza el modelo de llave propia del ADR-0001, que se tomó en la Fase 5; la nota que lo deja escrito en el propio ADR queda para la Fase 8.

```mermaid
graph TD
    Prestatario["Prestatario<br/>(no bancarizado)"]
    Prestamista["Prestamista<br/>(capital ocioso)"]
    Visitante["Visitante Web"]

    subgraph "Sistemas de LatiFi"
        Wallet["LatiFi Wallet<br/>[Sistema de Software]<br/>App móvil Android, sin llaves"]
        API["LatiFi API<br/>[Sistema de Software]<br/>Perfil, reputación, tasas e indexador"]
        SC["Smart Contracts<br/>[Sistema de Software]<br/>LoanBook y MockStablecoin"]
        Landing["Landing Page<br/>[Sistema de Software]<br/>Sitio institucional"]
    end

    UserWallet["Billetera del usuario<br/>[Sistema Externo]<br/>MetaMask u otra con WalletConnect"]
    Reown["Relay de Reown<br/>[Sistema Externo]"]
    Firebase["Firebase App Distribution<br/>[Sistema Externo]"]
    Polygon["Polygon Amoy<br/>[Sistema Externo]"]
    FXApi["Proveedor de tasas de cambio<br/>[Sistema Externo]<br/>open.er-api.com"]

    Prestatario --> Wallet
    Prestamista --> Wallet
    Prestatario -->|"Aprueba cada firma"| UserWallet
    Prestamista -->|"Aprueba cada firma"| UserWallet
    Visitante --> Landing
    Wallet -->|"REST/HTTPS"| API
    Wallet -->|"Solicita la firma"| Reown
    Reown -->|"Entrega la solicitud"| UserWallet
    UserWallet -->|"Firma y envía la transacción"| Polygon
    SC -->|"Se ejecuta en"| Polygon
    API -->|"Lee eventos"| Polygon
    API -->|"Consulta cotizaciones"| FXApi
    Landing -.->|"Enlaza a la descarga"| Firebase
    Firebase -.->|"Entrega la app a los testers"| Wallet

    style Wallet fill:#1168bd,color:#fff
    style API fill:#1168bd,color:#fff
    style SC fill:#1168bd,color:#fff
    style Landing fill:#1168bd,color:#fff
    style UserWallet fill:#999,color:#fff
    style Reown fill:#999,color:#fff
    style Firebase fill:#999,color:#fff
    style Polygon fill:#999,color:#fff
    style FXApi fill:#999,color:#fff
```

**Context Level Diagram (C4, Nivel 1)**

El sistema LatiFi se representa como una única caja negra ("LatiFi Platform") rodeada de personas y de sistemas externos. El **Prestatario** y el **Prestamista** usan la app móvil LatiFi Wallet para solicitar, fondear, pagar y consultar préstamos, y aprueban cada firma en su propia billetera. La **billetera del usuario** y el **relay de Reown** son sistemas externos: LatiFi Platform les pide una firma y la billetera envía la transacción a **Polygon Amoy**, la red externa que actúa como libro mayor inmutable del ciclo de préstamo y de la que LatiFi Platform también lee eventos. El **proveedor de tasas de cambio** es otro sistema externo, que LatiFi Platform consume en un solo sentido para obtener cotizaciones de stablecoin a moneda local. **Firebase App Distribution** entrega la app a los testers. El **Visitante web** solo usa la porción pública de LatiFi Platform, la Landing Page, y no necesita billetera ni cuenta.

```mermaid
graph TD
    Prestatario["Prestatario<br/>(no bancarizado)"]
    Prestamista["Prestamista<br/>(capital ocioso)"]
    Visitante["Visitante Web<br/>(prestatario/prestamista potencial)"]
    LatiFi["LatiFi Platform<br/>[Sistema de Software]<br/>Plataforma de microcréditos P2P<br/>basada en reputación, sin llaves en la app"]
    UserWallet["Billetera del usuario<br/>[Sistema Externo]<br/>Firma y envía las transacciones"]
    Reown["Relay de Reown<br/>[Sistema Externo]<br/>Transporta las solicitudes de firma"]
    Firebase["Firebase App Distribution<br/>[Sistema Externo]<br/>Canal de instalación para testers"]
    Polygon["Polygon Amoy<br/>[Sistema Externo]<br/>Red blockchain testnet"]
    FXApi["Proveedor de tasas de cambio<br/>[Sistema Externo]<br/>Cotizaciones FX"]

    Prestatario -->|"Solicita, paga préstamos"| LatiFi
    Prestamista -->|"Explora feed, fondea préstamos"| LatiFi
    Prestatario -->|"Aprueba firmas"| UserWallet
    Prestamista -->|"Aprueba firmas"| UserWallet
    Visitante -->|"Consulta propuesta de valor"| LatiFi
    LatiFi -->|"Pide cada firma"| Reown
    Reown -->|"Entrega la solicitud"| UserWallet
    UserWallet -->|"Envía la transacción firmada"| Polygon
    LatiFi -->|"Lee eventos on-chain"| Polygon
    LatiFi -->|"Consulta cotizaciones"| FXApi
    Firebase -.->|"Entrega la app"| LatiFi

    style LatiFi fill:#1168bd,color:#fff
    style UserWallet fill:#999,color:#fff
    style Reown fill:#999,color:#fff
    style Firebase fill:#999,color:#fff
    style Polygon fill:#999,color:#fff
    style FXApi fill:#999,color:#fff
```

#### 4.3.2. Software Architecture Container Level Diagrams

**Container Level Diagram (C4, Nivel 2)**

Al abrir la caja negra "LatiFi Platform" se distinguen seis contenedores, cada uno con su repositorio. **LatiFi Wallet (mobile)**, en el repositorio latifi-android, es una app nativa Android escrita en Kotlin con Jetpack Compose y Reown AppKit. Es el punto de entrada de Prestatario y Prestamista. Se comunica con la **LatiFi API** por REST sobre HTTPS para perfil, reputación, feed y conversión de moneda, y lee Polygon Amoy por JSON-RPC, solo para consultas. Cada firma sale por otro camino: la app la pide a la billetera del usuario a través del relay de Reown, y la billetera firma y envía la transacción al contrato.

Los **Smart Contracts**, en el repositorio latifi-contracts, están escritos en Solidity 0.8.35 y desplegados en Polygon Amoy. LoanBook ejecuta el ciclo del préstamo y MockStablecoin es la moneda de prueba. Son la fuente de verdad del préstamo y emiten eventos. La **LatiFi API**, en el repositorio latifi-api, usa Spring Boot 3.5 sobre Java 21 y expone los endpoints de perfil, reputación e historial y de conversión de moneda, para lo cual consulta a su vez al proveedor externo de tasas. El **Event Indexer** corre dentro del mismo proceso que la API. Lee los eventos con web3j mediante consultas periódicas de eth_getLogs a través de una llave RPC dedicada, y los escribe directamente en la **LatiFi DB** (PostgreSQL) por JDBC. Es idempotente por hash de transacción e índice del evento, así que releer un bloque no duplica filas. La **Landing Page**, en el repositorio latifi-landing, es un contenedor estático independiente que solo enlaza a la descarga de la app.

```mermaid
graph TD
    subgraph Actores
        Prestatario["Prestatario"]
        Prestamista["Prestamista"]
        Visitante["Visitante Web"]
    end

    subgraph "LatiFi Platform"
        Mobile["LatiFi Wallet (Mobile)<br/>[Container: Kotlin, Jetpack Compose,<br/>Reown AppKit, Android nativo]<br/>Repositorio latifi-android"]
        SC["Smart Contracts<br/>[Container: Solidity 0.8.35]<br/>LoanBook y MockStablecoin<br/>Repositorio latifi-contracts"]
        API["LatiFi API<br/>[Container: Spring Boot 3.5, Java 21]<br/>Profile, Reputation, Exchange Rate<br/>Repositorio latifi-api"]
        Indexer["Event Indexer<br/>[Container: web3j, embebido en<br/>el proceso de LatiFi API]<br/>Traduce eventos on-chain"]
        DB[("LatiFi DB<br/>[Container: PostgreSQL]<br/>Perfiles, reputación,<br/>eventos indexados, caché FX")]
        Landing["Landing Page<br/>[Container: HTML5, CSS3, JavaScript]<br/>Repositorio latifi-landing"]
    end

    UserWallet["Billetera del usuario<br/>[Sistema Externo]"]
    Reown["Relay de Reown<br/>[Sistema Externo]"]
    Polygon["Polygon Amoy<br/>[Sistema Externo]"]
    FXApi["Proveedor de tasas de cambio<br/>[Sistema Externo]"]

    Prestatario --> Mobile
    Prestamista --> Mobile
    Visitante --> Landing

    Mobile -->|"REST/HTTPS"| API
    Mobile -->|"JSON-RPC, solo lecturas"| Polygon
    Mobile -->|"Pide cada firma"| Reown
    Reown -->|"Entrega la solicitud"| UserWallet
    UserWallet -->|"Firma y envía la transacción"| SC
    SC -->|"emite eventos en"| Polygon
    Indexer -->|"eth_getLogs con llave RPC dedicada"| Polygon
    Indexer -->|"escribe eventos por JDBC"| DB
    API -->|"JDBC, lee y escribe"| DB
    API -->|"consulta cotizaciones"| FXApi

    style Mobile fill:#1168bd,color:#fff
    style SC fill:#1168bd,color:#fff
    style Indexer fill:#1168bd,color:#fff
    style API fill:#1168bd,color:#fff
    style DB fill:#1168bd,color:#fff
    style Landing fill:#1168bd,color:#fff
    style UserWallet fill:#999,color:#fff
    style Reown fill:#999,color:#fff
    style Polygon fill:#999,color:#fff
    style FXApi fill:#999,color:#fff
```

#### 4.3.3. Software Architecture Deployment Diagrams

**Deployment Diagram (C4)**

El despliegue distribuye el sistema en los nodos que usa el equipo. La app se instala en el teléfono Android desde Firebase App Distribution, y allí el Android Keystore sella la sesión (dirección y token), no una llave de billetera. La landing page se publica como sitio estático en GitHub Pages y el visitante la abre desde su navegador. Los Smart Contracts viven en Polygon Amoy. El código de la API pasa por GitHub Actions, que construye y prueba la imagen y la publica en GHCR. El servidor privado virtual (VPS) de Hetzner administrado con Dokploy construye el contenedor latifi-api desde el Dockerfile del repositorio con la integración Git, y Traefik publica el servicio por HTTPS con certificados de Let's Encrypt. En el mismo VPS corre una instancia compartida de PostgreSQL con una base de datos para LatiFi. El indexador lee Polygon Amoy a través de un proveedor RPC con llave dedicada, y la app pide sus firmas por el relay de Reown. Tres datos dependen del despliegue en vivo y siguen marcados como pendientes hasta que existan: la URL base de la API, la URL de Swagger UI y el enlace de invitación de Firebase.

```mermaid
graph TD
    subgraph "Teléfono Android"
        App["LatiFi Wallet<br/>[App Kotlin]<br/>Paquete com.latifi.wallet"]
        KS["Android Keystore<br/>[Sesión sellada: dirección y token]"]
    end

    UserWallet["Billetera del usuario<br/>[MetaMask u otra con WalletConnect]"]

    subgraph "Navegador"
        Browser["Landing Page<br/>[HTML5 / CSS3 / JS]"]
    end

    Firebase["Firebase App Distribution<br/>[Canal de testers]<br/>Enlace de invitación de Firebase App Distribution: PENDIENTE"]

    subgraph "GitHub Pages"
        Pages["Landing Page<br/>[Sitio estático]<br/>https://arquitectura-de-softwares-emergentes.github.io/latifi-landing/"]
    end

    subgraph "GitHub"
        Repo["Repositorio latifi-api"]
        CI["GitHub Actions<br/>[Construye y prueba la imagen]"]
        GHCR["GHCR<br/>[Registro de imágenes]<br/>ghcr.io/arquitectura-de-softwares-emergentes/latifi-api"]
    end

    subgraph "VPS Hetzner con Dokploy"
        Dokploy["Dokploy<br/>[Integración Git]<br/>Construye con el Dockerfile"]
        Traefik["Traefik<br/>[HTTPS con Let's Encrypt]"]
        APIsrv["latifi-api<br/>[Contenedor Spring Boot con el Event Indexer]<br/>URL base de la API: https://latifi-api.juan-tech.com<br/>URL de Swagger UI: https://latifi-api.juan-tech.com/swagger-ui/index.html"]
        PG[("PostgreSQL compartido<br/>[Base de datos de LatiFi]")]
    end

    subgraph "Polygon Amoy (testnet, cadena 80002)"
        Contracts["Smart Contracts<br/>[Solidity]<br/>LoanBook 0xccb8ad15a4954138c987a77924ceab468a843266<br/>MockStablecoin 0x66757f1cc66b278bfc0eefad7e3cac1d70fd4f8b"]
    end

    RPC["Proveedor RPC<br/>[Sistema Externo]<br/>Llave dedicada"]
    Reown["Relay de Reown<br/>[Sistema Externo]"]
    FX["Proveedor de tasas de cambio<br/>[Sistema Externo]<br/>https://open.er-api.com/v6/latest/USD"]

    Firebase -->|"Entrega el APK"| App
    App --> KS
    App -->|"HTTPS"| Traefik
    Traefik --> APIsrv
    App -->|"JSON-RPC, solo lecturas"| Contracts
    App -->|"Pide cada firma"| Reown
    Reown -->|"Entrega la solicitud"| UserWallet
    UserWallet -->|"Firma y envía la transacción"| Contracts
    Browser -->|"HTTPS"| Pages
    Pages -.->|"Enlaza a la descarga"| Firebase
    Repo --> CI
    CI -->|"Publica la imagen probada"| GHCR
    Dokploy -->|"Clona el repositorio"| Repo
    Dokploy -->|"Despliega"| APIsrv
    APIsrv --> PG
    APIsrv -->|"eth_getLogs"| RPC
    RPC -->|"Consulta la cadena"| Contracts
    APIsrv -->|"HTTPS"| FX

    style App fill:#1168bd,color:#fff
    style KS fill:#1168bd,color:#fff
    style Browser fill:#1168bd,color:#fff
    style Pages fill:#1168bd,color:#fff
    style Repo fill:#1168bd,color:#fff
    style CI fill:#1168bd,color:#fff
    style GHCR fill:#1168bd,color:#fff
    style Dokploy fill:#1168bd,color:#fff
    style Traefik fill:#1168bd,color:#fff
    style APIsrv fill:#1168bd,color:#fff
    style PG fill:#1168bd,color:#fff
    style Contracts fill:#1168bd,color:#fff
    style UserWallet fill:#999,color:#fff
    style Firebase fill:#999,color:#fff
    style RPC fill:#999,color:#fff
    style Reown fill:#999,color:#fff
    style FX fill:#999,color:#fff
```

**Tabla de despliegue**

| Componente | Plataforma | Origen | URL o dirección | Cómo se despliega |
|---|---|---|---|---|
| LatiFi Wallet (app Android) | Teléfono Android | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-android | Paquete com.latifi.wallet | Build de release firmado, subido a Firebase App Distribution e instalado desde el enlace de invitación |
| Firebase App Distribution | Servicio externo | Build de release de latifi-android | Enlace de invitación de Firebase App Distribution: PENDIENTE | El equipo sube el build y envía la invitación a los testers |
| Landing Page | GitHub Pages | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-landing | https://arquitectura-de-softwares-emergentes.github.io/latifi-landing/ | Un workflow de GitHub Actions publica el sitio estático |
| Navegador del visitante | Equipo del visitante | Sin código propio | https://arquitectura-de-softwares-emergentes.github.io/latifi-landing/ | Abre la landing por HTTPS |
| Billetera del usuario | Dispositivo del usuario | Billetera de terceros | Sin URL de LatiFi | La instala el usuario; firma y envía cada transacción |
| CI e imágenes | GitHub Actions y GHCR | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-api | ghcr.io/arquitectura-de-softwares-emergentes/latifi-api | El workflow ci construye y prueba la imagen y publish-image la publica en main y en las etiquetas v* |
| Dokploy y Traefik | VPS Hetzner | Instancia propia del equipo | Sin URL pública de administración | Dokploy construye desde el repositorio con la integración Git; Traefik sirve HTTPS con Let's Encrypt |
| LatiFi API con Event Indexer | VPS Hetzner con Dokploy | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-api | URL base de la API: https://latifi-api.juan-tech.com y URL de Swagger UI: https://latifi-api.juan-tech.com/swagger-ui/index.html | Contenedor construido desde el Dockerfile del repositorio; los secretos van en la configuración de Dokploy |
| PostgreSQL | VPS Hetzner con Dokploy | Instancia compartida de Dokploy | Sin URL pública | Base de datos propia de LatiFi con un usuario de mínimos privilegios |
| Smart Contracts | Polygon Amoy, cadena 80002 | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-contracts | LoanBook 0xccb8ad15a4954138c987a77924ceab468a843266, MockStablecoin 0x66757f1cc66b278bfc0eefad7e3cac1d70fd4f8b, explorador https://amoy.polygonscan.com/address/0xccb8ad15a4954138c987a77924ceab468a843266 | Despliegue desde el repositorio, con las direcciones registradas en deployments/amoy.json |
| Proveedor RPC | Servicio externo | Cuenta del equipo | No se publica, la URL lleva una llave | La llave dedicada se guarda como secreto en Dokploy |
| Relay de Reown | Servicio externo | Proyecto de Reown del equipo | Sin URL de LatiFi | El proyecto de Reown debe admitir el paquete com.latifi.wallet |
| Proveedor de tasas de cambio | Servicio externo | ExchangeRate-API | https://open.er-api.com/v6/latest/USD | La API lo consulta y guarda las cotizaciones en PostgreSQL |

## Capítulo V: Tactical-Level Software Design

El Capítulo IV delimitó los cinco bounded contexts de LatiFi y fijó cómo se relacionan entre sí. Este capítulo baja un nivel y define, para cada contexto, las clases que lo implementan, la capa a la que pertenece cada una, los componentes de cada container y las estructuras donde persiste su información. El diseño sigue los patrones tácticos de Domain-Driven Design: Entities, Value Objects, Aggregates, Domain Services, Repositories, Command Handlers y Event Handlers.

Cada contexto se organiza en cuatro capas, con una dependencia que siempre apunta hacia el dominio:

| Capa | Responsabilidad | Ejemplos en LatiFi |
|---|---|---|
| Domain Layer | Reglas de negocio, invariantes y lenguaje ubicuo del contexto. No conoce frameworks ni bases de datos. | `Loan`, `Profile`, `ReputationProfile`, `ExchangeRate`, repositorios como interfaces |
| Application Layer | Orquesta los casos de uso y los flujos de proceso. Recibe comandos y consultas, y reacciona a eventos. | `LoanAgreement` (comandos on-chain), `ProfileService`, `RecordLoanOutcomeHandler` |
| Interface Layer | Puerta de entrada al contexto: controladores REST, funciones externas del contrato, pantallas móviles. | `ProfileController`, ABI de `LoanAgreement`, `LoanFeedController` |
| Infrastructure Layer | Acceso a servicios externos: base de datos, red blockchain, proveedor de tasas, Android Keystore. | `JpaProfileRepository`, `Web3jChainEventSource`, `HttpExchangeRateProvider` |

Los contextos se reparten entre los containers que definió el Capítulo IV y usan las tecnologías ya decididas:

| Bounded context | Containers que lo implementan | Tecnología | Persistencia | Historias de usuario |
|---|---|---|---|---|
| Lending | Smart Contracts | Solidity 0.8.35, OpenZeppelin 5.x, Foundry | Almacenamiento del contrato en Polygon Amoy | US-LEND-01, US-LEND-03, US-LEND-04, US-LEND-05 |
| Identity/Wallet | LatiFi Wallet, LatiFi API | Kotlin y web3j para Android; Spring Boot 3.5 con Java 21 | Android Keystore; PostgreSQL | US-AUTH-01 a US-AUTH-04, US-IDEN-01, US-IDEN-02 |
| Reputation | LatiFi API, Event Indexer | Spring Boot 3.5, web3j, Spring Data JPA | PostgreSQL | US-REP-01 a US-REP-04, US-API-01, US-LEND-02, US-LEND-05 |
| Exchange Rate | LatiFi API | Spring Boot 3.5, cliente HTTP, caché en base de datos | PostgreSQL | US-LEND-06, US-API-02 |
| Marketing/Landing | Landing Page | HTML5, CSS3, JavaScript y Material Design | Archivos JSON versionados | US-LAND-01, US-LAND-02 |

Los diagramas de componentes usan la notación del C4 Model (Container Boundary, Component, Component DB y System Ext). Los diagramas de clases usan UML con visibilidad (`+` público, `-` privado, `#` protegido), relaciones con nombre y multiplicidad. Los diagramas de base de datos muestran tablas, columnas, claves primarias (PK), claves foráneas (FK) y restricciones únicas (UK).

### 5.1. Bounded Context: Lending

El Lending Context es el único dueño del ciclo de vida del préstamo y vive completo en la cadena. Su diseño parte de cuatro decisiones, todas coherentes con el Capítulo IV:

- **Un único contrato registro.** `LoanAgreement` guarda todos los préstamos en un mapa indexado por identificador. Se descartó una fábrica que despliegue un contrato por préstamo, porque obligaría al Event Indexer a descubrir direcciones nuevas de forma dinámica y encarece el gas de cada solicitud.
- **La solicitud nace on-chain.** `LoanRequested` se emite desde el contrato, de modo que el feed de solicitudes se deriva solo de eventos y ningún estado del préstamo existe fuera de la cadena.
- **Cuotas iguales con un vencimiento cada una.** El plazo total se divide en entre una y seis cuotas del mismo monto, espaciadas de forma uniforme. La última cuota absorbe el residuo del redondeo.
- **Ningún dato de precio entra al contrato.** El contrato opera solo con la unidad de la stablecoin. La conversión a moneda local es presentacional y pertenece al Exchange Rate Context.

#### 5.1.1. Domain Layer

El dominio del contrato se compone de tipos de datos, una librería de cálculo y las interfaces que expresan el contrato público. No depende de ninguna librería externa salvo la interfaz estándar `IERC20`.

| Clase | Tipo | Propósito | Atributos y métodos |
|---|---|---|---|
| `Loan` | Aggregate Root (struct) | Representa un préstamo desde la solicitud hasta su liquidación. Es la única copia del estado del préstamo. | `id`, `borrower`, `lender`, `principal`, `interestRateBps`, `termDays`, `installments`, `totalDue`, `amountRepaid`, `installmentsPaid`, `requestedAt`, `fundedAt`, `status` |
| `LoanStatus` | Enumeración | Estados válidos de un préstamo, que alimentan la consulta de estado de US-LEND-05. | `Open`, `Active`, `Repaid`, `Defaulted` |
| `BorrowerStats` | Value Object (struct) | Contadores de resultados de un prestatario que el contrato incrementa y nadie más puede modificar. | `onTimePayments`, `latePayments`, `defaults` |
| `InterestMath` | Domain Service (librería) | Calcula el monto total a pagar, el monto y la fecha de cada cuota. Es pura: no lee ni escribe estado. | `totalDue(principal, rateBps)`, `installmentAmount(totalDue, count, index)`, `dueDate(fundedAt, termDays, count, index)` |
| `ILoanAgreement` | Interfaz | Declara las operaciones, los eventos y los errores del contexto. Es el contrato público que consumen la app y el indexador. | `requestLoan`, `fundLoan`, `repay`, `markDefaulted`, `getLoan`, `getBorrowerStats`, `nextDueDate` |

Las reglas de negocio que el dominio hace cumplir son estas:

1. El monto y el plazo deben ser mayores que cero, el número de cuotas debe ser un entero entre 1 y 6 ([ADR-0004](docs/adr/0004-repayment-installment-model.md)) y la tasa debe estar dentro del rango configurado.
2. Un préstamo solo se fondea una vez, y nunca lo fondea su propio prestatario.
3. Una vez fondeado, ni el monto, ni la tasa, ni el plazo, ni el vencimiento cambian.
4. El prestatario no puede pagar más de lo que adeuda.
5. Después del vencimiento final, cualquier cuenta puede marcar el préstamo como incumplido.

Los eventos de dominio y sus parámetros son:

| Evento | Parámetros | Cuándo se emite |
|---|---|---|
| `LoanRequested` | `loanId`, `borrower`, `amount`, `interestRateBps`, `termDays`, `installments` | El prestatario publica una solicitud válida. |
| `LoanFunded` | `loanId`, `lender`, `borrower`, `amount`, `fundedAt`, `dueDate` | Un prestamista fondea y la stablecoin pasa al prestatario. |
| `LoanRepaid` | `loanId`, `amountPaid`, `onTime` | En cada pago del prestatario, aunque el préstamo no se liquide. |
| `LoanDefaulted` | `loanId`, `borrower`, `outstandingAmount` | Se marca como incumplido un préstamo vencido. |

Los nombres y el orden de los parámetros coinciden con `abi/loan-events.v0.json` del repositorio `latifi-contracts`. Están indexados `loanId` en los cuatro eventos, `borrower` en `LoanRequested`, `LoanFunded` y `LoanDefaulted`, y `lender` en `LoanFunded`. En los eventos, `amount` es el `principal` del préstamo, `dueDate` es el vencimiento de la última cuota y `termDays` es un `uint32`. Ningún evento lleva precio, tasa de cambio ni dato de oráculo.

#### 5.1.2. Interface Layer

La capa de interfaz del contrato es su ABI. Las funciones externas reciben las intenciones de los usuarios y delegan la regla de negocio en las capas inferiores.

| Elemento | Tipo | Propósito | Firma |
|---|---|---|---|
| `requestLoan` | Función de escritura | Publica una solicitud de préstamo (US-LEND-01). | `requestLoan(uint256 principal, uint16 interestRateBps, uint32 termDays, uint8 installments) returns (uint256 loanId)` |
| `fundLoan` | Función de escritura | Fondea una solicitud abierta (US-LEND-03). | `fundLoan(uint256 loanId)` |
| `repay` | Función de escritura | Registra un pago del prestatario (US-LEND-04). | `repay(uint256 loanId, uint256 amount)` |
| `markDefaulted` | Función de escritura | Marca un préstamo vencido como incumplido. | `markDefaulted(uint256 loanId)` |
| `getLoan` | Función de lectura | Devuelve el préstamo completo (US-LEND-05). | `getLoan(uint256 loanId) returns (Loan)` |
| `getBorrowerStats` | Función de lectura | Devuelve los contadores de un prestatario. | `getBorrowerStats(address borrower) returns (BorrowerStats)` |
| `nextDueDate` | Función de lectura | Devuelve la fecha de la próxima cuota pendiente. | `nextDueDate(uint256 loanId) returns (uint64)` |

Los errores personalizados reemplazan a los mensajes de texto para reducir el gas y facilitar las pruebas: `InvalidAmount`, `InvalidTerm`, `InvalidInstallments`, `RateOutOfRange`, `LoanNotOpen`, `SelfFunding`, `LoanNotActive`, `Overpayment` y `NotYetDefaultable`.

#### 5.1.3. Application Layer

La capa de aplicación del contrato la forman los manejadores de comandos, que son las funciones de `LoanAgreement`. Cada uno valida la entrada, aplica la regla del dominio, actualiza el estado y emite el evento. En un contrato no existen manejadores de eventos entrantes: el contexto solo publica eventos, nunca los consume.

| Manejador | Comando que atiende | Flujo |
|---|---|---|
| `requestLoan` | Publicar solicitud | Valida monto, plazo, cuotas y tasa; calcula `totalDue`; guarda el préstamo en estado `Open`; emite `LoanRequested`. |
| `fundLoan` | Fondear solicitud | Verifica que esté `Open` y que el prestamista no sea el prestatario; cambia a `Active`; fija `fundedAt`; transfiere la stablecoin del prestamista al prestatario; emite `LoanFunded`. |
| `repay` | Pagar | Verifica que esté `Active` y que el pago no exceda lo adeudado; determina si el pago es puntual; transfiere la stablecoin del prestatario al prestamista; actualiza contadores; emite `LoanRepaid`; si el saldo llega a cero, cambia a `Repaid`. |
| `markDefaulted` | Marcar incumplimiento | Verifica que esté `Active` y que haya pasado el vencimiento final; cambia a `Defaulted`; incrementa `defaults`; emite `LoanDefaulted`. |

Todas las funciones que mueven fondos llevan el modificador `nonReentrant` y siguen el patrón checks-effects-interactions: el estado se actualiza antes de transferir la stablecoin.

#### 5.1.4. Infrastructure Layer

La infraestructura del contrato la forman las dependencias externas que sostienen la ejecución. Se reutilizan componentes auditados de OpenZeppelin en lugar de escribirlos de nuevo.

| Componente | Origen | Propósito |
|---|---|---|
| `SafeERC20` | OpenZeppelin 5.x | Transfiere la stablecoin con verificación del resultado de cada llamada. |
| `ReentrancyGuard` | OpenZeppelin 5.x | Provee el modificador `nonReentrant`. |
| `Pausable` y `AccessControl` | OpenZeppelin 5.x | Permiten que un rol administrador detenga las operaciones ante un incidente. |
| `MockStablecoin` | Propio | ERC-20 de prueba con 6 decimales y emisión pública acotada, que evita depender de faucets externos durante las demostraciones. |
| `IERC20` | Estándar ERC-20 | Puerto por el que `LoanAgreement` conoce la stablecoin sin acoplarse a una implementación. |

#### 5.1.5. Bounded Context Software Architecture Component Level Diagrams

El container Smart Contracts se descompone en cuatro componentes propios y tres de OpenZeppelin. La app firma las transacciones y el Event Indexer lee los eventos desde la red.

```mermaid
C4Component
    title Diagrama de componentes: Smart Contracts (Lending Context)

    Boundary(up, "Actores y clientes", "") {
        Container(wallet, "LatiFi Wallet", "Kotlin, Android", "Firma y envía transacciones")
    }

    Container_Boundary(sc, "Smart Contracts [Solidity 0.8.35]") {
        Component(abi, "ILoanAgreement", "Interfaz Solidity", "Funciones, eventos y errores")
        Component(agreement, "LoanAgreement", "Contrato Solidity", "Manejadores de comandos y registro de préstamos")
        Component(math, "InterestMath", "Librería Solidity", "Interés, cuotas y vencimientos")
        Component(guard, "ReentrancyGuard y Pausable", "OpenZeppelin 5.x", "Protección y pausa de emergencia")
        Component(safe, "SafeERC20", "OpenZeppelin 5.x", "Transferencias verificadas")
        Component(token, "MockStablecoin", "ERC-20, 6 decimales", "Stablecoin de prueba")
    }

    Boundary(down, "Entorno del container", "") {
        System_Ext(amoy, "Polygon Amoy", "Red blockchain de pruebas")
        Container(indexer, "Event Indexer", "Java, embebido en LatiFi API", "Lee y traduce los eventos")
    }

    Rel(wallet, agreement, "requestLoan, fundLoan, repay", "JSON-RPC")
    Rel(agreement, abi, "Implementa")
    Rel(agreement, math, "Calcula con")
    Rel(agreement, guard, "Hereda")
    Rel(agreement, safe, "Transfiere con")
    Rel(safe, token, "Mueve fondos de")
    Rel(agreement, amoy, "Se ejecuta en")
    Rel(indexer, amoy, "Lee eventos", "eth_getLogs")

    UpdateLayoutConfig($c4ShapeInRow="3", $c4BoundaryInRow="1")
```

#### 5.1.6. Bounded Context Software Architecture Code Level Diagrams

##### 5.1.6.1. Bounded Context Domain Layer Class Diagrams

El diagrama muestra las clases del Domain Layer y la interfaz que las expone. `LoanAgreement` conserva todos los préstamos y todos los contadores; `InterestMath` es una librería sin estado.

```mermaid
classDiagram
    class ILoanAgreement {
        <<interface>>
        +requestLoan(principal, interestRateBps, termDays, installments) uint256
        +fundLoan(loanId) void
        +repay(loanId, amount) void
        +markDefaulted(loanId) void
        +getLoan(loanId) Loan
        +getBorrowerStats(borrower) BorrowerStats
        +nextDueDate(loanId) uint64
    }
    class LoanAgreement {
        <<contract>>
        -IERC20 _token
        -uint16 _maxRateBps
        -uint32 _minTermDays
        -uint32 _maxTermDays
        -uint256 _nextLoanId
        -Map~uint256,Loan~ _loans
        -Map~address,BorrowerStats~ _stats
        +requestLoan(principal, interestRateBps, termDays, installments) uint256
        +fundLoan(loanId) void
        +repay(loanId, amount) void
        +markDefaulted(loanId) void
        +pause() void
        +unpause() void
    }
    class Loan {
        <<struct>>
        +uint256 id
        +address borrower
        +address lender
        +uint256 principal
        +uint16 interestRateBps
        +uint32 termDays
        +uint8 installments
        +uint256 totalDue
        +uint256 amountRepaid
        +uint8 installmentsPaid
        +uint64 requestedAt
        +uint64 fundedAt
        +LoanStatus status
    }
    class LoanStatus {
        <<enumeration>>
        Open
        Active
        Repaid
        Defaulted
    }
    class BorrowerStats {
        <<struct>>
        +uint32 onTimePayments
        +uint32 latePayments
        +uint32 defaults
    }
    class InterestMath {
        <<library>>
        +totalDue(principal, rateBps) uint256
        +installmentAmount(totalDue, count, index) uint256
        +dueDate(fundedAt, termDays, count, index) uint64
    }
    class IERC20 {
        <<interface>>
        +transferFrom(from, to, amount) bool
        +balanceOf(account) uint256
    }

    LoanAgreement ..|> ILoanAgreement : implementa
    LoanAgreement "1" *-- "0..*" Loan : registra
    LoanAgreement "1" *-- "0..*" BorrowerStats : acumula por prestatario
    Loan "1" --> "1" LoanStatus : tiene estado
    LoanAgreement ..> InterestMath : calcula con
    LoanAgreement --> "1" IERC20 : mueve fondos con
```

##### 5.1.6.2. Bounded Context Database Diagram

El Lending Context no usa tablas. Su persistencia es el almacenamiento del contrato y el registro de eventos de la cadena. El diagrama presenta ambos con la misma notación relacional para facilitar la lectura: el préstamo se identifica por su `id`, los contadores se identifican por la dirección del prestatario y cada evento referencia al préstamo que lo originó.

```mermaid
erDiagram
    BORROWER_STATS {
        address borrower PK "mapping _stats"
        uint32 onTimePayments
        uint32 latePayments
        uint32 defaults
    }
    LOAN {
        uint256 id PK "mapping _loans"
        address borrower FK
        address lender
        uint256 principal
        uint16 interestRateBps
        uint32 termDays
        uint8 installments
        uint256 totalDue
        uint256 amountRepaid
        uint8 installmentsPaid
        uint64 requestedAt
        uint64 fundedAt
        uint8 status "Open, Active, Repaid, Defaulted"
    }
    LOAN_EVENT {
        bytes32 txHash PK
        uint32 logIndex PK
        uint256 loanId FK
        string eventName "LoanRequested, LoanFunded, LoanRepaid, LoanDefaulted"
        uint64 blockNumber
    }

    BORROWER_STATS ||--o{ LOAN : "acumula resultados de"
    LOAN ||--o{ LOAN_EVENT : "emite"
```

Restricciones del esquema:

- `LOAN.id` es un contador ascendente (`_nextLoanId`) que nunca se reutiliza.
- `LOAN.borrower` y `LOAN.lender` son distintos cuando el estado es `Active` o posterior.
- `LOAN.amountRepaid` nunca supera `LOAN.totalDue`.
- `LOAN.principal`, `LOAN.interestRateBps`, `LOAN.termDays`, `LOAN.installments` y `LOAN.totalDue` son inmutables desde que el estado pasa a `Active`.
- `LOAN_EVENT` no se escribe desde el contrato: la red lo produce como registro inmutable de cada transacción, y el par `txHash` y `logIndex` lo identifica de forma única.

### 5.2. Bounded Context: Identity/Wallet

El Identity/Wallet Context responde a la pregunta de quién es el usuario. Se reparte en dos containers: LatiFi Wallet, que crea y custodia en el dispositivo la clave del usuario y firma, y LatiFi API, que verifica las firmas y guarda el perfil ligero. La dirección on-chain es la identidad; no existen usuario ni contraseña.

Las decisiones de diseño del contexto son:

- **Billetera propia y no custodial.** La app genera el par de claves en el primer arranque y lo protege con Android Keystore. Ninguna clave ni frase de recuperación sale del dispositivo (DR-08). La conexión con una billetera externa a través de Reown queda como vía opcional de importación, no como flujo principal.
- **Autenticación por desafío y firma.** La API entrega un nonce de un solo uso; la app lo firma con el esquema de mensaje personal de Ethereum (EIP-191); la API recupera la dirección del firmante y, solo si coincide con la declarada, emite un token de sesión.
- **Perfil ligero como barrera mínima contra Sybil.** El perfil guarda nombre y un dato de contacto. La API nunca devuelve el contacto a un usuario distinto de su dueño.

#### 5.2.1. Domain Layer

Dominio del container LatiFi Wallet (Android):

| Clase | Tipo | Propósito | Atributos y métodos |
|---|---|---|---|
| `Wallet` | Entity | Billetera del usuario en el dispositivo. | `address: WalletAddress`, `createdAt: Instant`, `recoveryConfirmed: Boolean`; `confirmRecovery()` |
| `WalletAddress` | Value Object | Dirección de 20 bytes en formato hexadecimal con suma de verificación. | `value: String`; `toChecksum(): String`; valida el prefijo `0x` y 40 caracteres hexadecimales |
| `RecoveryPhrase` | Value Object | Frase de 12 palabras que permite restaurar la billetera. Nunca se persiste en texto plano. | `words: List<String>`; `toSeed(): ByteArray` |
| `SignedMessage` | Value Object | Resultado de firmar un mensaje. | `message: String`, `signature: String`, `signer: WalletAddress` |
| `TransactionStatus` | Enumeración | Estados que ve el usuario durante una operación on-chain (US-AUTH-04). | `Pending`, `Confirming`, `Confirmed`, `Failed` |
| `WalletRepository` | Repositorio (interfaz) | Puerto de persistencia de la billetera. | `current(): Wallet?`, `save(wallet)`, `clear()` |
| `MessageSigner` | Domain Service (interfaz) | Puerto de firma de mensajes y transacciones con la clave del usuario. | `sign(message): SignedMessage`, `signTransaction(raw): ByteArray` |

Dominio del container LatiFi API:

| Clase | Tipo | Propósito | Atributos y métodos |
|---|---|---|---|
| `Profile` | Aggregate Root | Perfil ligero vinculado a una dirección. | `address: WalletAddress`, `displayName: String`, `contact: ContactInfo`, `createdAt`, `updatedAt`; `update(displayName, contact)`, `isComplete(): Boolean` |
| `ContactInfo` | Value Object | Dato de contacto validado. | `type: ContactType`, `value: String` |
| `ContactType` | Enumeración | Tipo de contacto aceptado. | `EMAIL`, `PHONE` |
| `AuthChallenge` | Entity | Desafío de un solo uso que el usuario debe firmar. | `id: UUID`, `address: WalletAddress`, `nonce: String`, `issuedAt`, `expiresAt`, `consumedAt`; `isExpired(now)`, `consume(now)` |
| `SignatureVerifier` | Domain Service (interfaz) | Puerto que recupera la dirección de quien firmó un mensaje. | `recoverSigner(message, signature): WalletAddress` |
| `ProfileRepository` | Repositorio (interfaz) | Puerto de persistencia de perfiles. | `findByAddress(address)`, `save(profile)` |
| `AuthChallengeRepository` | Repositorio (interfaz) | Puerto de persistencia de desafíos. | `findById(id)`, `save(challenge)` |
| `ProfileCreated` | Domain Event | Se emite al registrarse un perfil nuevo. | `address`, `occurredAt` |
| `ProfileUpdated` | Domain Event | Se emite al cambiar un perfil existente. | `address`, `occurredAt` |

Invariantes: un desafío solo se consume una vez y solo antes de su expiración; un perfil siempre pertenece a exactamente una dirección; el contacto solo es legible por su dueño.

#### 5.2.2. Interface Layer

Interfaz del container LatiFi API (REST, con prefijo `/api/v1`):

| Controlador | Operación | Propósito | Acceso |
|---|---|---|---|
| `AuthController` | `POST /auth/challenge` | Solicita un nonce para una dirección. | Público |
| `AuthController` | `POST /auth/verify` | Entrega `challengeId`, dirección y firma. Devuelve el token de sesión solo si el firmante coincide con la dirección declarada y con la del desafío, y el desafío está sin usar y vigente. | Público |
| `ProfileController` | `GET /profiles/{address}` | Lee un perfil. El contacto solo se incluye cuando la dirección consultada es la del usuario autenticado. | Autenticado |
| `ProfileController` | `PUT /profiles/{address}` | Crea o actualiza el perfil. Solo el dueño de la dirección puede escribir. | Autenticado |

Los objetos de transferencia son `ChallengeRequest`, `ChallengeResponse`, `VerifyRequest` (con `challengeId`, `address` y `signature`), `TokenResponse`, `ProfileResponse` y `ProfileUpdateRequest`. Los errores se devuelven con código 401 para firmas inválidas, repetidas o vencidas, y con código 403 cuando el usuario intenta escribir un perfil ajeno.

Toda operación de la API, salvo `/auth/challenge` y `/auth/verify`, exige el token de sesión. `PUT /profiles/{address}` responde 201 cuando crea el perfil, 200 cuando lo actualiza y 403 cuando quien llama no es el dueño de la dirección. El contrato completo es el borrador OpenAPI del repositorio `latifi-api`: https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-api/blob/develop/openapi/latifi-api.v0.yaml.

Interfaz del container LatiFi Wallet (pantallas y modelos de vista):

| Clase | Propósito | Historia |
|---|---|---|
| `OnboardingScreen` y `OnboardingViewModel` | Explica en lenguaje simple cómo se solicita, fondea y paga un préstamo antes de crear la billetera. | US-AUTH-03 |
| `WalletSetupScreen` y `WalletSetupViewModel` | Crea la billetera, muestra la frase de recuperación y exige su confirmación. | US-AUTH-01, US-AUTH-02 |
| `ProfileScreen` y `ProfileViewModel` | Captura y edita nombre y contacto. Bloquea publicar o fondear mientras el perfil esté incompleto. | US-IDEN-01 |
| `TransactionStatusSheet` y `TransactionStatusViewModel` | Muestra el estado de una transacción y ofrece reintentar o reconectar si la firma nunca llega. | US-AUTH-04 |

#### 5.2.3. Application Layer

Aplicación del container LatiFi API:

| Clase | Operaciones | Flujo |
|---|---|---|
| `AuthService` | `issueChallenge(address)` | Genera un nonce aleatorio, fija su vencimiento en cinco minutos y lo persiste. |
| `AuthService` | `verify(challengeId, address, signature)` | Recupera el firmante y comprueba que coincida con la dirección declarada y con la del desafío, y que el desafío esté sin usar y vigente. Luego consume el desafío y emite el token. |
| `ProfileService` | `getProfile(address, requester)` | Devuelve el perfil y omite el contacto si el solicitante no es el dueño. |
| `ProfileService` | `upsertProfile(address, request, requester)` | Verifica la propiedad, valida el contacto, guarda y publica `ProfileCreated` o `ProfileUpdated`. |

Aplicación del container LatiFi Wallet (casos de uso):

| Caso de uso | Flujo |
|---|---|
| `CreateWalletUseCase` | Genera el par de claves, lo guarda a través de `WalletRepository` y devuelve la frase de recuperación para mostrarla una vez. |
| `RestoreWalletUseCase` | Reconstruye la billetera desde una frase de recuperación y la guarda. |
| `SignInUseCase` | Pide el desafío a la API, lo firma con `MessageSigner`, lo verifica y almacena el token de sesión. |
| `SaveProfileUseCase` | Envía nombre y contacto a la API y actualiza el estado local del perfil. |
| `TrackTransactionUseCase` | Consulta el recibo de la transacción hasta confirmarla y emite cada cambio de `TransactionStatus`. |

#### 5.2.4. Infrastructure Layer

Infraestructura del container LatiFi API:

| Clase | Implementa | Tecnología |
|---|---|---|
| `JpaProfileRepository` | `ProfileRepository` | Spring Data JPA sobre PostgreSQL |
| `JpaAuthChallengeRepository` | `AuthChallengeRepository` | Spring Data JPA sobre PostgreSQL |
| `Web3jSignatureVerifier` | `SignatureVerifier` | web3j, recuperación de firma ECDSA según EIP-191 |
| `JwtTokenProvider` | Emisión y lectura del token de sesión | Spring Security con JWT |
| `JwtAuthenticationFilter` | Autenticación de cada petición | Filtro de Spring Security |
| `SpringDomainEventPublisher` | Publicación de `ProfileCreated` y `ProfileUpdated` | Eventos de aplicación de Spring |

Infraestructura del container LatiFi Wallet:

| Clase | Implementa | Tecnología |
|---|---|---|
| `KeystoreWalletRepository` | `WalletRepository` | Android Keystore protege la clave que cifra el material de la billetera con AES-GCM |
| `Web3jMessageSigner` | `MessageSigner` | web3j para Android, firma EIP-191 y de transacciones |
| `LatiFiAuthApi` y `LatiFiProfileApi` | Clientes REST | Retrofit y OkHttp |
| `SessionStore` | Almacén del token de sesión | Preferencias cifradas |
| `ReceiptPoller` | Consulta de recibos | web3j sobre JSON-RPC |
| `ReownImportAdapter` | Importación opcional de una billetera externa | SDK de Reown |

#### 5.2.5. Bounded Context Software Architecture Component Level Diagrams

Container LatiFi API, módulo de identidad:

```mermaid
C4Component
    title Diagrama de componentes: LatiFi API, módulo Identity (Identity/Wallet Context)

    Boundary(up, "Actores y clientes", "") {
        Container(wallet, "LatiFi Wallet", "Kotlin, Android", "Cliente móvil")
    }

    Container_Boundary(api, "LatiFi API [Spring Boot 3.5, Java 21]") {
        Component(authc, "AuthController", "Spring MVC RestController", "POST /auth/challenge y /auth/verify")
        Component(profc, "ProfileController", "Spring MVC RestController", "GET y PUT /profiles/{address}")
        Component(filter, "JwtAuthenticationFilter", "Spring Security", "Autentica cada petición")
        Component(authsvc, "AuthService", "Spring Service", "Emite y verifica desafíos")
        Component(profsvc, "ProfileService", "Spring Service", "Casos de uso del perfil")
        Component(pub, "SpringDomainEventPublisher", "Spring Events", "Publica eventos de perfil")
        Component(verifier, "Web3jSignatureVerifier", "web3j", "Recupera el firmante EIP-191")
        Component(jwt, "JwtTokenProvider", "Spring Security JWT", "Emite y valida tokens")
        Component(repos, "Repositorios JPA", "Spring Data JPA", "Perfiles y desafíos")
    }

    Boundary(down, "Entorno del container", "") {
        ContainerDb(db, "LatiFi DB", "PostgreSQL", "Perfiles y desafíos")
        Container(rep, "Módulo Reputation", "Spring Boot", "Consume ProfileCreated")
    }

    Rel(wallet, authc, "Solicita desafío y verifica", "REST, HTTPS")
    Rel(wallet, profc, "Lee y guarda perfil", "REST, HTTPS")
    Rel(filter, jwt, "Valida token")
    Rel(authc, authsvc, "Usa")
    Rel(profc, profsvc, "Usa")
    Rel(authsvc, verifier, "Verifica firma")
    Rel(authsvc, jwt, "Emite token")
    Rel(authsvc, repos, "Lee y guarda desafíos")
    Rel(profsvc, repos, "Lee y guarda perfiles")
    Rel(profsvc, pub, "Publica eventos")
    Rel(repos, db, "SQL", "JDBC")
    Rel(pub, rep, "ProfileCreated")

    UpdateLayoutConfig($c4ShapeInRow="3", $c4BoundaryInRow="1")
```

Container LatiFi Wallet, módulo de identidad y billetera:

```mermaid
C4Component
    title Diagrama de componentes: LatiFi Wallet, módulo Identity/Wallet

    Boundary(up, "Actores y clientes", "") {
        Person(user, "Prestatario o prestamista", "Usuario de la app")
    }

    Container_Boundary(app, "LatiFi Wallet [Kotlin, Android]") {
        Component(ui, "Onboarding, WalletSetup y Profile", "Jetpack Compose y ViewModel", "Pantallas del contexto")
        Component(tx, "TransactionStatusViewModel", "ViewModel", "Estado de la transacción")
        Component(uc, "Casos de uso", "Kotlin", "CreateWallet, RestoreWallet, SignIn, SaveProfile, TrackTransaction")
        Component(walletrepo, "KeystoreWalletRepository", "Android Keystore, AES-GCM", "Guarda la billetera")
        Component(signer, "Web3jMessageSigner", "web3j, Android", "Firma mensajes y transacciones")
        Component(client, "LatiFiAuthApi y LatiFiProfileApi", "Retrofit, OkHttp", "Cliente REST")
        Component(poller, "ReceiptPoller", "web3j", "Consulta recibos")
    }

    Boundary(down, "Entorno del container", "") {
        Container(api, "LatiFi API", "Spring Boot", "Autenticación y perfil")
        System_Ext(amoy, "Polygon Amoy", "Red blockchain de pruebas")
    }

    Rel(user, ui, "Usa")
    Rel(ui, uc, "Invoca")
    Rel(tx, uc, "Invoca")
    Rel(uc, walletrepo, "Guarda y lee la billetera")
    Rel(uc, signer, "Firma")
    Rel(uc, client, "Llama a la API")
    Rel(uc, poller, "Sigue la transacción")
    Rel(client, api, "REST", "HTTPS")
    Rel(poller, amoy, "Lee recibos", "JSON-RPC")

    UpdateLayoutConfig($c4ShapeInRow="3", $c4BoundaryInRow="1")
```

#### 5.2.6. Bounded Context Software Architecture Code Level Diagrams

##### 5.2.6.1. Bounded Context Domain Layer Class Diagrams

Dominio del container LatiFi API:

```mermaid
classDiagram
    class Profile {
        <<Aggregate Root>>
        -WalletAddress address
        -String displayName
        -ContactInfo contact
        -Instant createdAt
        -Instant updatedAt
        +update(displayName, contact) void
        +isComplete() boolean
    }
    class ContactInfo {
        <<Value Object>>
        -ContactType type
        -String value
        +validate() boolean
    }
    class ContactType {
        <<enumeration>>
        EMAIL
        PHONE
    }
    class WalletAddress {
        <<Value Object>>
        -String value
        +toChecksum() String
    }
    class AuthChallenge {
        <<Entity>>
        -UUID id
        -WalletAddress address
        -String nonce
        -Instant issuedAt
        -Instant expiresAt
        -Instant consumedAt
        +isExpired(now) boolean
        +consume(now) void
    }
    class SignatureVerifier {
        <<interface>>
        +recoverSigner(message, signature) WalletAddress
    }
    class ProfileRepository {
        <<interface>>
        +findByAddress(address) Profile
        +save(profile) void
    }
    class AuthChallengeRepository {
        <<interface>>
        +findById(id) AuthChallenge
        +save(challenge) void
    }
    class ProfileCreated {
        <<Domain Event>>
        -WalletAddress address
        -Instant occurredAt
    }

    Profile "1" *-- "1" ContactInfo : contiene
    Profile "1" --> "1" WalletAddress : se identifica por
    ContactInfo "1" --> "1" ContactType : es de tipo
    AuthChallenge "0..*" --> "1" WalletAddress : se emite para
    Profile ..> ProfileCreated : emite
    ProfileRepository ..> Profile : persiste
    AuthChallengeRepository ..> AuthChallenge : persiste
    SignatureVerifier ..> WalletAddress : devuelve
```

Dominio del container LatiFi Wallet:

```mermaid
classDiagram
    class Wallet {
        <<Entity>>
        -WalletAddress address
        -Instant createdAt
        -boolean recoveryConfirmed
        +confirmRecovery() void
    }
    class WalletAddress {
        <<Value Object>>
        -String value
        +toChecksum() String
    }
    class RecoveryPhrase {
        <<Value Object>>
        -List~String~ words
        +toSeed() ByteArray
    }
    class SignedMessage {
        <<Value Object>>
        -String message
        -String signature
        -WalletAddress signer
    }
    class TransactionStatus {
        <<enumeration>>
        Pending
        Confirming
        Confirmed
        Failed
    }
    class WalletRepository {
        <<interface>>
        +current() Wallet
        +save(wallet) void
        +clear() void
    }
    class MessageSigner {
        <<interface>>
        +sign(message) SignedMessage
        +signTransaction(raw) ByteArray
    }

    Wallet "1" --> "1" WalletAddress : se identifica por
    Wallet "1" ..> "1" RecoveryPhrase : se restaura con
    MessageSigner ..> SignedMessage : produce
    SignedMessage "1" --> "1" WalletAddress : firmado por
    WalletRepository ..> Wallet : persiste
```

##### 5.2.6.2. Bounded Context Database Diagram

Las tablas del contexto viven en PostgreSQL y las crea una migración versionada. El desafío no declara clave foránea hacia `profile`, porque se emite antes de que el perfil exista. En el dispositivo, la billetera no se modela como tabla: el material cifrado se guarda en almacenamiento privado de la app, protegido por una clave que nunca abandona Android Keystore.

```mermaid
erDiagram
    PROFILE {
        char42 address PK "dirección 0x en formato checksum"
        varchar display_name "no nulo, hasta 80 caracteres"
        varchar contact_type "EMAIL o PHONE"
        varchar contact_value "no nulo"
        timestamptz created_at
        timestamptz updated_at
    }
    AUTH_CHALLENGE {
        uuid id PK
        char42 address "dirección que solicita el desafío"
        varchar nonce UK "aleatorio, de un solo uso"
        timestamptz issued_at
        timestamptz expires_at
        timestamptz consumed_at "nulo mientras no se use"
    }

    PROFILE ||--o{ AUTH_CHALLENGE : "se vincula por dirección, sin FK"
```

Restricciones del esquema:

- `PROFILE.address` es la clave primaria natural y se guarda siempre en formato checksum.
- `AUTH_CHALLENGE.nonce` es único; un desafío con `consumed_at` distinto de nulo se rechaza, lo que impide reutilizar una firma.
- `AUTH_CHALLENGE.expires_at` es siempre posterior a `issued_at`, y la verificación rechaza los desafíos vencidos.
- `PROFILE.contact_value` se valida contra el formato de `contact_type` antes de guardarse.

### 5.3. Bounded Context: Reputation

El Reputation Context calcula y expone la confianza que merece cada prestatario. Es el diferenciador de LatiFi: sustituye al colateral por un score híbrido que combina resultados on-chain con señales off-chain. Vive en LatiFi API y se alimenta del Event Indexer, que actúa como Anti-Corruption Layer entre la cadena y el dominio.

El contexto también aloja la proyección de lectura de los préstamos. Como el contrato es la única fuente de verdad, la API mantiene una copia derivada de sus eventos para servir el feed y las listas sin consultar la cadena en cada pantalla. Esa copia nunca decide el estado de un préstamo: solo lo refleja.

Las decisiones de diseño del contexto son:

- **Score de 0 a 100 con niveles.** El número alimenta el orden del feed y el nivel (`NEW`, `BUILDING`, `TRUSTED`, `EXCELLENT`) alimenta la etiqueta que ve el prestamista.
- **Cambios graduales y explicables.** Cada variación queda registrada como un `ReputationEvent` con su motivo y la transacción que la originó, de modo que la historia del score siempre puede auditarse.
- **Idempotencia por transacción y posición del log.** Procesar dos veces el mismo evento on-chain no cambia el score, porque el par `txHash` y `logIndex` es único.
- **Política configurable.** Los parámetros del cálculo viven en una clase de política y no en el código de los casos de uso, para ajustarlos sin tocar el flujo.

La política inicial del cálculo es la siguiente:

| Situación | Efecto sobre el score |
|---|---|
| Prestatario sin perfil completo | Score inicial de 30 |
| Perfil con nombre y contacto | Suma 10 puntos una sola vez (score inicial de 40) |
| Pago puntual | Suma 5 puntos; suma 7 mientras el score esté por debajo del máximo que alcanzó el prestatario (recuperación gradual) |
| Pago tardío | Resta 2 puntos por día de atraso, con un tope de 15 |
| Incumplimiento | Resta 30 puntos |

El score siempre se mantiene entre 0 y 100. Los niveles son `NEW` de 0 a 39, `BUILDING` de 40 a 59, `TRUSTED` de 60 a 79 y `EXCELLENT` de 80 a 100.

#### 5.3.1. Domain Layer

| Clase | Tipo | Propósito | Atributos y métodos |
|---|---|---|---|
| `ReputationProfile` | Aggregate Root | Reputación vigente de un prestatario. | `address: WalletAddress`, `score: ReputationScore`, `level: ReputationLevel`, `onTimeCount`, `lateCount`, `defaultCount`, `peakScore`, `profileComplete`, `updatedAt`; `applyOutcome(outcome, policy): ReputationEvent`, `applyProfileSignal(complete, policy): ReputationEvent` |
| `ReputationScore` | Value Object | Puntaje acotado entre 0 y 100. | `value: Int`; `plus(delta): ReputationScore`, `minus(delta): ReputationScore`, `level(): ReputationLevel` |
| `ReputationLevel` | Enumeración | Nivel que se muestra al prestamista. | `NEW`, `BUILDING`, `TRUSTED`, `EXCELLENT` |
| `ReputationEvent` | Entity | Registro de una variación del score y de su causa. | `id`, `address`, `loanId`, `type: ReputationEventType`, `delta`, `scoreAfter`, `daysLate`, `chainEventId`, `occurredAt` |
| `ReputationEventType` | Enumeración | Causa de la variación. | `PROFILE_COMPLETED`, `REPAID_ON_TIME`, `REPAID_LATE`, `DEFAULTED` |
| `LoanOutcome` | Value Object | Resultado de un préstamo ya traducido a lenguaje de dominio por el Anti-Corruption Layer. | `loanId`, `borrower`, `kind: OutcomeKind`, `amountPaid`, `daysLate`, `txHash`, `logIndex`, `occurredAt` |
| `OutcomeKind` | Enumeración | Tipo de resultado. | `BORROWER_REPAID_ON_TIME`, `BORROWER_REPAID_LATE`, `BORROWER_DEFAULTED` |
| `ReputationPolicy` | Domain Service | Contiene los parámetros y calcula la variación de cada situación. | `initialScore`, `profileBonus`, `onTimeGain`, `recoveryGain`, `latePenaltyPerDay`, `latePenaltyCap`, `defaultPenalty`; `deltaFor(profile, outcome): Int` |
| `LoanSummary` | Entity (proyección) | Copia de lectura de un préstamo, derivada de eventos. | `loanId`, `borrower`, `lender`, `principal`, `interestRateBps`, `termDays`, `installments`, `status`, `totalDue`, `amountRepaid`, `requestedAt`, `fundedAt`, `finalDueDate`; `apply(chainEvent)`, `installmentsPaid()`, `nextDueDate()` |
| `ChainEvent` | Entity | Evento on-chain recibido, con su posición exacta. | `txHash`, `logIndex`, `blockNumber`, `eventName`, `loanId`, `payload`, `processedAt` |
| `IndexerCheckpoint` | Entity | Último bloque procesado del contrato. | `contractAddress`, `lastProcessedBlock`, `updatedAt` |
| `ReputationRepository`, `ReputationEventRepository`, `LoanSummaryRepository`, `ChainEventRepository`, `IndexerCheckpointRepository` | Repositorios (interfaces) | Puertos de persistencia del contexto. | `findByAddress`, `save`, `existsByTxHashAndLogIndex`, `findFeed(filter, sort)` |
| `ChainEventSource` | Domain Service (interfaz) | Puerto por el que el dominio obtiene eventos de la cadena. | `fetch(fromBlock, toBlock): List<RawLog>`, `latestBlock(): Long` |

Invariantes: el score nunca sale del rango de 0 a 100; un `ChainEvent` se procesa una sola vez; cada cambio de score genera exactamente un `ReputationEvent`; la proyección `LoanSummary` solo avanza hacia estados posteriores del préstamo.

La proyección usa los nombres de la base de datos y no los de los eventos. Guarda el `amount` de `LoanRequested` como `principal` y el `dueDate` de `LoanFunded` como `finalDueDate`, y deja el `outstandingAmount` de `LoanDefaulted` solo en el `payload` del `ChainEvent`. No guarda `installmentsPaid()` ni `nextDueDate()`: los calcula a partir de `amountRepaid`, `totalDue`, `installments` y la regla de cuotas de `docs/EVENTS.md` del repositorio `latifi-contracts`. La primera devuelve el número de cuotas que `amountRepaid` ya cubre. La segunda devuelve el vencimiento de la primera cuota que falta, o nulo cuando no queda ninguna.

#### 5.3.2. Interface Layer

Interfaz REST de LatiFi API:

| Controlador | Operación | Propósito | Historia |
|---|---|---|---|
| `ReputationController` | `GET /reputation/{address}` | Devuelve score, nivel y contadores de un prestatario. | US-REP-02, US-API-01 |
| `ReputationController` | `GET /reputation/{address}/history` | Lista paginada (`page` y `size`) de los `ReputationEvent` con la referencia de transacción de cada uno. El filtro opcional `type` (`PROFILE_COMPLETED`, `REPAID_ON_TIME`, `REPAID_LATE` o `DEFAULTED`) alimenta los chips de resultado de 6.2.3. | US-API-01 |
| `LoanFeedController` | `GET /loans` | Lista préstamos por páginas (`page` y `size`) con filtros `status`, `minAmount`, `maxAmount`, `maxTermDays`, `minLevel`, `borrower` y `lender`. El orden `sort` admite `reputation` (por defecto), `amount`, `term`, `rate`, `recent` y `nextDue`. La respuesta trae `items` y `totalItems`, que alimenta el contador de resultados de 6.2.3. | US-LEND-02, US-REP-03, US-LEND-05 |
| `LoanFeedController` | `GET /loans/{loanId}` | Devuelve el mismo `LoanSummary` que la lista, con su estado y la reputación del prestatario. | US-LEND-05 |

El contrato completo es el borrador OpenAPI del repositorio `latifi-api`: https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-api/blob/develop/openapi/latifi-api.v0.yaml.

Consumidores internos del contexto:

| Clase | Tipo | Propósito |
|---|---|---|
| `ChainEventPoller` | Consumer programado | Dispara un ciclo de indexación a intervalo fijo. |
| `ProfileEventListener` | Event listener | Recibe `ProfileCreated` y `ProfileUpdated` del Identity/Wallet Context. |

#### 5.3.3. Application Layer

| Clase | Tipo | Flujo |
|---|---|---|
| `EventIndexingService` | Servicio de aplicación | Lee desde el checkpoint hasta el último bloque, traduce cada log, entrega el resultado a los manejadores y avanza el checkpoint en la misma transacción. |
| `RecordLoanOutcomeHandler` | Event Handler | Recibe un `LoanOutcome`, descarta duplicados por `txHash` y `logIndex`, aplica la política, guarda el `ReputationEvent` y actualiza el `ReputationProfile`. |
| `ApplyProfileSignalHandler` | Event Handler | Al recibir un perfil completo, suma la bonificación una sola vez y registra `PROFILE_COMPLETED`. |
| `LoanMirrorProjector` | Event Handler | Aplica `LoanRequested`, `LoanFunded`, `LoanRepaid` y `LoanDefaulted` sobre la proyección de préstamos. |
| `GetReputationQuery` y `GetReputationHistoryQuery` | Query Handlers | Devuelven la reputación y su historia. |
| `ListLoansQuery` | Query Handler | Combina la proyección de préstamos con la reputación para el feed y las listas. |

El flujo de un resultado de préstamo es este: el contrato emite el evento, el indexador lo lee y lo traduce, `RecordLoanOutcomeHandler` recalcula el score y la app lo muestra la próxima vez que consulta la API. El Reputation Context nunca decide si un préstamo está pagado o vencido; solo reacciona al resultado que la cadena ya fijó.

#### 5.3.4. Infrastructure Layer

| Clase | Implementa | Tecnología |
|---|---|---|
| `Web3jChainEventSource` | `ChainEventSource` | web3j sobre JSON-RPC, consulta `eth_getLogs` por rangos de bloques con reintentos y espera creciente |
| `LoanAgreementEventDecoder` | Decodificación de logs | Wrapper de web3j generado desde el ABI de `LoanAgreement` |
| `ChainEventTranslator` | Anti-Corruption Layer | Convierte logs crudos en `LoanOutcome` y en eventos de proyección |
| `JpaReputationRepository` | `ReputationRepository` | Spring Data JPA sobre PostgreSQL |
| `JpaReputationEventRepository` | `ReputationEventRepository` | Spring Data JPA sobre PostgreSQL |
| `JpaLoanSummaryRepository` | `LoanSummaryRepository` | Spring Data JPA con consultas dinámicas de filtro y orden |
| `JpaChainEventRepository` | `ChainEventRepository` | Spring Data JPA con restricción única sobre `tx_hash` y `log_index` |
| `JpaIndexerCheckpointRepository` | `IndexerCheckpointRepository` | Spring Data JPA |

#### 5.3.5. Bounded Context Software Architecture Component Level Diagrams

Container LatiFi API, módulo Reputation y Loan Feed:

```mermaid
C4Component
    title Diagrama de componentes: LatiFi API, módulo Reputation y Loan Feed (Reputation Context)

    Boundary(up, "Actores y clientes", "") {
        Container(wallet, "LatiFi Wallet", "Kotlin, Android", "Consulta feed y reputación")
        Container(indexer, "Event Indexer", "Java, embebido en LatiFi API", "Entrega eventos traducidos")
        Container(identity, "Módulo Identity", "Spring Boot", "Publica ProfileCreated")
    }

    Container_Boundary(api, "LatiFi API [Spring Boot 3.5, Java 21]") {
        Component(repc, "ReputationController", "Spring MVC RestController", "GET /reputation y /history")
        Component(feedc, "LoanFeedController", "Spring MVC RestController", "GET /loans y /loans/{id}")
        Component(queries, "Query Handlers", "Spring Service", "GetReputation, GetHistory, ListLoans")
        Component(outcome, "RecordLoanOutcomeHandler", "Event Handler", "Recalcula el score")
        Component(signal, "ApplyProfileSignalHandler", "Event Handler", "Aplica la señal de perfil")
        Component(projector, "LoanMirrorProjector", "Event Handler", "Actualiza la proyección")
        Component(policy, "ReputationPolicy", "Domain Service", "Parámetros y cálculo")
        Component(repos, "Repositorios JPA", "Spring Data JPA", "Reputación, eventos y préstamos")
    }

    Boundary(down, "Entorno del container", "") {
        ContainerDb(db, "LatiFi DB", "PostgreSQL", "Reputación y préstamos")
    }

    Rel(wallet, repc, "Lee reputación", "REST, HTTPS")
    Rel(wallet, feedc, "Lee feed y préstamos", "REST, HTTPS")
    Rel(indexer, outcome, "LoanOutcome")
    Rel(indexer, projector, "Evento de préstamo")
    Rel(identity, signal, "ProfileCreated")
    Rel(repc, queries, "Usa")
    Rel(feedc, queries, "Usa")
    Rel(outcome, policy, "Calcula variación")
    Rel(signal, policy, "Calcula variación")
    Rel(queries, repos, "Lee")
    Rel(outcome, repos, "Guarda score y evento")
    Rel(projector, repos, "Guarda proyección")
    Rel(repos, db, "SQL", "JDBC")

    UpdateLayoutConfig($c4ShapeInRow="3", $c4BoundaryInRow="1")
```

Container Event Indexer:

```mermaid
C4Component
    title Diagrama de componentes: Event Indexer (Reputation Context)

    Boundary(up, "Actores y clientes", "") {
        System_Ext(amoy, "Polygon Amoy", "Red blockchain de pruebas")
    }

    Container_Boundary(idx, "Event Indexer [Java 21, embebido en LatiFi API]") {
        Component(poller, "ChainEventPoller", "Spring Scheduler", "Dispara cada ciclo")
        Component(service, "EventIndexingService", "Spring Service", "Orquesta el ciclo y el checkpoint")
        Component(source, "Web3jChainEventSource", "web3j", "Obtiene logs por rango de bloques")
        Component(decoder, "LoanAgreementEventDecoder", "web3j, wrapper del ABI", "Decodifica topics y datos")
        Component(acl, "ChainEventTranslator", "Anti-Corruption Layer", "Traduce a lenguaje de dominio")
        Component(store, "Repositorios de checkpoint y eventos", "Spring Data JPA", "Garantiza idempotencia")
    }

    Boundary(down, "Entorno del container", "") {
        Container(rep, "Módulo Reputation", "Spring Boot", "Manejadores de eventos")
        ContainerDb(db, "LatiFi DB", "PostgreSQL", "Checkpoint y eventos")
    }

    Rel(poller, service, "Inicia ciclo")
    Rel(service, source, "Pide logs")
    Rel(source, amoy, "Lee eventos", "eth_getLogs")
    Rel(source, decoder, "Entrega logs")
    Rel(decoder, acl, "Log decodificado")
    Rel(service, store, "Lee y avanza checkpoint")
    Rel(acl, rep, "LoanOutcome y eventos")
    Rel(store, db, "SQL", "JDBC")

    UpdateLayoutConfig($c4ShapeInRow="3", $c4BoundaryInRow="1")
```

#### 5.3.6. Bounded Context Software Architecture Code Level Diagrams

##### 5.3.6.1. Bounded Context Domain Layer Class Diagrams

```mermaid
classDiagram
    class ReputationProfile {
        <<Aggregate Root>>
        -WalletAddress address
        -ReputationScore score
        -ReputationLevel level
        -int onTimeCount
        -int lateCount
        -int defaultCount
        -int peakScore
        -boolean profileComplete
        -Instant updatedAt
        +applyOutcome(outcome, policy) ReputationEvent
        +applyProfileSignal(complete, policy) ReputationEvent
    }
    class ReputationScore {
        <<Value Object>>
        -int value
        +plus(delta) ReputationScore
        +minus(delta) ReputationScore
        +level() ReputationLevel
    }
    class ReputationLevel {
        <<enumeration>>
        NEW
        BUILDING
        TRUSTED
        EXCELLENT
    }
    class ReputationEvent {
        <<Entity>>
        -long id
        -WalletAddress address
        -Long loanId
        -ReputationEventType type
        -int delta
        -int scoreAfter
        -int daysLate
        -Instant occurredAt
    }
    class ReputationEventType {
        <<enumeration>>
        PROFILE_COMPLETED
        REPAID_ON_TIME
        REPAID_LATE
        DEFAULTED
    }
    class LoanOutcome {
        <<Value Object>>
        -long loanId
        -WalletAddress borrower
        -OutcomeKind kind
        -BigInteger amountPaid
        -int daysLate
        -String txHash
        -int logIndex
    }
    class ReputationPolicy {
        <<Domain Service>>
        -int initialScore
        -int profileBonus
        -int onTimeGain
        -int recoveryGain
        -int latePenaltyPerDay
        -int latePenaltyCap
        -int defaultPenalty
        +deltaFor(profile, outcome) int
    }
    class LoanSummary {
        <<Entity>>
        -long loanId
        -WalletAddress borrower
        -WalletAddress lender
        -BigInteger principal
        -int interestRateBps
        -int termDays
        -int installments
        -String status
        -BigInteger totalDue
        -BigInteger amountRepaid
        -Instant fundedAt
        +apply(event) void
        +installmentsPaid() int
        +nextDueDate() Instant
    }
    class ChainEvent {
        <<Entity>>
        -String txHash
        -int logIndex
        -long blockNumber
        -String eventName
        -Long loanId
        -Instant processedAt
    }
    class IndexerCheckpoint {
        <<Entity>>
        -String contractAddress
        -long lastProcessedBlock
        +advanceTo(block) void
    }
    class ChainEventSource {
        <<interface>>
        +fetch(fromBlock, toBlock) List~RawLog~
        +latestBlock() long
    }

    ReputationProfile "1" *-- "1" ReputationScore : tiene
    ReputationProfile "1" o-- "0..*" ReputationEvent : registra
    ReputationScore "1" --> "1" ReputationLevel : determina
    ReputationEvent "0..*" --> "1" ReputationEventType : es de tipo
    ReputationProfile ..> ReputationPolicy : calcula con
    ReputationProfile ..> LoanOutcome : reacciona a
    ChainEvent "1" --> "0..1" ReputationEvent : origina
    ChainEvent "1" --> "0..1" LoanSummary : actualiza
    IndexerCheckpoint ..> ChainEventSource : avanza con
```

##### 5.3.6.2. Bounded Context Database Diagram

```mermaid
erDiagram
    REPUTATION_PROFILE {
        char42 address PK
        smallint score "entre 0 y 100"
        varchar level "NEW, BUILDING, TRUSTED, EXCELLENT"
        smallint peak_score
        integer on_time_count
        integer late_count
        integer default_count
        boolean profile_complete
        timestamptz updated_at
    }
    CHAIN_EVENT {
        bigint id PK
        char66 tx_hash UK
        integer log_index UK
        bigint block_number
        varchar event_name
        bigint loan_id FK
        jsonb payload
        timestamptz processed_at
    }
    REPUTATION_EVENT {
        bigint id PK
        char42 address FK
        bigint loan_id
        varchar event_type
        smallint delta
        smallint score_after
        smallint days_late
        bigint chain_event_id FK
        timestamptz occurred_at
    }
    LOAN_MIRROR {
        bigint loan_id PK
        char42 borrower_address FK
        char42 lender_address
        numeric principal
        integer interest_rate_bps
        integer term_days
        smallint installments
        numeric total_due
        numeric amount_repaid
        varchar status "OPEN, ACTIVE, REPAID, DEFAULTED"
        timestamptz requested_at
        timestamptz funded_at
        timestamptz final_due_date
        bigint last_block
    }
    INDEXER_CHECKPOINT {
        char42 contract_address PK
        bigint last_processed_block
        timestamptz updated_at
    }

    REPUTATION_PROFILE ||--o{ REPUTATION_EVENT : "acumula"
    REPUTATION_PROFILE ||--o{ LOAN_MIRROR : "solicita"
    LOAN_MIRROR ||--o{ CHAIN_EVENT : "se actualiza con"
    CHAIN_EVENT ||--o| REPUTATION_EVENT : "origina"
```

Restricciones del esquema:

- `CHAIN_EVENT` tiene una restricción única sobre `tx_hash` y `log_index`, que vuelve idempotente el procesamiento de eventos.
- `REPUTATION_PROFILE.score` y `peak_score` están acotados entre 0 y 100 mediante una restricción `CHECK`.
- `REPUTATION_EVENT.chain_event_id` es nulo para los eventos que no provienen de la cadena, como `PROFILE_COMPLETED`.
- `LOAN_MIRROR.borrower_address` referencia a `REPUTATION_PROFILE`, que se crea con el score inicial la primera vez que aparece un prestatario.
- `LOAN_MIRROR.status` solo admite valores del conjunto `OPEN`, `ACTIVE`, `REPAID` y `DEFAULTED`.
- Los índices cubren `LOAN_MIRROR(status, requested_at)` y `REPUTATION_EVENT(address, occurred_at)` para el feed y para el historial paginado.

### 5.4. Bounded Context: Exchange Rate

El Exchange Rate Context convierte montos de stablecoin a la moneda local del usuario para que un prestatario sin experiencia entienda cuánto debe o cuánto recibe (US-LEND-06). Es un contexto de presentación: ningún dato de precio entra al contrato ni modifica el estado de un préstamo, lo que elimina el riesgo de manipulación de oráculo que identificó el Capítulo IV.

Las decisiones de diseño del contexto son:

- **La app nunca llama al proveedor externo.** Solo LatiFi API consulta las tasas, las cachea y las expone con un endpoint propio (US-API-02).
- **Refresco programado, no por petición.** Un trabajo periódico actualiza las tasas; las conversiones siempre leen de la caché, de modo que un proveedor lento o caído no afecta la respuesta al usuario.
- **Valor vencido pero disponible.** Si el proveedor falla, la API devuelve la última tasa guardada con la marca `stale`, y la app puede avisar que el valor es aproximado.
- **Paridad supuesta de la stablecoin.** La conversión toma la stablecoin como equivalente a un dólar estadounidense y aplica la tasa del dólar a la moneda local.

#### 5.4.1. Domain Layer

| Clase | Tipo | Propósito | Atributos y métodos |
|---|---|---|---|
| `ExchangeRate` | Aggregate Root | Tasa vigente de un par de monedas. | `pair: CurrencyPair`, `rate: BigDecimal`, `source: String`, `fetchedAt: Instant`; `isStale(now, ttl): Boolean`, `convert(amount: StablecoinAmount): LocalAmount`, `refresh(newRate, fetchedAt)` |
| `CurrencyPair` | Value Object | Par de moneda base y moneda local. | `base: CurrencyCode`, `quote: CurrencyCode` |
| `CurrencyCode` | Value Object | Código de moneda ISO 4217. | `value: String`; valida tres letras mayúsculas |
| `StablecoinAmount` | Value Object | Monto de stablecoin en unidades mínimas. | `units: BigInteger`, `decimals: Int`; `toDecimal(): BigDecimal` |
| `LocalAmount` | Value Object | Resultado de una conversión. | `value: BigDecimal`, `currency: CurrencyCode`, `rate: BigDecimal`, `asOf: Instant`, `stale: Boolean` |
| `ExchangeRateRefreshed` | Domain Event | Se emite cuando se actualiza la caché de tasas. | `pair`, `rate`, `fetchedAt` |
| `ExchangeRateProvider` | Domain Service (interfaz) | Puerto hacia el proveedor externo de tasas. | `fetchRates(base, quotes): List<RateQuote>` |
| `ExchangeRateRepository` | Repositorio (interfaz) | Puerto de persistencia de tasas e historial. | `findByPair(pair)`, `findAll()`, `save(rate)` |

Invariantes: la tasa es siempre mayor que cero; el par se identifica por base y moneda local, sin repeticiones; una conversión indica siempre desde qué instante proviene la tasa que usó.

#### 5.4.2. Interface Layer

| Controlador | Operación | Propósito | Historia |
|---|---|---|---|
| `ExchangeRateController` | `GET /exchange-rate/convert?amount={units}&currency={code}` | Convierte un monto de stablecoin a la moneda local. Devuelve valor, tasa, instante de la tasa y la marca `stale`. | US-API-02, US-LEND-06 |
| `ExchangeRateController` | `GET /exchange-rate/rates` | Lista las tasas disponibles y su antigüedad. | US-API-02 |

`GET /exchange-rate/rates` devuelve una lista con `base`, `quote`, `rate`, el instante de la tasa (`asOf`) y la marca `stale`. `GET /exchange-rate/convert` responde 200 con `stale` en verdadero cuando el proveedor está caído y la API usa la última tasa guardada. Una moneda no soportada devuelve el código 400 con un mensaje localizado según `Accept-Language`.

El contrato completo es el borrador OpenAPI del repositorio `latifi-api`: https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-api/blob/develop/openapi/latifi-api.v0.yaml.

#### 5.4.3. Application Layer

| Clase | Tipo | Flujo |
|---|---|---|
| `ConvertAmountQuery` | Query Handler | Busca la tasa del par, construye el `StablecoinAmount`, convierte y marca el resultado como `stale` si superó el tiempo de vida configurado. |
| `ListRatesQuery` | Query Handler | Devuelve todas las tasas guardadas con su antigüedad. |
| `RefreshRatesHandler` | Command Handler | Pide al proveedor las tasas de las monedas configuradas, actualiza cada `ExchangeRate`, guarda el historial y publica `ExchangeRateRefreshed`. Si el proveedor falla, conserva la tasa anterior. |
| `RateRefreshJob` | Disparador programado | Invoca a `RefreshRatesHandler` cada hora. |

#### 5.4.4. Infrastructure Layer

| Clase | Implementa | Tecnología |
|---|---|---|
| `HttpExchangeRateProvider` | `ExchangeRateProvider` | Cliente HTTP de Spring con tiempo de espera de tres segundos y dos reintentos |
| `JpaExchangeRateRepository` | `ExchangeRateRepository` | Spring Data JPA sobre PostgreSQL |
| `RateRefreshJob` | Planificador | `@Scheduled` de Spring |
| `ExchangeRateProperties` | Configuración | Monedas soportadas, tiempo de vida de la caché y dirección del proveedor |

#### 5.4.5. Bounded Context Software Architecture Component Level Diagrams

```mermaid
C4Component
    title Diagrama de componentes: LatiFi API, módulo Exchange Rate (Exchange Rate Context)

    Boundary(up, "Actores y clientes", "") {
        Container(wallet, "LatiFi Wallet", "Kotlin, Android", "Pide conversiones")
    }

    Container_Boundary(api, "LatiFi API [Spring Boot 3.5, Java 21]") {
        Component(ctrl, "ExchangeRateController", "Spring MVC RestController", "GET /exchange-rate/convert y /rates")
        Component(query, "ConvertAmountQuery y ListRatesQuery", "Spring Service", "Conversión desde la caché")
        Component(job, "RateRefreshJob", "Spring Scheduler", "Dispara el refresco cada hora")
        Component(refresh, "RefreshRatesHandler", "Spring Service", "Actualiza tasas e historial")
        Component(provider, "HttpExchangeRateProvider", "Spring HTTP client", "Consulta al proveedor con reintentos")
        Component(repo, "JpaExchangeRateRepository", "Spring Data JPA", "Persistencia")
    }

    Boundary(down, "Entorno del container", "") {
        ContainerDb(db, "LatiFi DB", "PostgreSQL", "Tasas e historial")
        System_Ext(fx, "API de Tasas de Cambio", "Proveedor externo de cotizaciones")
    }

    Rel(wallet, ctrl, "Convierte montos", "REST, HTTPS")
    Rel(ctrl, query, "Usa")
    Rel(query, repo, "Lee tasa vigente")
    Rel(job, refresh, "Invoca")
    Rel(refresh, provider, "Pide tasas")
    Rel(refresh, repo, "Guarda tasa e historial")
    Rel(provider, fx, "Consulta cotizaciones", "HTTPS")
    Rel(repo, db, "SQL", "JDBC")

    UpdateLayoutConfig($c4ShapeInRow="3", $c4BoundaryInRow="1")
```

#### 5.4.6. Bounded Context Software Architecture Code Level Diagrams

##### 5.4.6.1. Bounded Context Domain Layer Class Diagrams

```mermaid
classDiagram
    class ExchangeRate {
        <<Aggregate Root>>
        -CurrencyPair pair
        -BigDecimal rate
        -String source
        -Instant fetchedAt
        +isStale(now, ttl) boolean
        +convert(amount) LocalAmount
        +refresh(newRate, fetchedAt) void
    }
    class CurrencyPair {
        <<Value Object>>
        -CurrencyCode base
        -CurrencyCode quote
    }
    class CurrencyCode {
        <<Value Object>>
        -String value
    }
    class StablecoinAmount {
        <<Value Object>>
        -BigInteger units
        -int decimals
        +toDecimal() BigDecimal
    }
    class LocalAmount {
        <<Value Object>>
        -BigDecimal value
        -CurrencyCode currency
        -BigDecimal rate
        -Instant asOf
        -boolean stale
    }
    class ExchangeRateProvider {
        <<interface>>
        +fetchRates(base, quotes) List~RateQuote~
    }
    class ExchangeRateRepository {
        <<interface>>
        +findByPair(pair) ExchangeRate
        +findAll() List~ExchangeRate~
        +save(rate) void
    }
    class ExchangeRateRefreshed {
        <<Domain Event>>
        -CurrencyPair pair
        -BigDecimal rate
        -Instant fetchedAt
    }

    ExchangeRate "1" *-- "1" CurrencyPair : identifica por
    CurrencyPair "1" --> "2" CurrencyCode : usa
    ExchangeRate ..> StablecoinAmount : convierte
    ExchangeRate ..> LocalAmount : produce
    ExchangeRate ..> ExchangeRateRefreshed : emite al refrescar
    ExchangeRateRepository ..> ExchangeRate : persiste
    ExchangeRateProvider ..> ExchangeRate : alimenta
```

##### 5.4.6.2. Bounded Context Database Diagram

```mermaid
erDiagram
    EXCHANGE_RATE {
        bigint id PK
        char3 base_currency UK
        char3 quote_currency UK
        numeric rate "mayor que cero, 8 decimales"
        varchar source
        timestamptz fetched_at
    }
    EXCHANGE_RATE_HISTORY {
        bigint id PK
        bigint exchange_rate_id FK
        numeric rate
        timestamptz fetched_at
    }

    EXCHANGE_RATE ||--o{ EXCHANGE_RATE_HISTORY : "conserva"
```

Restricciones del esquema:

- `EXCHANGE_RATE` tiene una restricción única sobre `base_currency` y `quote_currency`, de modo que cada par tiene una sola tasa vigente.
- `rate` lleva una restricción `CHECK` que exige un valor mayor que cero.
- `EXCHANGE_RATE_HISTORY` solo se agrega: no se actualiza ni se borra, y permite reconstruir qué tasa vio un usuario en un momento dado.
- El índice sobre `EXCHANGE_RATE_HISTORY(exchange_rate_id, fetched_at)` acelera la consulta del historial reciente.

### 5.5. Bounded Context: Marketing/Landing

El Marketing/Landing Context sirve el sitio institucional. No comparte modelo, usuarios autenticados ni ciclo de despliegue con el resto del sistema, así que su diseño táctico es el más breve: no tiene agregados de negocio ni base de datos, y sus reglas son de presentación. Aun así conserva las cuatro capas para que el código de la landing mantenga la misma separación de responsabilidades que el resto de los contextos.

Las decisiones de diseño del contexto son:

- **Contenido separado de la estructura.** Los textos viven en diccionarios JSON por idioma, de modo que añadir un idioma no exige tocar el HTML.
- **Idioma según el navegador, con selector manual.** La página arranca en el idioma del navegador cuando está soportado, usa `en_US` como alternativa y recuerda la elección del visitante (US-LAND-02).
- **Sin dependencia técnica de otros contextos.** El único vínculo es un enlace de descarga hacia la app.

#### 5.5.1. Domain Layer

| Clase | Tipo | Propósito | Atributos y métodos |
|---|---|---|---|
| `Locale` | Value Object | Idioma soportado por el sitio. | `code: String` con valores `en_US` y `es_419`; `fromBrowser(languages): Locale` |
| `TranslationDictionary` | Value Object | Conjunto de textos de un idioma, indexado por clave. | `locale: Locale`, `entries: Map<String, String>`; `get(key): String` |
| `PageSection` | Entity | Sección anclada de la página. | `id`, `anchor`, `titleKey`, `audience` (prestatario, prestamista o ambos) |
| `SeoMetadata` | Value Object | Etiquetas de cabecera de una página en un idioma. | `title` (hasta 60 caracteres), `description` (hasta 155), `keywords`, `canonical`, `openGraph`, `robots` |
| `DownloadTarget` | Value Object | Destino del botón de descarga. | `url`, `label` |

#### 5.5.2. Interface Layer

| Elemento | Propósito | Historia |
|---|---|---|
| `index.html` | Página única con las secciones How it works, Benefits, Security, FAQ y Download. | US-LAND-01 |
| `terms.html` y `privacy.html` | Términos y condiciones y política de privacidad, accesibles desde el pie de página. | US-LAND-02 |
| `LanguageSelector` | Control visible que cambia el idioma. | US-LAND-02 |
| `FaqAccordion` | Acordeón de preguntas frecuentes operable por teclado. | US-LAND-02 |
| `SkipLink` y `MobileMenu` | Salto al contenido y menú compacto para teléfonos, con foco visible. | US-LAND-02 |

#### 5.5.3. Application Layer

| Clase | Flujo |
|---|---|
| `LanguageSwitcher` | Detecta el idioma, carga el diccionario, reemplaza los textos, fija el atributo `lang` y guarda la preferencia. |
| `SeoMetadataUpdater` | Actualiza título, descripción, `hreflang` y etiquetas sociales al cambiar de idioma. |
| `SectionNavigator` | Desplaza suavemente hacia cada ancla y marca la sección activa en el menú. |
| `DownloadLinkResolver` | Entrega el destino de descarga vigente a cada botón de acción. |

#### 5.5.4. Infrastructure Layer

| Clase o recurso | Propósito | Tecnología |
|---|---|---|
| `i18n/en_US.json` y `i18n/es_419.json` | Diccionarios de texto versionados en el repositorio. | JSON |
| `LocalePreferenceStore` | Guarda la elección del visitante, con respaldo si el almacenamiento no está disponible. | `localStorage` |
| Hosting estático | Publica el sitio por HTTPS desde la rama `main`. | Servidor estático en el VPS administrado con Dokploy |
| Hojas de estilo | Aplican la guía de estilo y el diseño responsive. | CSS3 con Material Design |

#### 5.5.5. Bounded Context Software Architecture Component Level Diagrams

```mermaid
C4Component
    title Diagrama de componentes: Landing Page (Marketing/Landing Context)

    Boundary(up, "Actores y clientes", "") {
        Person(visitor, "Visitante web", "Prestatario o prestamista potencial")
    }

    Container_Boundary(landing, "Landing Page [HTML5, CSS3, JavaScript, Material Design]") {
        Component(page, "index.html, terms.html y privacy.html", "HTML5", "Estructura y secciones")
        Component(lang, "LanguageSwitcher", "JavaScript", "Idioma y diccionario activo")
        Component(seo, "SeoMetadataUpdater", "JavaScript", "Metadatos por idioma")
        Component(nav, "SectionNavigator y FaqAccordion", "JavaScript", "Navegación y acordeón accesibles")
        Component(dl, "DownloadLinkResolver", "JavaScript", "Destino de descarga")
        Component(dict, "Diccionarios i18n", "JSON", "Textos en_US y es_419")
        Component(store, "LocalePreferenceStore", "localStorage", "Preferencia de idioma")
    }

    Boundary(down, "Entorno del container", "") {
        Container(wallet, "LatiFi Wallet", "Kotlin, Android", "Destino de la descarga")
    }

    Rel(visitor, page, "Navega", "HTTPS")
    Rel(page, lang, "Inicia al cargar")
    Rel(page, nav, "Usa")
    Rel(page, dl, "Resuelve botones")
    Rel(lang, seo, "Notifica el cambio")
    Rel(lang, dict, "Carga textos")
    Rel(lang, store, "Lee y guarda idioma")
    Rel(dl, wallet, "Enlaza a la descarga")

    UpdateLayoutConfig($c4ShapeInRow="3", $c4BoundaryInRow="1")
```

#### 5.5.6. Bounded Context Software Architecture Code Level Diagrams

##### 5.5.6.1. Bounded Context Domain Layer Class Diagrams

```mermaid
classDiagram
    class Locale {
        <<Value Object>>
        -String code
        +fromBrowser(languages) Locale
    }
    class TranslationDictionary {
        <<Value Object>>
        -Locale locale
        -Map~String,String~ entries
        +get(key) String
    }
    class PageSection {
        <<Entity>>
        -String id
        -String anchor
        -String titleKey
        -String audience
    }
    class SeoMetadata {
        <<Value Object>>
        -String title
        -String description
        -String keywords
        -String canonical
        -String robots
    }
    class DownloadTarget {
        <<Value Object>>
        -String url
        -String label
    }
    class LanguageSwitcher {
        <<Application Service>>
        +apply(locale) void
        +detect() Locale
    }

    TranslationDictionary "1" --> "1" Locale : pertenece a
    SeoMetadata "1" --> "1" Locale : se publica en
    PageSection "1" --> "1" TranslationDictionary : se titula con
    LanguageSwitcher ..> TranslationDictionary : carga
    LanguageSwitcher ..> SeoMetadata : actualiza
    PageSection ..> DownloadTarget : puede enlazar a
```

##### 5.5.6.2. Bounded Context Database Diagram

El contexto no persiste datos de usuarios: no hay base de datos ni formularios que almacenen información. Lo único que persiste es el contenido, que vive como archivos JSON versionados junto al código. El diagrama muestra su estructura lógica, que es la que valida la integración continua para garantizar que ningún idioma quede con textos sin traducir.

```mermaid
erDiagram
    LOCALE {
        string code PK "en_US o es_419"
        string language_tag "valor del atributo lang"
    }
    TRANSLATION_ENTRY {
        string locale_code PK, FK
        string key PK
        string text "no vacío"
    }
    PAGE_SEO {
        string page PK "index, terms o privacy"
        string locale_code PK, FK
        string title "hasta 60 caracteres"
        string description "hasta 155 caracteres"
        string canonical
    }

    LOCALE ||--o{ TRANSLATION_ENTRY : "contiene"
    LOCALE ||--o{ PAGE_SEO : "define"
```

Restricciones de contenido:

- Cada clave de `TRANSLATION_ENTRY` existe en ambos idiomas; la integración continua falla si falta alguna.
- `PAGE_SEO.title` no supera los 60 caracteres y `PAGE_SEO.description` no supera los 155.
- `LOCALE.code` solo admite `en_US` y `es_419`; añadir un idioma consiste en agregar un archivo JSON, sin cambios de estructura.

## Capítulo VI: Solution UX Design

### 6.1. Style Guidelines

Las guías de estilo de LatiFi Wallet establecen las reglas visuales y de interacción que dan coherencia a la aplicación móvil nativa para Android (Kotlin) y a la landing page (HTML5, CSS3 y JavaScript). Se basan en Material Design 3. La versión para iOS y sus guías de diseño quedan como trabajo futuro. Las guías se orientan a un público que desconfía de las plataformas financieras: la interfaz debe transmitir claridad, seguridad y transparencia, como lo expresó la persona entrevistada al comparar la experiencia con la de su banco.

Los principios que guían las decisiones de diseño son:

| Principio | Descripción |
|---|---|
| Claridad | Un objetivo por pantalla, montos y plazos siempre visibles, lenguaje sencillo. |
| Confianza | Estados y confirmaciones explícitas, colores sobrios y trazabilidad de cada operación. |
| Inclusión | Contraste mínimo WCAG 2.1 AA, texto escalable y estados que no dependen solo del color. |
| Consistencia | Los mismos componentes, colores y reglas en app y web. |

#### 6.1.1. General Style Guidelines

##### Identidad visual

El logotipo representa a dos personas (los nodos del prestatario y del prestamista) unidas por una línea de pulso: “Lati” de latido y “Fi” de finanzas. Se definen versiones sobre fondo claro, oscuro y azul de marca, un ícono de aplicación (Android adaptive), un isotipo sin contenedor para favicon, tamaños mínimos (48, 32 y 20 px), un margen libre igual a la mitad de la altura del isotipo y usos incorrectos que deben evitarse (cambiar colores, deformar o usarlo con bajo contraste).

![Identidad visual de LatiFi](resources/Cap6/6.1.1-identidad-visual.png)

##### Paleta de colores

| Color | HEX | RGB | Uso |
|---|---|---|---|
| Navy 900 | #0B1F3A | 11, 31, 58 | Color primario: textos, barras y botón principal |
| Navy 700 | #14407A | 20, 64, 122 | Enlaces, estados activos e información |
| Green 600 | #0A7D5A | 10, 125, 90 | Éxito y pagos realizados |
| Lime 400 | #C6FF3D | 198, 255, 61 | Acento y llamadas a la acción en modo oscuro |
| Coral 500 | #FF6B4A | 255, 107, 74 | Alertas suaves; solo como fondo o ícono sobre claro |

Colores de estado: éxito #0A7D5A, advertencia #B45309, error #C62828 e información #14407A, cada uno con un fondo suave asociado. Se define también una escala de neutros (#FFFFFF, #F5F7FA, #DDE3EA, #566174, #101828) y dos superficies para modo oscuro (#0B0F14 y #171C24).

Todos los pares de texto y fondo se verificaron con la fórmula de contraste de WCAG 2.1. Por ejemplo, blanco sobre Navy 900 alcanza 16.52:1 y Lime 400 sobre el fondo oscuro 16.27:1. Coral 500 sobre blanco llega solo a 2.82:1, por lo que no se usa como color de texto sobre fondos claros.

![Paleta de colores](resources/Cap6/6.1.1-paleta-de-colores.png)

##### Tipografía

| Estilo | Fuente | Tamaño / interlineado | Uso |
|---|---|---|---|
| Display | Sora Bold | 32 / 40 | Saldos y montos |
| Headline | Sora SemiBold | 24 / 32 | Título de pantalla |
| Title | Sora SemiBold | 18 / 24 | Secciones y tarjetas |
| Body L | Inter Regular | 16 / 24 | Texto principal |
| Body M | Inter Regular | 14 / 20 | Listas y tarjetas |
| Label | Inter SemiBold | 14 / 20 | Botones, tabs y chips |
| Caption | Inter Medium | 12 / 16 | Ayudas y metadatos |

Ambas familias son gratuitas (Google Fonts) y se complementan: Sora aporta personalidad a títulos y cifras, e Inter ofrece alta legibilidad en pantallas pequeñas.

![Tipografía](resources/Cap6/6.1.1-tipografia.png)

##### Fundamentos de diseño

- **Espaciado:** escala de base 4 pt (4, 8, 12, 16, 24, 32, 48). Margen lateral de 16 dp y separación entre tarjetas de 12 a 16 dp.
- **Formas:** radios de 8 (campos), 12 (chips), 16 (tarjetas) y 28 (hojas inferiores).
- **Elevación:** tres niveles (borde, tarjeta y diálogo) con sombras suaves.
- **Iconografía:** Material Symbols Rounded, con trazo de 2 dp. Todo ícono va acompañado de una etiqueta de texto.
- **Accesibilidad:** áreas táctiles de 48 dp, compatibilidad con TalkBack y texto escalable hasta 200 %.
- **Idioma y tema:** la interfaz usa inglés (en_US) por defecto y ofrece español (es_419) cuando el dispositivo lo pide, con en_US como idioma de respaldo. Incluye modo claro y modo oscuro.

![Fundamentos de diseño](resources/Cap6/6.1.1-fundamentos-de-diseno.png)

#### 6.1.2. Web, Mobile & Devices Style Guidelines

##### Aplicación móvil

La aplicación se desarrolla de forma nativa para Android (Kotlin) y sigue Material Design 3. Android es la única plataforma móvil del proyecto. Se diseña primero para teléfono (clase compact) y escala a tablet con un riel lateral de navegación.

Los componentes base son:

| Componente | Especificación |
|---|---|
| Botón primario | Altura de 48 dp, esquinas totalmente redondeadas. Navy 900 con texto blanco en modo claro; Lime 400 con texto oscuro en modo oscuro. |
| Botón secundario | Contorno de 1.5 dp y texto del mismo color. |
| Botón deshabilitado | Fondo gris neutro y texto atenuado. |
| Campo de texto | Altura de 56 dp, etiqueta flotante, borde de 1.5 dp. En error cambia a rojo y muestra un mensaje explícito. |
| Chips de estado | Pagado, Pendiente, En mora y En revisión. Incluyen ícono y texto además del color. |
| Tarjeta de préstamo | Monto, plazo, tasa, estado y barra de progreso de cuotas. |
| Barra superior | Título de pantalla y botón de regreso. |
| Navegación inferior | Cuatro destinos por rol, con indicador de pestaña activa. |

![Componentes móviles](resources/Cap6/6.1.2-componentes-moviles.png)

##### Landing page

La landing page se construye con HTML5, CSS3 y JavaScript, siguiendo Material Design. Usa un enfoque mobile-first con tres clases de tamaño.

| Clase | Rango | Columnas | Margen / canal | Navegación | Dispositivos |
|---|---|---|---|---|---|
| Compact | 0 – 599 px | 4 | 16 / 16 | Menú hamburguesa | Teléfonos |
| Medium | 600 – 1023 px | 8 | 24 / 16 | Menú compacto | Tablets |
| Expanded | ≥ 1024 px | 12 | 24 / 24 | Menú horizontal completo | Laptops y monitores |

El contenedor máximo es de 1200 px. Las imágenes son fluidas, los textos usan unidades relativas (rem) y los botones mantienen al menos 48 px de alto en todos los tamaños.

![Diseño responsive](resources/Cap6/6.1.2-responsive-web.png)

### 6.2. Information Architecture

La arquitectura de información de LatiFi decide cómo se agrupa, se ordena y se nombra el contenido para que un prestatario sin experiencia financiera digital y un prestamista que evalúa riesgo encuentren lo que buscan sin esfuerzo. Las cinco subsecciones siguientes recorren esas decisiones: organización, etiquetado, búsqueda, etiquetas para buscadores y navegación.

#### 6.2.1. Organization Systems

El equipo combina tres esquemas de organización visual y cuatro esquemas de categorización, y asigna cada uno al tipo de información que mejor sirve.

##### Organización visual del contenido

| Esquema | Dónde aplica | Decisión |
|---|---|---|
| Jerárquico (visual hierarchy) | Pantalla Inicio de cada rol, tarjetas de préstamo y feed de Invertir | El dato que decide la acción va primero y más grande: el saldo o el monto en tipografía Display, luego el plazo y la tasa, y al final los metadatos en Caption. El botón primario ocupa un solo lugar por pantalla. |
| Secuencial (step by step) | Solicitud de préstamo, fondeo, pago de cuota, onboarding y verificación de identidad | Un objetivo por paso, con indicador de avance y botón Atrás. La barra inferior se oculta durante estos flujos y cada flujo termina en una pantalla de confirmación con comprobante. |
| Matricial | Portafolio del prestamista, lista de préstamos y comparación de oportunidades | Filas de tarjetas con los mismos campos en la misma posición, de modo que el prestamista compare riesgo, tasa y plazo de varias solicitudes con un vistazo. En tablet las tarjetas pasan a una cuadrícula de dos columnas. |

En la landing page, la jerarquía visual manda sobre las demás: el hero con la propuesta de valor y el llamado a la acción ocupa la primera pantalla, y las secciones siguientes bajan de lo general (cómo funciona) a lo específico (seguridad y preguntas). El paso a paso de Cómo funciona usa un esquema secuencial numerado con los pasos de cada segmento.

##### Esquemas de categorización

| Esquema | Dónde aplica | Decisión |
|---|---|---|
| Por audiencia | Estructura general de la app y contenido de la landing | La app ofrece dos recorridos separados, uno para el prestatario y otro para el prestamista, con su propia barra inferior. La landing presenta bloques diferenciados para cada segmento, en línea con US-LAND-01. |
| Por tópicos | Sección de ayuda, preguntas frecuentes y perfil | Las preguntas se agrupan por tema: cómo funciona, seguridad, pagos y reputación. El perfil agrupa sus ajustes en datos personales, billetera, seguridad e idioma. |
| Cronológico | Historial de operaciones, eventos de reputación y lista de cuotas | El orden por defecto es del más reciente al más antiguo. En cuotas pendientes, la más próxima a vencer va primero. |
| Alfabético | Selector de idioma | Solo donde el usuario conoce el nombre exacto de lo que busca. El resto del contenido no usa orden alfabético porque el valor está en el riesgo, el plazo o la fecha y no en el nombre. |

##### Agrupación de la información por pantalla

| Grupo de información | Contenido | Esquema principal |
|---|---|---|
| Resumen financiero | Saldo, préstamos activos, próximo vencimiento | Jerárquico |
| Oportunidades | Solicitudes abiertas con la reputación visible del solicitante | Matricial, ordenado por reputación |
| Mis préstamos y mi portafolio | Estado, monto, plazo, tasa y progreso de cuotas | Matricial y cronológico |
| Operaciones críticas | Solicitar, fondear, pagar | Secuencial |
| Reputación | Nivel actual y eventos que lo modificaron | Jerárquico y cronológico |
| Ayuda y cuenta | Preguntas frecuentes, perfil, seguridad, idioma | Por tópicos |

Estas decisiones responden a lo que las entrevistas mostraron: el prestamista pide ver el historial de pagos del solicitante antes de decidir, y el prestatario desconfía de las plataformas poco claras. Por eso la reputación y las condiciones del préstamo ocupan el nivel más alto de la jerarquía en cada pantalla donde aparecen.

#### 6.2.2. Labeling Systems

Las etiquetas de LatiFi usan el menor número de palabras posible y el mismo término en la aplicación, la landing page y este informe. El equipo parte del lenguaje ubicuo del Capítulo II y evita la jerga de blockchain en toda pantalla que ve un prestatario sin experiencia previa con criptomonedas, como pide la historia US-AUTH-03. Cuando un término técnico no tiene reemplazo, la interfaz lo acompaña con una explicación breve en el momento en que aparece.

Cada tipo de etiqueta sigue una regla fija:

| Tipo | Regla | Ejemplos |
|---|---|---|
| Destinos de navegación | Un sustantivo, máximo dos palabras | Inicio, Préstamos, Reputación, Invertir, Portafolio, Perfil |
| Acciones | Verbo en infinitivo seguido del objeto | Solicitar préstamo, Fondear, Pagar cuota, Conectar billetera, Ver detalle |
| Estados | Un adjetivo o participio, siempre con ícono y texto | Abierta, Pendiente, Pagado, En mora, En revisión |
| Datos del préstamo | Un sustantivo y su unidad visible | Monto, Tasa, Plazo, Cuota |
| Secciones de la landing | Una o dos palabras, igual al texto del ancla | Cómo funciona, Beneficios, Seguridad, Preguntas, Descargar app |

El equipo reemplaza el vocabulario técnico por palabras que el usuario ya conoce:

| Término técnico | Etiqueta en la interfaz | Motivo |
|---|---|---|
| Wallet | Billetera | Remite a las billeteras digitales cotidianas que el usuario ya conoce. |
| Gas fee | Comisión de red | Se lee como cualquier comisión financiera. |
| Transaction hash | Comprobante | Es lo que el usuario espera recibir tras pagar o invertir. |
| Stablecoin | Moneda digital de prueba, con su equivalente en soles | Aclara que el monto no tiene valor real y evita el término técnico en las pantallas de monto. |
| Default | En mora | Es un término financiero que el usuario ya reconoce. |

Los montos aparecen siempre en la stablecoin y en soles (S/), como exige US-LEND-06. Los estados de una transacción on-chain (pendiente, confirmando, confirmada y fallida) conservan estas mismas palabras en toda la app, de modo que el usuario no necesita consultar un explorador de bloques.

La interfaz sale en inglés (en_US) por defecto y en español (es_419) cuando el dispositivo lo pide. Este informe cita los ejemplos de etiquetas en español para que el equipo los lea con facilidad. Las equivalencias son estas:

| en_US | es_419 |
|---|---|
| Home | Inicio |
| Loans | Préstamos |
| Reputation | Reputación |
| Invest | Invertir |
| Portfolio | Portafolio |
| Profile | Perfil |
| Request a loan | Solicitar préstamo |
| Pay installment | Pagar cuota |

Ningún ícono aparece sin etiqueta de texto. Los íconos decorativos se ocultan a los lectores de pantalla, y los que activan una acción llevan una etiqueta accesible equivalente al texto visible.

#### 6.2.3. Searching Systems

LatiFi no ofrece un buscador global. El contenido de la app se organiza en listas acotadas (solicitudes abiertas, préstamos propios, inversiones y operaciones), y en ese contexto un campo de texto libre aporta menos que un filtro bien ubicado. El equipo prioriza tres medios de ayuda: filtros por chips, criterios de orden y una búsqueda por texto solo en la sección de ayuda, donde el volumen de contenido sí crece.

| Zona | Quién la usa | Filtros | Orden | Resultado |
|---|---|---|---|---|
| Invertir (feed de oportunidades) | Prestamista | Riesgo, plazo y rango de monto | Reputación del solicitante (por defecto), tasa, plazo y más recientes | Tarjeta de solicitud con monto en stablecoin y en soles, tasa, plazo, chip de reputación y botón Fondear |
| Préstamos | Prestatario | Estado: Todos, Abierta, Pendiente, Pagado y En mora | Más reciente primero | Tarjeta de préstamo con monto, plazo, tasa, estado y barra de progreso de cuotas |
| Portafolio | Prestamista | Estado: Todos, Pendiente, Pagado y En mora | Próximo vencimiento primero | Tarjeta de inversión con monto prestado, retorno esperado, estado y fecha de la siguiente cuota |
| Reputación | Prestatario | Resultado: A tiempo, Tardío e Incumplido | Cronológico, del más reciente al más antiguo | Lista de eventos con fecha, monto, resultado y efecto sobre la reputación |
| Ayuda | Ambos | Búsqueda por texto y temas sugeridos | Relevancia | Lista de preguntas con la respuesta resumida y un enlace al detalle |

Los filtros de riesgo se apoyan en la reputación híbrida del solicitante (US-REP-02), y el orden por reputación responde a US-REP-03: el prestamista ve primero los perfiles que le piden menos esfuerzo de revisión, pero siempre puede cambiar el criterio.

Todas las listas filtrables comparten el mismo comportamiento:

1. Los filtros viven en una fila de chips sobre la lista. Cada chip activo muestra una marca y se quita con un toque.
2. Un contador indica cuántos resultados quedan, por ejemplo "12 solicitudes". El lector de pantalla anuncia ese número cada vez que cambia.
3. El botón Limpiar filtros aparece en cuanto hay al menos un filtro activo.
4. Si no hay coincidencias, la pantalla explica la causa y ofrece la salida: "No hay solicitudes con estos filtros. Limpia los filtros para ver todas."
5. La app conserva los filtros elegidos mientras dura la sesión, para que el usuario no los repita al volver desde un detalle.
6. Mientras llegan los datos, la lista muestra marcadores de carga con la forma de las tarjetas.

La landing page tampoco incluye buscador. Es una página única con cinco secciones ancladas, de modo que el encabezado fijo y los enlaces internos llevan al visitante a cualquier contenido en un toque. La sección de preguntas frecuentes agrupa las respuestas por tema (cómo funciona, seguridad y descarga) en un acordeón navegable con teclado.

#### 6.2.4. SEO Tags and Meta Tags

Los SEO tags y los meta tags corresponden a la landing page, el único producto web de LatiFi. La aplicación es nativa y no tiene versión web, así que su visibilidad depende de las fichas de las tiendas, que esta sección cubre al final con los elementos ASO. La landing publica sus textos en inglés (en_US) por defecto y en español (es_419), de acuerdo con US-LAND-02.

Los límites de longitud siguen las prácticas habituales de los buscadores: títulos de hasta 60 caracteres y descripciones de hasta 155.

##### Landing page: página de inicio

| Etiqueta | Valor en_US | Valor es_419 |
|---|---|---|
| title | LatiFi: P2P microloans with verifiable reputation | LatiFi: microcréditos P2P con reputación verificable |
| meta description | LatiFi connects borrowers and lenders through blockchain-based P2P microloans. It never holds your funds and shows each applicant's reputation. | LatiFi conecta a prestatarios y prestamistas con microcréditos P2P sobre blockchain. No custodia tu dinero y muestra la reputación de cada solicitante. |
| meta keywords | microloans, P2P loans, blockchain, stablecoins, credit reputation, digital wallet, LatiFi Wallet, Peru | microcréditos, préstamos P2P, blockchain, stablecoins, reputación crediticia, billetera digital, LatiFi Wallet, Perú |
| meta author | LatiFi | LatiFi |

Google ignora la etiqueta keywords para posicionar, pero el enunciado del curso la exige y otros buscadores todavía la leen, por lo que la landing la incluye con ocho términos como máximo.

Etiquetas complementarias de la landing:

| Etiqueta | Valor |
|---|---|
| html lang | en-US en la versión en inglés y es-419 en la versión en español |
| meta viewport | width=device-width, initial-scale=1 |
| meta robots | index, follow |
| link rel="canonical" | La URL pública de cada página |
| link rel="alternate" hreflang | en-US, es-419 y x-default hacia la versión en inglés |
| og:title, og:description | Los mismos textos del title y la meta description |
| og:type y og:site_name | website y LatiFi |
| og:image | Imagen de 1200 x 630 px con el logotipo sobre el azul de marca |
| twitter:card | summary_large_image |

##### Landing page: páginas legales

| Página | title | meta description |
|---|---|---|
| Términos y condiciones | LatiFi: términos y condiciones | Condiciones de uso de LatiFi Wallet: reglas para solicitar, fondear y pagar microcréditos P2P. |
| Política de privacidad | LatiFi: política de privacidad | Cómo LatiFi trata tus datos de perfil y por qué nunca custodia tus llaves privadas ni tus fondos. |

Estas páginas heredan author, robots, viewport y las etiquetas de idioma de la página de inicio.

##### Elementos ASO de la ficha de Google Play

Android es la única plataforma móvil del proyecto, así que la ficha de Google Play es el único espacio de tienda que este capítulo define. La ficha de la tienda de Apple queda como trabajo futuro, junto con la versión para iOS.

| Elemento | Google Play |
|---|---|
| App Title (30 caracteres) | LatiFi Wallet |
| Descripción corta (80 caracteres) | en_US: Borrow or lend in P2P microloans with verifiable reputation. es_419: Pide o invierte en microcréditos P2P con reputación verificable. |
| Categoría | Finanzas |

Descripción completa de la ficha de Google Play (en_US):

> LatiFi Wallet connects people who need a microloan with people who have spare capital to lend. If you borrow, you post the amount, rate and term, and lenders see your reputation before they decide. If you lend, you review open requests, filter by risk and term, and fund the one you prefer. Agreements run on an automated contract on the Polygon Amoy test network: LatiFi never holds your funds or your private keys. This version is an academic demonstration and uses a test stablecoin with no real monetary value.

Descripción completa de la ficha de Google Play (es_419):

> LatiFi Wallet conecta a personas que necesitan un microcrédito con personas que tienen capital disponible para prestarlo. Si pides un préstamo, publicas el monto, la tasa y el plazo, y los prestamistas ven tu reputación antes de decidir. Si inviertes, revisas las solicitudes abiertas, filtras por riesgo y plazo, y fondeas la que prefieras. Los acuerdos corren en un contrato automático sobre la red de pruebas Polygon Amoy: LatiFi no custodia tus fondos ni tus llaves privadas. Esta versión es una demostración académica y opera con una stablecoin de prueba sin valor monetario real.

#### 6.2.5. Navigation Systems

El sistema de navegación define cómo el usuario se desplaza por la aplicación y la landing page. Se organiza en cuatro tipos de navegación (global, local, contextual y suplementaria), de acuerdo con los principios de arquitectura de información de Rosenfeld y Morville.

##### Navegación de la aplicación móvil

El usuario crea una billetera o importa una que ya tiene, firma el desafío de inicio de sesión, completa un perfil ligero con nombre y contacto, y después elige su rol (prestatario o prestamista). Cada rol tiene una barra de navegación inferior propia con cuatro destinos, un número dentro del límite recomendado por Material Design.

![Mapa de navegación de la app](resources/Cap6/6.2.5-mapa-navegacion-app.png)

El mapa todavía muestra pasos de una versión anterior del alcance. El texto y las tablas de esta sección prevalecen hasta que el equipo rehaga la imagen.

| Tipo | Elemento | Descripción |
|---|---|---|
| Global | Barra inferior (prestatario) | Inicio, Préstamos, Reputación y Perfil. Siempre visible en las pantallas principales. |
| Global | Barra inferior (prestamista) | Inicio, Invertir, Portafolio y Perfil. |
| Local | Pasos de solicitud de préstamo | Stepper de varios pasos con indicador de avance y botón “Atrás”. |
| Local | Filtros de oportunidades | Chips de riesgo y plazo dentro de “Invertir”. |
| Contextual | Tarjetas y avisos | Una tarjeta de préstamo lleva a su detalle; el aviso de cuota próxima, que aparece dentro de Inicio, lleva a “Pagar cuota”. |
| Contextual | Botón de regreso (←) | Vuelve a la pantalla anterior en pantallas de nivel 2 y 3. |
| Suplementaria | Ayuda, idioma y cerrar sesión | Accesibles desde Inicio y Perfil. El recordatorio de una cuota próxima es un aviso dentro de la app, no una notificación. |

Reglas de navegación:

1. La barra inferior solo aparece en las pantallas principales y se oculta durante flujos de varios pasos (solicitud, pago, inversión) para no distraer.
2. Cada pantalla de nivel 2 o 3 tiene un botón de regreso y el gesto de retroceso del sistema.
3. Las operaciones críticas (pagar, invertir) terminan en una pantalla de confirmación y un comprobante.
4. Las pantallas de creación de billetera, inicio de sesión y perfil no muestran la barra inferior.
5. Al reabrir la app con sesión activa, el usuario llega directamente a Inicio de su rol.

Trazabilidad con las historias de usuario:

| Pantalla o sección | Historias de usuario |
|---|---|
| Creación de billetera, firma y sesión | US-AUTH-01 a US-AUTH-04 |
| Perfil ligero | US-IDEN-01, US-IDEN-02 |
| Préstamos (prestatario) | US-LEND-01, US-LEND-04, US-LEND-05, US-LEND-06 |
| Invertir y Portafolio (prestamista) | US-LEND-02, US-LEND-03, US-LEND-05, US-LEND-06, US-REP-03 |
| Reputación | US-REP-01 a US-REP-04 |

##### Navegación de la landing page

La landing page es de una sola página con secciones ancladas. El encabezado fijo lleva a cada sección y el botón principal conduce a la descarga de la aplicación. En móvil el menú se colapsa en un ícono de hamburguesa.

![Mapa de navegación de la landing](resources/Cap6/6.2.5-mapa-navegacion-landing.png)

| Tipo | Elemento | Descripción |
|---|---|---|
| Global | Encabezado fijo | Logo, Cómo funciona, Beneficios, Seguridad, Preguntas y Descargar app. |
| Local | Anclas de sección | Desplazamiento suave hacia #como-funciona, #beneficios, #seguridad, #faq y #descarga. |
| Contextual | Botones “Empezar ahora” | Aparecen en el hero y en cada paso, y llevan a la sección de descarga. |
| Contextual | Botón “Volver arriba” | Aparece tras dos pantallas de desplazamiento. |
| Suplementaria | Pie de página | Términos y condiciones, política de privacidad, contacto, redes sociales y selector de idioma. |

Trazabilidad: la landing responde a las historias US-LAND-01 y US-LAND-02.

### 6.3. Landing Page UI Design

El equipo traduce las decisiones de diseño y de arquitectura de información en dos entregables para la landing page: un wireframe de baja fidelidad que fija la estructura y un mock-up que aplica la guía de estilo de 6.1. Las secciones siguen los cinco anclajes de 6.2.5 (#como-funciona, #beneficios, #seguridad, #faq y #descarga) y la jerarquía de lo general a lo específico que define 6.2.1. El diseño inclusivo parte de A11Y.md: contraste de texto de al menos 4.5:1, estados que no dependen solo del color, etiquetas visibles en los controles, texto que se amplía hasta 200 % y un enlace para saltar al contenido. Las tablas de trazabilidad de 6.3.1 y 6.3.2 unen cada fotograma con las historias US-LAND-01 y US-LAND-02 y anotan qué cumple y qué falta. El enunciado pide una versión para Desktop Web Browser y otra para Mobile Web Browser, y hoy el informe muestra solo la primera.

#### 6.3.1. Landing Page Wireframe
> **Trazabilidad:** La landing page responde a las historias de usuario **US-LAND-01** y **US-LAND-02**.

A continuación, se presenta el diseño estructural de baja fidelidad (Wireframe) de la landing page de la plataforma, el cual define la distribución espacial, la jerarquía de la información y la disposición de los componentes clave antes de la aplicación de la interfaz gráfica final. El diseño se ha estructurado en tres secciones para asegurar su correcta visualización y legibilidad en la documentación:

* **Parte 1: Cabecera, Hero Section y Simulador de Microcrédito**
  Muestra la barra de navegación principal (*Navbar*), el título de alto impacto con la propuesta de valor del protocolo, los botones de acción rápida (*CTAs* para prestatario y prestamista) y el simulador de microcrédito interactivo en la parte superior.
  <div align="center">
    <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1791517699/Captura_de_pantalla_2026-10-08_a_la_s_10.48.14_p._m._whlr2d.png" alt="Landing Wireframe Parte 1 - Hero y Simulador" width="80%"/>
  </div>

* **Parte 2: Flujo de Funcionamiento y Finanzas Justas**
  Detalla la sección explicativa *"¿Cómo Funciona LatiFi?"* mediante un diagrama de flujo en tres pasos secuenciales (Solicitud, Reputación y Desembolso), seguido de la comparativa de finanzas justas y las métricas de impacto social orientadas a bodegas y pequeños negocios locales.
  <div align="center">
    <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1791517720/Captura_de_pantalla_2026-10-08_a_la_s_10.48.32_p._m._sspxnh.png" alt="Landing Wireframe Parte 2 - Funcionamiento e Impacto" width="80%"/>
  </div>

* **Parte 3: Seguridad Criptográfica, Preguntas Frecuentes (FAQ) y Footer**
  Agrupa los módulos de seguridad de grado institucional (arquitectura non-custodial y scoring híbrido), el acordeón interactivo de preguntas frecuentes para resolver fricciones del usuario, y el pie de página (*Footer*) institucional con accesos a la red de pruebas (Testnet) y documentación legal.
  <div align="center">
    <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1791517742/Captura_de_pantalla_2026-10-08_a_la_s_10.48.56_p._m._ix5cyu.png" alt="Landing Wireframe Parte 3 - Seguridad, FAQ y Footer" width="80%"/>
  </div>

**Trazabilidad y coherencia de los wireframes.** Los tres fotogramas corresponden a Desktop Web Browser. No existe todavía un wireframe de Mobile Web Browser, que el enunciado exige, y 6.1.2 pide para esa clase (compact) un menú hamburguesa. Los wireframes son de baja fidelidad y no usan la paleta de 6.1, así que la columna de coherencia revisa estructura, anclas, textos y reglas de A11Y.md que la imagen permite juzgar. Lo que solo el código puede cumplir (contraste medido, tamaño de los objetivos, enlace para saltar al contenido, foco visible, idioma declarado) se verifica al implementar.

| Frame | Dispositivo | Sección de la landing | Historias | Ancla de 6.2.5 | Coherencia |
|---|---|---|---|---|---|
| Landing Wireframe Parte 1 - Hero y Simulador | Desktop Web Browser | Encabezado, hero con los dos botones de segmento y simulador de microcrédito | US-LAND-01, US-LAND-02 | El encabezado ofrece Cómo funciona, Beneficios, Seguridad y Preguntas frecuentes. Falta el destino Descargar app (#descarga): el botón principal dice "Acceder a la web app". | Cumple: botones "Soy prestatario" y "Soy prestamista" que diferencian los segmentos, menú horizontal completo de la clase Expanded y selector de idioma en el encabezado. Difiere: el selector dice "ES (PE)" y 6.2.4 publica es_419 y en_US. El simulador usa un TrustScore de 840 sobre 1000, y el score del informe va de 0 a 100. Muestra el monto en soles con su equivalente en USDC, y la moneda local es solo de referencia según US-LEND-06. No muestra enlace para saltar al contenido. |
| Landing Wireframe Parte 2 - Funcionamiento e Impacto | Desktop Web Browser | Cómo funciona con selector Para prestatarios y Para prestamistas, tres pasos numerados, propuesta de valor y bloque de impacto | US-LAND-01 | Las secciones "¿Cómo funciona LatiFi?" (#como-funciona) y "Finanzas justas" (#beneficios) aparecen con su título. La imagen no dibuja los identificadores de ancla. | Cumple: el selector de segmento da contenido diferenciado, como pide US-LAND-01, y los pasos llevan número y texto. Difiere: el bloque de impacto muestra cifras de ejemplo (microcréditos simulados, tasa de cumplimiento, tiempo de aprobación). Una de ellas habla de aprobación, y en LatiFi un prestamista fondea la solicitud y no hay aprobación. El hueco de la fotografía está marcado como marcador de posición. |
| Landing Wireframe Parte 3 - Seguridad, FAQ y Footer | Desktop Web Browser | Seguridad, preguntas frecuentes, llamado final y pie de página | US-LAND-01, US-LAND-02 | Las secciones Seguridad (#seguridad) y Preguntas frecuentes (#faq) aparecen con su título. No hay sección Descargar (#descarga): el llamado final dice "Conectar wallet Web3". | Cumple: el acordeón de cinco preguntas marca el estado con un símbolo, el pie incluye Términos y condiciones y Política de privacidad, y el módulo de seguridad destaca la custodia por el usuario. Difiere: 6.2.3 agrupa las preguntas por tema (cómo funciona, seguridad y descarga) y el wireframe las lista sin agrupar. El selector de idioma que 6.2.5 ubica en el pie vive en el encabezado. Los botones de redes sociales llevan solo texto entre corchetes. |

#### 6.3.2. Landing Page Mock-up

> **Trazabilidad:** La landing page responde a las historias de usuario **US-LAND-01** y **US-LAND-02**.

##### Parte 1: Hero & Onboarding
Esta primera sección comprende la cabecera de la página (*Header*), el *Hero Section* con la propuesta de valor principal, el simulador de préstamos flotante y los primeros accesos directos (*CTAs*).

![LatiFi Landing Page Parte 1](https://res.cloudinary.com/dx0i2vioe/image/upload/v1791515319/Captura_de_pantalla_2026-10-08_a_la_s_10.08.31_p._m._fehfgs.png)

##### Parte 2: Funcionamiento y Propuesta de Valor
La segunda sección detalla el flujo de funcionamiento de la plataforma en tres pasos clave, junto con el comparativo de finanzas justas y el impacto social en bodegas y comercio local.

![LatiFi Landing Page Parte 2](https://res.cloudinary.com/dx0i2vioe/image/upload/v1791515344/Captura_de_pantalla_2026-10-08_a_la_s_10.08.51_p._m._p3hotu.png)

##### Parte 3: Seguridad, FAQ y Footer
Esta última sección muestra los estándares de seguridad criptográfica de grado institucional, el módulo de preguntas frecuentes (FAQ) interactivo y el pie de página institucional con sus respectivos enlaces legales.

![LatiFi Landing Page Parte 3](https://res.cloudinary.com/dx0i2vioe/image/upload/v1791515348/Captura_de_pantalla_2026-10-08_a_la_s_10.09.03_p._m._csxpxk.png)

**Trazabilidad y coherencia de los mock-ups.** Los tres fotogramas también corresponden a Desktop Web Browser, y falta el mock-up de Mobile Web Browser que el enunciado pide. En la paleta, el mock-up usa Navy 900 para títulos y superficies oscuras y un verde cercano a Green 600 para énfasis, como define 6.1. También usa el lima de los botones principales sobre fondo claro, y 6.1 reserva Lime 400 para el modo oscuro y fija Navy 900 con texto blanco como botón principal en modo claro.

| Frame | Dispositivo | Sección de la landing | Historias | Ancla de 6.2.5 | Coherencia |
|---|---|---|---|---|---|
| LatiFi Landing Page Parte 1 | Desktop Web Browser | Encabezado, hero con botones de segmento, cuatro garantías y simulador de microcrédito, seguido del inicio de Cómo funciona | US-LAND-01, US-LAND-02 | Encabezado con Cómo funciona, Beneficios, Seguridad y Preguntas frecuentes, sin Descargar app. El botón "Acceder a la Web App" ocupa el lugar de #descarga. | Cumple: los botones y los chips llevan ícono y texto, el selector de idioma está a la vista y el titular tiene jerarquía clara. Difiere: el simulador anuncia una "tasa fija comunitaria de 2.4 % al mes" y un "desembolso instantáneo", y en LatiFi el prestatario fija la tasa y un prestamista fondea la solicitud. Muestra un TrustScore de 840 sobre 1000, y el score del informe va de 0 a 100. El paso 1 de Cómo funciona menciona Account Abstraction y sin frases semilla, y ADR-0001 usa una frase de recuperación y ADR-0005 descarta account abstraction. |
| LatiFi Landing Page Parte 2 | Desktop Web Browser | Cómo funciona (tres pasos por segmento), Finanzas justas con cuatro tarjetas y bloque de impacto con fotografía | US-LAND-01 | Muestra los títulos de #como-funciona y #beneficios. | Cumple: las tarjetas combinan ícono, título y texto, y el bloque de impacto mantiene la jerarquía. Difiere: la tarjeta de doble denominación habla de "respaldadas 1:1 en USDC", y la conversión a soles es solo de referencia (US-LEND-06). La cifra "menos de 3 min de aprobación" no corresponde al modelo de fondeo. La fotografía necesita texto alternativo, que se verifica al implementar. |
| LatiFi Landing Page Parte 3 | Desktop Web Browser | Seguridad, preguntas frecuentes, llamado final y pie de página | US-LAND-01, US-LAND-02 | Muestra los títulos de #seguridad y #faq. El llamado final dice "Conectar Wallet Web3" y no lleva a una descarga (#descarga). | Cumple: el pie reúne Términos y condiciones y Política de privacidad, y el acordeón usa un chevron junto al texto. Difiere: la tarjeta de protección menciona oráculos de tasa auditados y el alcance no usa oráculos. Los íconos de redes sociales no llevan texto visible, por lo que necesitan un nombre accesible (se verifica al implementar). El selector de idioma no aparece en el pie. |

### 6.4. Applications UX/UI Design

Las pantallas móviles traducen el modelo de información de 6.2 en dos barras de navegación por rol, filtros por chips y flujos de varios pasos sin barra inferior. La guía de 6.1 fija la paleta Navy 900 y Green 600, las fuentes Sora e Inter, los objetivos táctiles de 48 dp y los chips con ícono y texto. A11Y.md añade el contraste mínimo, las etiquetas visibles en los campos y el anuncio de los cambios de estado. Esta sección avanza de lo simple a lo detallado: 6.4.1 fija la estructura con wireframes, 6.4.2 conecta las pantallas en wireflows, 6.4.3 aplica el diseño final en mock-ups y 6.4.4 recorre los user flows de los dos usuarios principales.

#### 6.4.1. Applications Wireframes

> **Trazabilidad:** Las interfaces móviles responden a las historias de usuario del flujo transaccional y de gestión de microcréditos de la aplicación.

Los 45 wireframes de LatiFi Wallet son de baja fidelidad, en escala de grises y a 540 x 1170 px, con datos de ejemplo. Corresponden al teléfono Android, la única plataforma móvil del alcance, y su texto está en español latino (es_419), que acompaña al inglés (en_US) por defecto. Cada pantalla lleva un identificador: A para autenticación y onboarding, B para el prestatario, C para los estados vacíos y el perfil ligero del prestatario, P para las hojas de estado del pago y L para el prestamista. Siguen la navegación de 6.2.5: una barra inferior de cuatro destinos por rol, sin barra en los flujos de varios pasos. Los chips llevan ícono y texto, los estados de una transacción on-chain usan las palabras pendiente, confirmando, confirmada y fallida, y los montos aparecen en tUSD y en soles (US-LEND-06).

Ambos roles completan un perfil ligero antes de operar (US-IDEN-01), de ahí las pantallas C01, C02, L08 y L16.

##### Autenticación y onboarding

| ID | Wireframe | Pantalla y estado | Historias |
|---|---|---|---|
| A01 | <img src="resources/Cap6/6.4.1-wireframes/A01.png" alt="Wireframe A01: Bienvenida" width="150"/> | Bienvenida, paso 1 de 4: Pide un préstamo, con aviso de que todo se hace con una billetera | US-AUTH-03 |
| A02 | <img src="resources/Cap6/6.4.1-wireframes/A02.png" alt="Wireframe A02: Bienvenida" width="150"/> | Bienvenida, paso 4 de 4: Construye tu reputación, con el aviso de que LatiFi nunca guarda la llave | US-AUTH-03, US-AUTH-02 |
| A03 | <img src="resources/Cap6/6.4.1-wireframes/A03.png" alt="Wireframe A03: Conecta tu billetera" width="150"/> | Conecta tu billetera, con acceso a Conectar billetera y a No tengo una billetera | US-AUTH-01 |
| A04 | <img src="resources/Cap6/6.4.1-wireframes/A04.png" alt="Wireframe A04: Hoja Cómo obtener una billetera" width="150"/> | Hoja Cómo obtener una billetera, con advertencia de que nadie en LatiFi pide la frase de recuperación | US-AUTH-01, US-AUTH-03 |
| A05 | <img src="resources/Cap6/6.4.1-wireframes/A05.png" alt="Wireframe A05: Hoja Confirma que eres tú" width="150"/> | Hoja Confirma que eres tú: firma de un mensaje corto que no mueve dinero | US-AUTH-01, US-AUTH-02 |
| A06 | <img src="resources/Cap6/6.4.1-wireframes/A06.png" alt="Wireframe A06: Hoja Pendiente del inicio de sesión" width="150"/> | Hoja Pendiente del inicio de sesión: paso 1 de 2, con botón Abrir billetera | US-AUTH-04 |
| A07 | <img src="resources/Cap6/6.4.1-wireframes/A07.png" alt="Wireframe A07: Elegir rol" width="150"/> | Elegir rol: Quiero pedir un préstamo o Quiero invertir | US-LEND-01, US-LEND-02 |

##### Prestatario

| ID | Wireframe | Pantalla y estado | Historias |
|---|---|---|---|
| B01 | <img src="resources/Cap6/6.4.1-wireframes/B01.png" alt="Wireframe B01: Inicio del prestatario" width="150"/> | Inicio del prestatario: saldo en tUSD y en soles, reputación, próxima cuota y acceso a Solicitar préstamo | US-LEND-05, US-LEND-06, US-REP-01 |
| B02 | <img src="resources/Cap6/6.4.1-wireframes/B02.png" alt="Wireframe B02: Solicitar préstamo" width="150"/> | Solicitar préstamo, paso 1 de 2: monto, tasa anual, plazo y de 1 a 6 cuotas | US-LEND-01, US-LEND-06 |
| B03 | <img src="resources/Cap6/6.4.1-wireframes/B03.png" alt="Wireframe B03: Revisa tu solicitud" width="150"/> | Revisa tu solicitud, paso 2 de 2: cuota, total a devolver y aviso de la comisión de red | US-LEND-01, US-LEND-06 |
| B04 | <img src="resources/Cap6/6.4.1-wireframes/B04.png" alt="Wireframe B04: Hoja Pendiente de la publicación" width="150"/> | Hoja Pendiente de la publicación: paso 1 de 2 | US-AUTH-04 |
| B05 | <img src="resources/Cap6/6.4.1-wireframes/B05.png" alt="Wireframe B05: Hoja Confirmando de la publicación" width="150"/> | Hoja Confirmando de la publicación: paso 2 de 2 | US-AUTH-04 |
| B06 | <img src="resources/Cap6/6.4.1-wireframes/B06.png" alt="Wireframe B06: Hoja Fallida de la publicación" width="150"/> | Hoja Fallida de la publicación, con Reintentar publicación y Reconectar billetera | US-AUTH-04 |
| B07 | <img src="resources/Cap6/6.4.1-wireframes/B07.png" alt="Wireframe B07: Tu solicitud está abierta" width="150"/> | Tu solicitud está abierta, con comprobante de la transacción | US-LEND-01, US-LEND-05 |
| B08 | <img src="resources/Cap6/6.4.1-wireframes/B08.png" alt="Wireframe B08: Lista Préstamos con chips de estado" width="150"/> | Lista Préstamos con chips de estado: Todos, Abierta, Pendiente, Pagado y En mora | US-LEND-05 |
| B09 | <img src="resources/Cap6/6.4.1-wireframes/B09.png" alt="Wireframe B09: Detalle del préstamo con progreso de cuotas" width="150"/> | Detalle del préstamo con progreso de cuotas, condiciones y lista de cuotas | US-LEND-05, US-LEND-06 |
| B10 | <img src="resources/Cap6/6.4.1-wireframes/B10.png" alt="Wireframe B10: Pagar cuota 3 de 4" width="150"/> | Pagar cuota 3 de 4: monto, saldo después del pago y aviso de que LatiFi nunca mueve el dinero | US-LEND-04, US-LEND-06 |
| B11 | <img src="resources/Cap6/6.4.1-wireframes/B11.png" alt="Wireframe B11: Cuota pagada" width="150"/> | Cuota pagada, con comprobante y acceso a Ver mi reputación | US-LEND-04, US-REP-01 |
| B12 | <img src="resources/Cap6/6.4.1-wireframes/B12.png" alt="Wireframe B12: Reputación" width="150"/> | Reputación: puntaje sobre 1000, contadores de pagos e historial con filtros por resultado | US-REP-01, US-REP-02 |
| B13 | <img src="resources/Cap6/6.4.1-wireframes/B13.png" alt="Wireframe B13: Reputación con la hoja Niveles abierta y los puntos que suma cada resultado" width="150"/> | Reputación con la hoja Niveles abierta y los puntos que suma cada resultado | US-REP-04 |
| B14 | <img src="resources/Cap6/6.4.1-wireframes/B14.png" alt="Wireframe B14: Perfil" width="150"/> | Perfil: datos personales, billetera, rol, idioma, moneda local y ayuda | US-IDEN-01, US-LEND-06 |
| B15 | <img src="resources/Cap6/6.4.1-wireframes/B15.png" alt="Wireframe B15: Hoja Obtener monedas de prueba" width="150"/> | Hoja Obtener monedas de prueba: 1,000 tUSD sin valor real | US-LEND-01 |
| C01 | <img src="resources/Cap6/6.4.1-wireframes/C01.png" alt="Wireframe C01: Primero agrega tus datos" width="150"/> | Primero agrega tus datos, aviso previo a pedir un préstamo con el perfil incompleto | US-IDEN-01 |
| C02 | <img src="resources/Cap6/6.4.1-wireframes/C02.png" alt="Wireframe C02: Tus datos" width="150"/> | Tus datos: nombre completo y teléfono o correo electrónico | US-IDEN-01 |
| C03 | <img src="resources/Cap6/6.4.1-wireframes/C03.png" alt="Wireframe C03: Lista Préstamos en estado vacío" width="150"/> | Lista Préstamos en estado vacío, con el botón Solicitar préstamo | US-LEND-05 |
| P01 | <img src="resources/Cap6/6.4.1-wireframes/P01.png" alt="Wireframe P01: Pagar cuota" width="150"/> | Pagar cuota, hoja Pendiente: paso 1 de 2 del pago | US-AUTH-04 |
| P02 | <img src="resources/Cap6/6.4.1-wireframes/P02.png" alt="Wireframe P02: Pagar cuota" width="150"/> | Pagar cuota, hoja Fallida, con Reintentar pago y Reconectar billetera | US-AUTH-04 |
| P03 | <img src="resources/Cap6/6.4.1-wireframes/P03.png" alt="Wireframe P03: Pagar cuota" width="150"/> | Pagar cuota, hoja Confirmando: paso 2 de 2 del pago | US-AUTH-04 |

##### Prestamista

| ID | Wireframe | Pantalla y estado | Historias |
|---|---|---|---|
| L01 | <img src="resources/Cap6/6.4.1-wireframes/L01.png" alt="Wireframe L01: Inicio del prestamista" width="150"/> | Inicio del prestamista: saldo, solicitudes abiertas, próximo pago que recibe y acceso a Ver solicitudes | US-LEND-02, US-LEND-06 |
| L02 | <img src="resources/Cap6/6.4.1-wireframes/L02.png" alt="Wireframe L02: Invertir" width="150"/> | Invertir: feed ordenado por reputación, con la reputación de cada solicitante y el botón Fondear | US-LEND-02, US-REP-03 |
| L03 | <img src="resources/Cap6/6.4.1-wireframes/L03.png" alt="Wireframe L03: Invertir con un filtro activo" width="150"/> | Invertir con un filtro activo: riesgo bajo y el contador de solicitudes | US-REP-03 |
| L04 | <img src="resources/Cap6/6.4.1-wireframes/L04.png" alt="Wireframe L04: Invertir sin resultados" width="150"/> | Invertir sin resultados, con el botón Limpiar filtros | US-REP-03 |
| L05 | <img src="resources/Cap6/6.4.1-wireframes/L05.png" alt="Wireframe L05: Hoja Ordenar solicitudes" width="150"/> | Hoja Ordenar solicitudes: reputación, tasa, plazo o más recientes | US-REP-03 |
| L06 | <img src="resources/Cap6/6.4.1-wireframes/L06.png" alt="Wireframe L06: Detalle de la solicitud con la reputación del prestatario y su historial reciente de pagos" width="150"/> | Detalle de la solicitud con la reputación del prestatario y su historial reciente de pagos | US-LEND-02, US-API-01 |
| L07 | <img src="resources/Cap6/6.4.1-wireframes/L07.png" alt="Wireframe L07: Detalle de la solicitud de un prestatario nuevo" width="150"/> | Detalle de la solicitud de un prestatario nuevo, sin historial de pagos | US-LEND-02, US-REP-02 |
| L08 | <img src="resources/Cap6/6.4.1-wireframes/L08.png" alt="Wireframe L08: Primero agrega tus datos" width="150"/> | Primero agrega tus datos, aviso antes de fondear con el perfil incompleto | US-IDEN-01 |
| L09 | <img src="resources/Cap6/6.4.1-wireframes/L09.png" alt="Wireframe L09: Confirmar fondeo" width="150"/> | Confirmar fondeo: monto, tasa, plazo, cuotas que recibirá y condiciones que quedan fijas | US-LEND-03, US-LEND-06 |
| L10 | <img src="resources/Cap6/6.4.1-wireframes/L10.png" alt="Wireframe L10: Confirmar fondeo" width="150"/> | Confirmar fondeo, hoja Pendiente: paso 1 de 2 | US-AUTH-04 |
| L11 | <img src="resources/Cap6/6.4.1-wireframes/L11.png" alt="Wireframe L11: Confirmar fondeo" width="150"/> | Confirmar fondeo, hoja Fallida: la solicitud ya no está abierta | US-AUTH-04 |
| L12 | <img src="resources/Cap6/6.4.1-wireframes/L12.png" alt="Wireframe L12: Solicitud fondeada" width="150"/> | Solicitud fondeada, con comprobante y acceso a Ver portafolio | US-LEND-03, US-LEND-05 |
| L13 | <img src="resources/Cap6/6.4.1-wireframes/L13.png" alt="Wireframe L13: Portafolio con total prestado" width="150"/> | Portafolio con total prestado, chips de estado y próximo vencimiento primero | US-LEND-05 |
| L14 | <img src="resources/Cap6/6.4.1-wireframes/L14.png" alt="Wireframe L14: Detalle de la inversión en estado Pendiente" width="150"/> | Detalle de la inversión en estado Pendiente, con cuotas recibidas y por pagar | US-LEND-05 |
| L15 | <img src="resources/Cap6/6.4.1-wireframes/L15.png" alt="Wireframe L15: Detalle de la inversión En mora" width="150"/> | Detalle de la inversión En mora, con la explicación del efecto en la reputación | US-LEND-05, US-REP-01 |
| L16 | <img src="resources/Cap6/6.4.1-wireframes/L16.png" alt="Wireframe L16: Tus datos del prestamista" width="150"/> | Tus datos del prestamista: nombre completo y teléfono o correo | US-IDEN-01 |
| L17 | <img src="resources/Cap6/6.4.1-wireframes/L17.png" alt="Wireframe L17: Confirmar fondeo" width="150"/> | Confirmar fondeo, hoja Confirmando: paso 2 de 2 | US-AUTH-04 |

**Cobertura.** Los wireframes cubren las historias US-AUTH-01 a US-AUTH-04, US-IDEN-01, US-LEND-01 a US-LEND-06, US-REP-01 a US-REP-04 y US-API-01. La escala de reputación que muestra B12 es de 0 a 1000 con cuatro niveles (Nuevo de 0 a 399, En construcción de 400 a 599, Confiable de 600 a 799 y Excelente de 800 a 1000). El Capítulo V define el puntaje de 0 a 100, y la aplicación lo presenta sobre 1000.

#### 6.4.2. Applications Wireflow Diagrams

Cada wireflow sigue el objetivo de un usuario concreto, de una persona concreta, y usa los wireframes de 6.4.1 como pasos. Cuando una pantalla cambia de estado, el diagrama añade un paso para ese estado. Los siete flujos cubren cuatro objetivos del prestatario y tres del prestamista, y cada uno cita las historias de 3.2 que cumple.

Cada nodo de pantalla lleva el identificador del wireframe de 6.4.1 y su título, por ejemplo `B02: Solicitar préstamo`. Los rombos son decisiones y los óvalos son acciones del usuario, y ninguno representa una pantalla. El identificador, no el color, dice qué wireframe corresponde a cada paso. Las hojas inferiores de estado de una transacción (pendiente, confirmando y fallida) tienen su propio identificador, porque cambian el estado de la pantalla sin cambiar de pantalla.

##### W-B1. Crear la billetera y entrar

**Objetivo del usuario:** Crear o conectar una billetera propia, entrar a LatiFi con ella y llegar al inicio del prestatario sin conocer términos de blockchain.

**Persona:** Prestatario no bancarizado (sección 2.3.1, construido a partir de la entrevista con Joseph Falcón).

```mermaid
flowchart TD
    A(["Prestatario abre la app"]) --> B["A01: Bienvenida, paso 1"]
    B --> C["A02: Bienvenida, paso 4"]
    C --> D["A03: Conecta tu billetera"]
    D --> E{"¿Tiene billetera?"}
    E -->|No| F["A04: Cómo obtener una billetera"]
    F --> D
    E -->|Sí| G["A05: Confirma que eres tú"]
    G --> H["A06: Pendiente de inicio de sesión"]
    H --> I["A07: Elegir rol"]
    I --> J["B01: Inicio del prestatario"]
```

**Explicación del flujo:** El prestatario abre la app y recorre la bienvenida en lenguaje sencillo, que explica en cuatro pasos qué hace LatiFi y aclara que la app nunca guarda su llave (A01 y A02). En Conecta tu billetera (A03) toca Conectar billetera. Si no tiene una, la hoja A04 le explica cómo conseguir una y le advierte que nadie en LatiFi le pedirá jamás la frase de recuperación. Con la billetera lista, la hoja A05 le pide firmar un mensaje corto que no mueve dinero y que solo prueba que la billetera es suya. La hoja A06 muestra el estado pendiente mientras el usuario abre su billetera y aprueba. Luego elige el rol de prestatario (A07) y llega al inicio (B01). La frase y la llave nunca salen de la billetera, y este informe no incluye ninguna de las dos.

**Historias:** US-AUTH-01, US-AUTH-02, US-AUTH-03, US-AUTH-04, TS-API-05

##### W-B2. Pedir un préstamo

**Objetivo del usuario:** Publicar una solicitud de préstamo con el monto, la tasa, el plazo y las cuotas que el prestatario elige, y ver que quedó abierta.

**Persona:** Prestatario no bancarizado (sección 2.3.1, construido a partir de la entrevista con Joseph Falcón).

```mermaid
flowchart TD
    A["B01: Inicio del prestatario"] --> B{"¿Perfil completo?"}
    B -->|No| C["C01: Primero agrega tus datos"]
    C --> D["C02: Tus datos"]
    D --> E["B02: Solicitar préstamo"]
    B -->|Sí| E
    E --> F["B03: Revisa tu solicitud"]
    F --> G["B04: Hoja Pendiente"]
    G --> H["B05: Hoja Confirmando"]
    H --> I{"¿Transacción confirmada?"}
    I -->|Falló| J["B06: Hoja Fallida"]
    J --> F
    I -->|Confirmada| K["B07: Tu solicitud está abierta"]
    K --> L["B08: Lista de préstamos"]
```

**Explicación del flujo:** Desde el inicio (B01), el prestatario toca Solicitar préstamo. Si su perfil está incompleto (US-IDEN-01), C01 le pide agregar sus datos y C02 recoge su nombre y su contacto. En B02 elige el monto con atajos, la tasa anual, el plazo y de 1 a 6 cuotas, con el equivalente en soles de cada monto (US-LEND-06). B03 repite el monto, la tasa, el plazo, la cuota y el total a devolver, y avisa que la billetera cobra una comisión de red. Al publicar, la hoja de estado recorre los estados de US-AUTH-04: pendiente (B04), confirmando (B05) y confirmada o fallida. Si falla (B06), el usuario reintenta la publicación o reconecta la billetera sin perder lo que escribió. Si se confirma, B07 muestra la solicitud como abierta con su comprobante, y el usuario la ve en la lista de préstamos (B08) con su chip de estado.

**Historias:** US-LEND-01, US-LEND-06, US-AUTH-04, US-IDEN-01

##### W-B3. Pagar una cuota

**Objetivo del usuario:** Pagar la próxima cuota de un préstamo vigente y recibir el comprobante.

**Persona:** Prestatario no bancarizado (sección 2.3.1, construido a partir de la entrevista con Joseph Falcón).

```mermaid
flowchart TD
    A["B08: Lista de préstamos"] --> B["B09: Detalle del préstamo"]
    B --> C["B10: Pagar cuota"]
    C --> D["P01: Hoja Pendiente"]
    D --> E["P03: Hoja Confirmando"]
    E --> F{"¿Transacción confirmada?"}
    F -->|Falló| G["P02: Hoja Fallida"]
    G --> C
    F -->|Confirmada| H["B11: Cuota pagada"]
    H --> I["B12: Reputación"]
```

**Explicación del flujo:** El prestatario abre la lista de préstamos (B08) y filtra por los chips de estado, que llevan ícono y texto. En el detalle (B09) ve el progreso de cuotas y la fecha de la próxima, con los montos en tUSD y en soles (US-LEND-06). Al tocar Pagar cuota llega a B10, que repite el monto, el saldo después del pago y el aviso de que LatiFi nunca mueve el dinero. La hoja de estado muestra pendiente (P01) y confirmando (P03). Si falla (P02), el usuario vuelve a B10 para reintentar. Si se confirma, B11 muestra la cuota pagada con su comprobante. La reputación se actualiza sola poco después (US-REP-01), y B12 es el punto de llegada.

**Historias:** US-LEND-04, US-LEND-05, US-LEND-06, US-AUTH-04, US-REP-01

##### W-B4. Revisar mi reputación

**Objetivo del usuario:** Entender de dónde sale su puntaje y revisar cada evento que lo compone.

**Persona:** Prestatario no bancarizado (sección 2.3.1, construido a partir de la entrevista con Joseph Falcón).

```mermaid
flowchart TD
    S(["Prestatario abre la pestaña Reputación"]) --> A["B12: Reputación"]
    A --> B(["Filtra por A tiempo, Tardío o Incumplido"])
    B --> A
    A --> C["B13: Hoja Niveles"]
    C --> A
```

**Explicación del flujo:** El prestatario abre Reputación (B12) y ve su puntaje sobre 1000, su nivel y los contadores de pagos a tiempo, tardíos e incumplidos. Debajo, el historial lista cada evento con los puntos que sumó o restó, y el usuario lo filtra por resultado. La hoja Niveles (B13) explica los rangos (Nuevo, En construcción, Confiable y Excelente) y cuánto suma cada resultado (US-REP-04). El historial viene de `GET /reputation/{address}/history` (US-API-01).

**Historias:** US-REP-01, US-REP-02, US-REP-04, US-API-01

##### W-L1. Encontrar una solicitud para fondear

**Objetivo del usuario:** Encontrar entre las solicitudes abiertas una que encaje con su riesgo, plazo y monto, y revisar la reputación del solicitante antes de decidir.

**Persona:** Prestamista con capital ocioso (sección 2.3.1, construido a partir de la entrevista con Renso Julca).

```mermaid
flowchart TD
    S(["Prestamista elige invertir"]) --> A["A07: Elegir rol"]
    A --> B["L01: Inicio del prestamista"]
    B --> C["L02: Invertir"]
    C --> D["L03: Filtros activos"]
    D --> E{"¿Hay resultados?"}
    E -->|No| F["L04: Sin resultados"]
    F --> C
    E -->|Sí| G["L06: Detalle de la solicitud"]
    C --> H["L05: Ordenar solicitudes"]
    H --> C
    G --> I(["Decide fondear: sigue W-L2"])
```

**Explicación del flujo:** El prestamista elige su rol (A07) y llega a su inicio (L01), donde toca Ver solicitudes. El feed Invertir (L02) muestra las solicitudes abiertas con la reputación de cada solicitante (US-LEND-02) y los montos en tUSD y en soles (US-LEND-06). Arriba hay chips de riesgo, plazo y monto (L03), y una hoja para ordenar por reputación, tasa, plazo o más recientes (L05, US-REP-03). Cada cambio de filtro actualiza el contador de resultados. Si ninguna solicitud cumple los filtros, L04 ofrece el botón Limpiar filtros. Con resultados, el prestamista abre el detalle (L06 o L07 si el prestatario es nuevo) y revisa su historial de pagos antes de decidir (US-API-01).

**Historias:** US-LEND-02, US-REP-03, US-API-01, US-LEND-06

##### W-L2. Fondear una solicitud

**Objetivo del usuario:** Fondear una solicitud conociendo las condiciones que quedan fijas y ver la inversión en su portafolio.

**Persona:** Prestamista con capital ocioso (sección 2.3.1, construido a partir de la entrevista con Renso Julca).

```mermaid
flowchart TD
    A["L06: Detalle de la solicitud"] --> B{"¿Perfil completo?"}
    B -->|No| C["L08: Primero agrega tus datos"]
    C --> D["L16: Tus datos"]
    D --> A
    B -->|Sí| E["L09: Confirmar fondeo"]
    E --> F["L10: Hoja Pendiente"]
    F --> G["L17: Hoja Confirmando"]
    G --> H{"¿Transacción confirmada?"}
    H -->|Falló| I["L11: Hoja Fallida"]
    I --> E
    H -->|Confirmada| J["L12: Solicitud fondeada"]
    J --> K["L13: Portafolio"]
```

**Explicación del flujo:** En el detalle de la solicitud (L06), el prestamista toca Fondear solicitud. Si su perfil está incompleto (US-IDEN-01), L08 y L16 le piden su nombre y su contacto y lo devuelven al detalle. Con el perfil completo, L09 repite el monto en tUSD y en soles (US-LEND-06), la tasa, el plazo y las cuotas que recibirá, y avisa que las condiciones quedan fijas al firmar. La hoja de estado recorre pendiente (L10), confirmando (L17) y confirmada o fallida. Si falla (L11, por ejemplo porque otra persona ya fondeó la solicitud), el usuario reintenta o reconecta la billetera. Si se confirma, L12 muestra la solicitud fondeada con su comprobante y la inversión aparece en el portafolio (L13) con el estado Pendiente.

**Historias:** US-LEND-03, US-AUTH-04, US-LEND-06, US-IDEN-01

##### W-L3. Seguir mi portafolio

**Objetivo del usuario:** Saber qué inversiones tiene, cuál vence primero y si cada una recibe sus cuotas.

**Persona:** Prestamista con capital ocioso (sección 2.3.1, construido a partir de la entrevista con Renso Julca).

```mermaid
flowchart TD
    S(["Prestamista abre Portafolio"]) --> A["L13: Portafolio"]
    A --> B(["Elige Todos, Pendiente, Pagado o En mora"])
    B --> A
    A --> C{"¿Estado de la inversión?"}
    C -->|Pendiente| D["L14: Detalle de la inversión"]
    C -->|En mora| E["L15: Detalle En mora"]
    D --> A
    E --> A
```

**Explicación del flujo:** El prestamista abre Portafolio (L13) y ve el total prestado y sus inversiones con el próximo vencimiento primero. Los chips Todos, Pendiente, Pagado y En mora filtran la lista, y cada chip lleva ícono y texto. Al abrir una inversión, el detalle muestra las cuotas recibidas y por pagar (L14). Si una cuota lleva más de 7 días de atraso, el detalle explica que el préstamo quedó marcado como incumplido y que la reputación del prestatario bajó (L15). El chip del portafolio refleja el estado sin que el usuario tenga que buscarlo.

**Historias:** US-LEND-05, US-REP-01

#### 6.4.3. Applications Mock-ups

Los mock-ups muestran el diseño final de LatiFi Wallet en alta fidelidad, con la paleta Navy 900 y Green 600, las fuentes Sora e Inter, los objetivos táctiles de 48 dp y los chips con ícono y texto que fija 6.1. Son 38 pantallas en español latino (es_419), capturadas de una compilación de la aplicación Android en un Pixel 9a, en modo Demo. En ese modo la billetera es simulada y los montos son tUSD de prueba con nombres ficticios, sin dinero real.

Cada mock-up responde a un wireframe de 6.4.1, y la tabla de cierre relaciona ambos. Los tres recorridos principales (solicitar un préstamo, fondear una solicitud y pagar una cuota) también se grabaron en video, y 6.5 los usa como prototipo.

##### Onboarding y conexión de la billetera

| ID | Mock-up | Descripción |
|---|---|---|
| M01 | <img src="resources/Cap6/6.4.3-mockups/es-01-onboarding-1.png" alt="Mock-up M01: Bienvenida, paso 1 de 4" width="150"/> | Bienvenida, paso 1 de 4: Pide un préstamo |
| M02 | <img src="resources/Cap6/6.4.3-mockups/es-02-onboarding-2.png" alt="Mock-up M02: Bienvenida, paso 2 de 4" width="150"/> | Bienvenida, paso 2 de 4: Invierte en personas de confianza |
| M03 | <img src="resources/Cap6/6.4.3-mockups/es-03-onboarding-3.png" alt="Mock-up M03: Bienvenida, paso 3 de 4" width="150"/> | Bienvenida, paso 3 de 4: Paga en cuotas |
| M04 | <img src="resources/Cap6/6.4.3-mockups/es-04-onboarding-4.png" alt="Mock-up M04: Bienvenida, paso 4 de 4" width="150"/> | Bienvenida, paso 4 de 4: Construye tu reputación |
| M05 | <img src="resources/Cap6/6.4.3-mockups/es-05-conectar.png" alt="Mock-up M05: Conecta tu billetera" width="150"/> | Conecta tu billetera |
| M06 | <img src="resources/Cap6/6.4.3-mockups/es-06-firma-billetera.png" alt="Mock-up M06: Hoja Confirma que eres tú para firmar el inicio de sesión" width="150"/> | Hoja Confirma que eres tú para firmar el inicio de sesión |
| M07 | <img src="resources/Cap6/6.4.3-mockups/es-07-elegir-rol.png" alt="Mock-up M07: Elegir rol sin selección" width="150"/> | Elegir rol sin selección |
| M08 | <img src="resources/Cap6/6.4.3-mockups/es-08-elegir-rol-seleccionado.png" alt="Mock-up M08: Elegir rol con Quiero pedir un préstamo seleccionado" width="150"/> | Elegir rol con Quiero pedir un préstamo seleccionado |

##### Prestatario: pedir un préstamo

| ID | Mock-up | Descripción |
|---|---|---|
| M09 | <img src="resources/Cap6/6.4.3-mockups/es-09-inicio-prestatario.png" alt="Mock-up M09: Inicio del prestatario" width="150"/> | Inicio del prestatario |
| M10 | <img src="resources/Cap6/6.4.3-mockups/es-10-tus-datos.png" alt="Mock-up M10: Tus datos, vacío" width="150"/> | Tus datos, vacío |
| M11 | <img src="resources/Cap6/6.4.3-mockups/es-11-tus-datos-llenos.png" alt="Mock-up M11: Tus datos, completo" width="150"/> | Tus datos, completo |
| M12 | <img src="resources/Cap6/6.4.3-mockups/es-12-solicitud-paso-1.png" alt="Mock-up M12: Solicitar préstamo, paso 1 de 2, con el monto lleno" width="150"/> | Solicitar préstamo, paso 1 de 2, con el monto lleno |
| M13 | <img src="resources/Cap6/6.4.3-mockups/es-13-solicitud-completa.png" alt="Mock-up M13: Solicitar préstamo con monto, tasa, plazo y cuotas completos" width="150"/> | Solicitar préstamo con monto, tasa, plazo y cuotas completos |
| M14 | <img src="resources/Cap6/6.4.3-mockups/es-14-revisar-solicitud.png" alt="Mock-up M14: Revisa tu solicitud, paso 2 de 2" width="150"/> | Revisa tu solicitud, paso 2 de 2 |
| M15 | <img src="resources/Cap6/6.4.3-mockups/es-15-publicando.png" alt="Mock-up M15: Publicando la solicitud" width="150"/> | Publicando la solicitud: hoja Confirmando |
| M16 | <img src="resources/Cap6/6.4.3-mockups/es-16-solicitud-publicada.png" alt="Mock-up M16: Solicitud publicada" width="150"/> | Solicitud publicada: hoja Confirmada |

##### Prestatario: seguimiento, reputación y perfil

| ID | Mock-up | Descripción |
|---|---|---|
| M17 | <img src="resources/Cap6/6.4.3-mockups/es-17-prestamos.png" alt="Mock-up M17: Lista Préstamos con chips de estado" width="150"/> | Lista Préstamos con chips de estado |
| M18 | <img src="resources/Cap6/6.4.3-mockups/es-18-detalle-prestamo.png" alt="Mock-up M18: Detalle del préstamo" width="150"/> | Detalle del préstamo |
| M19 | <img src="resources/Cap6/6.4.3-mockups/es-19-reputacion.png" alt="Mock-up M19: Reputación" width="150"/> | Reputación |
| M20 | <img src="resources/Cap6/6.4.3-mockups/es-20-reputacion-niveles.png" alt="Mock-up M20: Reputación con la hoja Niveles abierta" width="150"/> | Reputación con la hoja Niveles abierta |
| M21 | <img src="resources/Cap6/6.4.3-mockups/es-21-perfil.png" alt="Mock-up M21: Perfil, parte 1" width="150"/> | Perfil, parte 1 |
| M22 | <img src="resources/Cap6/6.4.3-mockups/es-22-perfil-2.png" alt="Mock-up M22: Perfil, parte 2, con idioma y moneda local" width="150"/> | Perfil, parte 2, con idioma y moneda local |
| M23 | <img src="resources/Cap6/6.4.3-mockups/es-23-monedas.png" alt="Mock-up M23: Hoja Obtener monedas de prueba" width="150"/> | Hoja Obtener monedas de prueba |

##### Prestamista

| ID | Mock-up | Descripción |
|---|---|---|
| M24 | <img src="resources/Cap6/6.4.3-mockups/es-24-inicio-prestamista.png" alt="Mock-up M24: Inicio del prestamista" width="150"/> | Inicio del prestamista |
| M25 | <img src="resources/Cap6/6.4.3-mockups/es-25-solicitudes.png" alt="Mock-up M25: Invertir" width="150"/> | Invertir: solicitudes abiertas |
| M26 | <img src="resources/Cap6/6.4.3-mockups/es-26-filtros.png" alt="Mock-up M26: Invertir con los filtros desplegados" width="150"/> | Invertir con los filtros desplegados |
| M27 | <img src="resources/Cap6/6.4.3-mockups/es-27-detalle-solicitud.png" alt="Mock-up M27: Detalle de la solicitud" width="150"/> | Detalle de la solicitud |
| M28 | <img src="resources/Cap6/6.4.3-mockups/es-28-detalle-solicitud-2.png" alt="Mock-up M28: Detalle de la solicitud con el historial de pagos" width="150"/> | Detalle de la solicitud con el historial de pagos |
| M29 | <img src="resources/Cap6/6.4.3-mockups/es-29-confirmar-fondeo.png" alt="Mock-up M29: Confirmar fondeo" width="150"/> | Confirmar fondeo |
| M30 | <img src="resources/Cap6/6.4.3-mockups/es-30-fondeo-enviando.png" alt="Mock-up M30: Hoja Confirmando del fondeo" width="150"/> | Hoja Confirmando del fondeo |
| M31 | <img src="resources/Cap6/6.4.3-mockups/es-31-fondeo-paso-1.png" alt="Mock-up M31: Hoja Confirmada del fondeo, paso 1 de 2" width="150"/> | Hoja Confirmada del fondeo, paso 1 de 2 |
| M32 | <img src="resources/Cap6/6.4.3-mockups/es-32-fondeo-listo.png" alt="Mock-up M32: Solicitud fondeada" width="150"/> | Solicitud fondeada |
| M33 | <img src="resources/Cap6/6.4.3-mockups/es-33-portafolio.png" alt="Mock-up M33: Portafolio" width="150"/> | Portafolio |
| M34 | <img src="resources/Cap6/6.4.3-mockups/es-34-detalle-inversion.png" alt="Mock-up M34: Detalle de la inversión" width="150"/> | Detalle de la inversión |

##### Pago de una cuota y reputación final

| ID | Mock-up | Descripción |
|---|---|---|
| M35 | <img src="resources/Cap6/6.4.3-mockups/es-35-pagar-cuota.png" alt="Mock-up M35: Pagar cuota 2 de 3" width="150"/> | Pagar cuota 2 de 3 |
| M36 | <img src="resources/Cap6/6.4.3-mockups/es-36-pago-paso-1.png" alt="Mock-up M36: Hoja del pago, paso 1 de 2" width="150"/> | Hoja del pago, paso 1 de 2 |
| M37 | <img src="resources/Cap6/6.4.3-mockups/es-37-pago-listo.png" alt="Mock-up M37: Cuota pagada" width="150"/> | Cuota pagada |
| M38 | <img src="resources/Cap6/6.4.3-mockups/es-38-reputacion-final.png" alt="Mock-up M38: Reputación después del pago" width="150"/> | Reputación después del pago |

##### Del wireframe al mock-up

| Pantalla | Wireframes de 6.4.1 | Mock-ups de 6.4.3 |
|---|---|---|
| Bienvenida | A01, A02 | M01 a M04 |
| Conectar billetera y firma | A03 a A06 | M05, M06 |
| Elegir rol | A07 | M07, M08 |
| Inicio del prestatario | B01 | M09 |
| Perfil ligero | C01, C02, L08, L16 | M10, M11 |
| Solicitar préstamo | B02, B03 | M12 a M14 |
| Estado de la transacción | B04 a B06, P01 a P03, L10, L11, L17 | M15, M16, M30, M31, M36, M37 |
| Solicitud abierta | B07 | M16 |
| Préstamos y detalle | B08, B09, C03 | M17, M18 |
| Pagar cuota | B10, B11 | M35, M37 |
| Reputación | B12, B13 | M19, M20, M38 |
| Perfil y monedas de prueba | B14, B15 | M21 a M23 |
| Inicio del prestamista | L01 | M24 |
| Invertir y filtros | L02 a L05 | M25, M26 |
| Detalle de la solicitud | L06, L07 | M27, M28 |
| Confirmar fondeo | L09, L12 | M29, M32 |
| Portafolio e inversión | L13 a L15 | M33, M34 |

Los wireframes de error (B06, P02 y L11) y los de estado En mora (L15) no tienen mock-up porque la demostración en modo Demo no recorre esos estados. Los mock-ups de esos estados quedan para la versión final.

#### 6.4.4. Applications User Flow Diagrams

Esta sección presenta los User Flows de la aplicación móvil LatiFi Wallet para los user goals principales de los dos User Personas: el prestatario no bancarizado (Joseph) y el prestamista con capital ocioso (Renso). Los flujos se derivan de los Wireflows y recorren las pantallas implementadas en la aplicación, con la ruta esperada (happy path) y las rutas alternativas (unhappy paths).

En los diagramas, los nodos en verde corresponden al happy path, los nodos en naranja a las rutas alternativas y los rombos azules a las decisiones o condiciones del flujo. Toda transacción en la blockchain pasa por la hoja de estado de transacción, que muestra los estados pendiente, confirmando, confirmada y fallida (US-AUTH-04). Cuando una transacción falla, la aplicación ofrece la acción que resuelve el motivo:

| Motivo de la falla | Acción que ofrece la aplicación |
|---|---|
| El usuario rechaza la firma en su billetera | Reintentar |
| La sesión de la billetera expiró o no respondió a tiempo | Reconectar la billetera |
| No hay saldo de POL para la comisión de red | Copiar la dirección de la billetera para recibir POL de prueba |
| No hay saldo suficiente de la stablecoin de prueba | Obtener monedas de prueba |
| El contrato revirtió la transacción | Reintentar |
| La solicitud ya no está abierta (otro prestamista la fondeó) | Volver a las solicitudes |
| Error de red | Reintentar |

##### User Flow 1: Conectar la billetera e ingresar por primera vez

**User goal:** Como prestatario no bancarizado (Joseph), quiero entender cómo funciona LatiFi y conectar mi billetera de forma segura, para empezar a usar la aplicación sin entregar mis llaves a nadie.

<div align="center">
  <img src="resources/Cap6/6.4.4-user-flow-1.png" alt="User Flow 1: Conectar la billetera e ingresar por primera vez" width="60%"/>
</div>

**Explicación de los flujos y condiciones:** el usuario conoce el modelo P2P antes de conectar su billetera (US-AUTH-03). La conexión se realiza con Reown AppKit y el inicio de sesión consiste en firmar un mensaje que no genera ninguna transacción ni costo (US-AUTH-01, TS-API-05). La aplicación nunca recibe la llave privada (US-AUTH-02). Si el usuario no tiene una billetera, la hoja de ayuda le explica cómo obtenerla. Si rechaza la firma, puede reintentar, y si la billetera no responde a tiempo, la aplicación le propone reconectarla.

| Onboarding | Vinculación de billetera | Selección de rol |
|---|---|---|
| <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1791516018/Captura_de_pantalla_2026-10-08_a_la_s_10.19.48_p._m._nryhpc.png" alt="Onboarding" width="180"/> | <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1791516334/Captura_de_pantalla_2026-10-08_a_la_s_10.25.29_p._m._wcqeoe.png" alt="Vinculación de billetera" width="180"/> | <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1791516356/Captura_de_pantalla_2026-10-08_a_la_s_10.25.43_p._m._gpkpo0.png" alt="Selección de rol" width="180"/> |

##### User Flow 2: Solicitar un microcrédito

**User goal:** Como prestatario no bancarizado (Joseph), quiero publicar una solicitud de microcrédito con un monto y un plazo que pueda pagar, para conseguir capital de trabajo sin colateral.

<div align="center">
  <img src="resources/Cap6/6.4.4-user-flow-2.png" alt="User Flow 2: Solicitar un microcrédito" width="60%"/>
</div>

**Explicación de los flujos y condiciones:** el prestatario configura su solicitud y ve el costo total y cada cuota en stablecoin y en su moneda local antes de confirmar (US-LEND-01, US-LEND-06). Antes de publicar, la aplicación exige el perfil ligero (US-IDEN-01); si no existe, lo solicita y luego regresa al resumen. La solicitud queda registrada como un evento en el smart contract `LoanBook`. Si la transacción falla, la hoja de estado muestra el motivo y la acción que lo resuelve.

| Inicio del prestatario | Configurar solicitud | Proyección de cuotas |
|---|---|---|
| <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1791516109/Captura_de_pantalla_2026-10-08_a_la_s_10.21.36_p._m._whhzpb.png" alt="Inicio del prestatario" width="180"/> | <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1791516188/Captura_de_pantalla_2026-10-08_a_la_s_10.22.59_p._m._pjazye.png" alt="Configurar solicitud" width="180"/> | <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1791516208/Captura_de_pantalla_2026-10-08_a_la_s_10.23.23_p._m._pfht3q.png" alt="Proyección de cuotas" width="180"/> |

##### User Flow 3: Pagar una cuota

**User goal:** Como prestatario no bancarizado (Joseph), quiero pagar la cuota de mi préstamo desde la aplicación, para cumplir a tiempo y mejorar mi reputación.

<div align="center">
  <img src="resources/Cap6/6.4.4-user-flow-3.png" alt="User Flow 3: Pagar una cuota" width="60%"/>
</div>

**Explicación de los flujos y condiciones:** el prestatario paga cada cuota mediante el smart contract (US-LEND-04). La aplicación solicita la aprobación del monto exacto de la cuota y nunca una aprobación ilimitada de tokens. Después de la confirmación, LatiFi API indexa el evento `LoanRepaid` y recalcula la reputación (US-REP-01). Mientras eso ocurre, la aplicación espera y luego muestra el préstamo y el puntaje actualizados. Si falta saldo, la aplicación ofrece obtener monedas de prueba; si la sesión expiró, propone reconectar la billetera.

| Reputación on-chain | Pasaporte y nivel |
|---|---|
| <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1791516235/Captura_de_pantalla_2026-10-08_a_la_s_10.23.42_p._m._hoflo1.png" alt="Reputación on-chain" width="180"/> | <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1791516238/Captura_de_pantalla_2026-10-08_a_la_s_10.23.53_p._m._et2e5b.png" alt="Pasaporte y nivel" width="180"/> |

##### User Flow 4: Fondear una solicitud

**User goal:** Como prestamista con capital ocioso (Renso), quiero encontrar una solicitud con buena reputación y fondearla, para obtener rentabilidad con un riesgo que puedo evaluar.

<div align="center">
  <img src="resources/Cap6/6.4.4-user-flow-4.png" alt="User Flow 4: Fondear una solicitud" width="60%"/>
</div>

**Explicación de los flujos y condiciones:** el prestamista explora el feed ordenado por reputación (US-LEND-02, US-REP-03) y revisa el historial de pagos del solicitante antes de decidir, que es la condición que planteó en la entrevista. El fondeo transfiere los fondos directamente de su billetera a la del prestatario mediante el smart contract, sin que LatiFi los custodie (US-LEND-03). Si otro prestamista fondeó la solicitud antes, la transacción no procede y la aplicación lo devuelve al feed. Si el feed no tiene resultados con los filtros elegidos, se ofrece limpiarlos.

### 6.5. Applications Prototyping

El prototipo de LatiFi Wallet simula la interacción y la navegación de la aplicación móvil siguiendo los paths definidos en los User Flow Diagrams (6.4.4). Las decisiones de interacción se tomaron con los siguientes criterios:

- **Navegación por rol.** De acuerdo con el sistema de navegación (6.2.5), después de elegir su rol el usuario accede a una barra de navegación inferior con cuatro destinos. El prestatario ve Inicio, Préstamos, Reputación y Perfil, y el prestamista ve Inicio, Invertir, Portafolio y Perfil. Así, cada rol encuentra en un toque las tareas de su user goal, sin opciones que no le corresponden.
- **Una tarea por pantalla.** Solicitar un préstamo, pagar una cuota y fondear una solicitud son pantallas dedicadas que se abren desde el detalle del préstamo o de la solicitud. El usuario siempre ve el monto, el plazo y el equivalente en moneda local antes de confirmar, en línea con el principio de claridad de las guías de estilo (6.1).
- **Hojas inferiores para lo que interrumpe el flujo.** El inicio de sesión con la billetera, el estado de una transacción, la obtención de monedas de prueba y la ayuda para conseguir una billetera se muestran como hojas inferiores (bottom sheets). El usuario no pierde la pantalla en la que estaba y vuelve a ella al cerrar la hoja.
- **Estados explícitos y acciones de recuperación.** Toda transacción muestra los estados pendiente, confirmando, confirmada y fallida. Cuando algo falla, el prototipo ofrece la acción que lo resuelve (reintentar, reconectar la billetera u obtener monedas de prueba), en lugar de un mensaje genérico.
- **Filtros por chips.** En el feed del prestamista, los filtros de riesgo, plazo y monto son chips de un toque con un contador de resultados, según el sistema de búsqueda definido (6.2.3).
- **Lenguaje simple e inclusión.** Las etiquetas evitan la jerga cripto según el sistema de etiquetado (6.2.2), los botones nombran la acción que realizan, y la interfaz admite texto ampliado y el cambio de idioma entre español e inglés.

##### Prototipo: LatiFi Wallet (aplicación móvil)

El prototipo recorre los cuatro user flows principales:

| User flow | Rol | Pantallas que recorre |
|---|---|---|
| Conectar la billetera e ingresar por primera vez | Prestatario | Onboarding, ¿Cómo funciona?, Conectar billetera, hoja de inicio de sesión, Elegir rol |
| Solicitar un microcrédito | Prestatario | Inicio, Solicitar préstamo, Resumen, Formulario de perfil, hoja de estado de transacción, Detalle del préstamo |
| Pagar una cuota | Prestatario | Mis préstamos, Detalle del préstamo, Pagar cuota, hoja de estado de transacción, Reputación |
| Fondear una solicitud | Prestamista | Invertir, Detalle de la solicitud, Confirmar fondeo, hoja de estado de transacción, Portafolio |

El prototipo es la propia aplicación Android compilada en modo Demo, no una maqueta aparte. La billetera es simulada y los datos son de ejemplo (tUSD de prueba y nombres ficticios), de modo que cada pantalla de 6.4.3 responde al toque como lo hará la versión final. Cada recorrido principal tiene un video sin audio, grabado a 1080 x 2294 px.

| Video | User flow | Pantallas que recorre | Duración |
|---|---|---|---|
| Prestatario solicita un préstamo | User Flow 2 | M09 a M16 (6.4.3) | 01:53 |
| Prestamista fondea una solicitud | User Flow 4 | M24 a M34 (6.4.3) | 01:22 |
| Prestatario paga una cuota y ve su reputación | User Flow 3 | M35 a M38 (6.4.3) | 01:02 |

| Prestatario solicita un préstamo | Prestamista fondea una solicitud | Prestatario paga una cuota |
|---|---|---|
| <img src="resources/Cap6/6.5-prototype/prototipo-1.png" alt="Cuadro del video del prototipo: el prestatario solicita un préstamo" width="180"/> | <img src="resources/Cap6/6.5-prototype/prototipo-2.png" alt="Cuadro del video del prototipo: el prestamista fondea una solicitud" width="180"/> | <img src="resources/Cap6/6.5-prototype/prototipo-3.png" alt="Cuadro del video del prototipo: el prestatario paga una cuota" width="180"/> |

| Elemento | Detalle |
|---|---|
| Herramienta | Aplicación `latifi-android` en modo Demo, compilación debug sobre un Pixel 9a |
| Videos en Microsoft Stream | _[URL de cada video: Juan Angulo los sube a Stream]_ |

El User Flow 1 (conectar la billetera) no tiene video propio, porque en modo Demo la billetera simulada omite la firma real. Lo cubren las capturas M01 a M08.

## Capítulo VII: Product Implementation, Validation & Deployment

En este capítulo el equipo explica y evidencia el proceso de implementación, pruebas, despliegue y validación de LatiFi. La solución se compone de cuatro productos digitales, cada uno en su propio repositorio de GitHub: la landing page (HTML5, CSS3 y JavaScript), los smart contracts (Solidity sobre Polygon Amoy), LatiFi API (Spring Boot, con su indexador de eventos on-chain) y la aplicación móvil LatiFi Wallet (Kotlin con Jetpack Compose para Android).

El proceso core del negocio, el ciclo del microcrédito (solicitud, fondeo, pago en cuotas e incumplimiento), se ejecuta en el smart contract `LoanBook`. LatiFi API soporta los procesos de autenticación por firma de billetera, perfil ligero, reputación híbrida y conversión a moneda local, y la aplicación móvil integra ambos para los segmentos prestatario y prestamista.
### 7.1. Software Configuration Management

El equipo mantiene la consistencia de los cuatro productos durante el ciclo de vida aplicando las mismas convenciones en todos los repositorios: GitFlow como modelo de ramas, Conventional Commits para los mensajes, Semantic Versioning para los releases y dos verificaciones automáticas en GitHub Actions (`ci` y `commit-lint`) que deben pasar antes de integrar un pull request. Cada repositorio documenta estas reglas en su archivo `CONTRIBUTING.md`.
#### 7.1.1. Software Development Environment Configuration

Para colaborar en el ciclo de vida de LatiFi, los integrantes del equipo utilizan los siguientes productos de software, agrupados por tipo de actividad. Para los productos SaaS se indica la ruta de referencia, y para los que se ejecutan en el computador de cada integrante, la ruta de descarga. Las versiones corresponden a las fijadas en los repositorios.

**Project Management**

| Producto              | Propósito de uso en el proyecto                                                                                             | Ruta de referencia / descarga |
|-----------------------|-----------------------------------------------------------------------------------------------------------------------------|---|
| Trello                     | Gestión del backlog y de los sprints. Cada pull request se vincula con su issue mediante la clave del proyecto LatiFi en Trello. | https://trello.com/b/YDJ16JNs/latifi |
| GitHub (Organization) | Alojamiento de los repositorios del equipo, revisión de cambios mediante pull requests y analíticos de colaboración.        | https://github.com/Arquitectura-de-Softwares-Emergentes |

**Requirements Management**

| Producto          | Propósito de uso en el proyecto | Ruta de referencia / descarga |
|-------------------|---|---|
| Trello            | Registro de las épicas, user stories y technical stories del Product Backlog. | https://trello.com/ |
| UXPressia         | Elaboración de los User Personas y Empathy Maps a partir de las entrevistas. | https://uxpressia.com |
| Miro / LucidChart | Sesiones de EventStorming y modelado de escenarios As-Is y To-Be. | https://miro.com / https://www.lucidchart.com |

**Product UX/UI Design**

| Producto | Propósito de uso en el proyecto | Ruta de referencia / descarga |
|---|---|---|
| Jetpack Compose y Android Studio | Implementación del diseño final de la aplicación: mock-ups de 6.4.3 y prototipo en modo Demo de 6.5, grabados en un Pixel 9a. | https://developer.android.com/compose |
| _[Herramienta de los wireframes de 6.4.1: Anaely Burga confirma el nombre]_ | Diseño de los 45 wireframes de la aplicación móvil. | _[URL]_ |
| Google Fonts | Fuentes Sora e Inter del sistema de diseño. | https://fonts.google.com |
| Material Symbols | Íconos de la aplicación móvil. | https://fonts.google.com/icons |

**Software Development**

| Producto | Versión | Propósito de uso en el proyecto | Ruta de referencia / descarga |
|---|---|---|---|
| Git | n/a | Control de versiones local. | https://git-scm.com/downloads |
| JDK (Java Development Kit) | 21 | Compilación y ejecución de LatiFi API y de la aplicación Android. | https://adoptium.net |
| Android Studio / Android SDK | compileSdk 37, minSdk 26 | Desarrollo y emulación de la aplicación móvil nativa. | https://developer.android.com/studio |
| Kotlin + Jetpack Compose | Kotlin 2.4.21, Compose BOM 2026.09.00 | Lenguaje y toolkit de interfaz de la aplicación móvil. | https://kotlinlang.org / https://developer.android.com/compose |
| Gradle (wrapper) | 9.6.1 | Construcción de la aplicación Android. | https://gradle.org |
| Reown AppKit | 1.6.17 | Conexión no custodial de la aplicación con la billetera del usuario (WalletConnect). | https://reown.com |
| Spring Boot | 3.5.16 | Framework de LatiFi API. | https://spring.io/projects/spring-boot |
| Apache Maven (wrapper) | n/a | Construcción de LatiFi API. | https://maven.apache.org |
| web3j | 5.0.2 | Lectura de eventos de la blockchain y verificación de firmas en LatiFi API. | https://docs.web3j.io |
| PostgreSQL | 16 | Base de datos de LatiFi API. | https://www.postgresql.org/download |
| Docker | n/a | Ejecución de PostgreSQL en las pruebas mediante Testcontainers. | https://www.docker.com/products/docker-desktop |
| Foundry (forge, cast, anvil) | n/a | Compilación, pruebas y despliegue de los smart contracts. | https://getfoundry.sh |
| Solidity | 0.8.35 | Lenguaje de los smart contracts. | https://soliditylang.org |
| OpenZeppelin Contracts | 5.7.0 | Librería base de seguridad para los smart contracts. | https://www.openzeppelin.com/solidity-contracts |
| Polygon Amoy | chain id 80002 | Red de pruebas donde se despliegan los smart contracts. | https://polygon.technology |
| Node.js | 22 | Herramientas de verificación de la landing page. | https://nodejs.org |
| Visual Studio Code | n/a | Edición de la landing page, los smart contracts y el informe en Markdown. | https://code.visualstudio.com |

**Software Testing**

| Producto | Versión | Propósito de uso en el proyecto | Ruta de referencia / descarga |
|---|---|---|---|
| JUnit 5 | n/a | Unit tests de LatiFi API y de la aplicación Android. | https://junit.org/junit5 |
| Cucumber | 7.23.0 | Acceptance tests en Gherkin (archivos `.feature`) de LatiFi API. | https://cucumber.io |
| Testcontainers | n/a | Integration tests de LatiFi API con PostgreSQL real en contenedores. | https://testcontainers.com |
| Foundry (forge test) | n/a | Unit, fuzz, invariant y reentrancy tests de los smart contracts. | https://getfoundry.sh |
| Compose UI Test | n/a | Pruebas instrumentadas de las pantallas en un emulador Android. | https://developer.android.com/develop/ui/compose/testing |
| Lighthouse | 13.6.0 | Auditoría de accesibilidad y SEO de la landing page. | https://developer.chrome.com/docs/lighthouse |
| Nu HTML Checker | n/a | Validación del HTML de la landing page. | https://validator.github.io/validator |

**Software Deployment**

| Producto | Propósito de uso en el proyecto | Ruta de referencia / descarga |
|---|---|---|
| GitHub Actions | Integración continua (`ci` y `commit-lint`) de los cuatro repositorios y generación del APK. | https://github.com/features/actions |
| GitHub Pages | Publicación de la landing page en cada release integrado en `main`. | https://pages.github.com |
| Dokploy (VPS del equipo) | Despliegue de LatiFi API y su base de datos PostgreSQL (ver ADR-0006). | https://dokploy.com |
| Sourcify / Polygonscan (Amoy) | Verificación pública del código y las direcciones de los smart contracts desplegados. | https://sourcify.dev / https://amoy.polygonscan.com |

**Software Documentation**

| Producto | Propósito de uso en el proyecto | Ruta de referencia / descarga |
|---|---|---|
| GitHub (Markdown) | Redacción del informe del proyecto, README de cada repositorio y registros de decisiones de arquitectura (ADR). | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-report |
| OpenAPI + springdoc (Swagger UI) | Documentación de los endpoints de LatiFi API. | https://springdoc.org |
| Mermaid | Diagramas C4 y de clases del informe, renderizados por GitHub. | https://mermaid.js.org |
| Microsoft Stream | Publicación de los videos de exposiciones, entrevistas y prototipos. | https://www.microsoft.com/microsoft-365/microsoft-stream |

#### 7.1.2. Source Code Management

El equipo utiliza GitHub como plataforma y sistema de control de versiones. Cada producto digital tiene su propio repositorio dentro de la organización **Arquitectura-de-Softwares-Emergentes**, y el informe del proyecto se mantiene en un repositorio adicional.

**Repositorios por producto digital**

| Producto digital | Repositorio en GitHub | Contenido |
|---|---|---|
| Landing Page | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-landing | Sitio estático bilingüe (en_US / es_419), scripts de verificación y workflow de publicación en GitHub Pages. |
| Smart Contracts | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-contracts | Contratos `LoanBook` y `MockStablecoin` en Solidity, pruebas con Foundry, ABI y registro del despliegue en Polygon Amoy. |
| Web Services (LatiFi API) | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-api | Proyecto Spring Boot, contrato OpenAPI y pruebas, incluidos los archivos `.feature` en `src/test/resources/features`. |
| Mobile Application (LatiFi Wallet) | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-android | Aplicación nativa en Kotlin con Jetpack Compose, pruebas unitarias e instrumentadas. |
| Project Report | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-report | Informe del proyecto en Markdown y registros de decisiones de arquitectura (ADR). |

**GitFlow**

El equipo implementa GitFlow según el modelo de Vincent Driessen ("A successful Git branching model"). La rama `main` contiene solo versiones liberadas y la rama `develop` concentra la integración diaria. El trabajo se realiza en ramas de soporte que nacen de `develop` o de `main` según su tipo:

| Rama | Propósito | Nace de | Se integra en | Método de merge | Convención de nombre |
|---|---|---|---|---|---|
| `main` | Versiones liberadas. Cada commit es un release o un hotfix. | n/a | n/a | n/a | `main` |
| `develop` | Integración del trabajo diario. | `main` | n/a | n/a | `develop` |
| Feature branches | Desarrollo de una funcionalidad. | `develop` | `develop` | Squash | `feature/<slug>` |
| Release branches | Preparación de una versión. | `develop` | `main` | Merge commit | `release/<versión>` |
| Hotfix branches | Corrección urgente de una versión liberada. | `main` | `main` y luego `develop` | Merge commit | `hotfix/<versión>` |

El slug va en minúsculas y solo admite letras, dígitos, puntos, guiones bajos y guiones. Ejemplos válidos son `feature/loan-request-form`, `feature/amoy-smoke-workflow`, `release/0.2.0` y `hotfix/1.0.1`; nombres como `fix/typo` o `Feature/Login` son rechazados. La verificación `commit-lint` aplica estas reglas en cada pull request: hacia `develop` solo se aceptan ramas `feature/*`, `release/*` o `hotfix/*`, y hacia `main` solo `release/*` o `hotfix/*`.

**Semantic Versioning**

Los releases siguen Semantic Versioning 2.0.0 con el formato `MAJOR.MINOR.PATCH`. Después de integrar un release o un hotfix en `main`, se crea un tag anotado con el formato `vMAJOR.MINOR.PATCH`. Mientras el producto no tenga su primera versión pública, las versiones se mantienen en `0.y.z`.

| Repositorio | Tags publicados |
|---|---|
| latifi-landing | `v0.1.0`, `v0.2.0` |
| latifi-contracts | `v0.1.0`, `v0.2.0` |
| latifi-api | `v0.1.0` |
| latifi-android | `v0.1.0` |

**Conventional Commits**

Cada mensaje de commit y cada título de pull request sigue el formato de Conventional Commits:

```
type(scope): short description
```

El scope es opcional y va en minúsculas, un signo de exclamación antes de los dos puntos marca un cambio incompatible, y el asunto no supera los 100 caracteres. Como los feature branches se integran por squash, el título del pull request se convierte en el mensaje del commit en `develop`.

| Tipo | Uso |
|---|---|
| `feat` | Nueva funcionalidad |
| `fix` | Corrección de un error |
| `docs` | Documentación |
| `style` | Formato del código sin cambio de comportamiento |
| `refactor` | Reestructuración del código sin cambio de comportamiento |
| `perf` | Mejora de rendimiento |
| `test` | Pruebas |
| `build` | Sistema de construcción o dependencias |
| `ci` | Integración continua |
| `chore` | Tareas de mantenimiento |
| `revert` | Reversión de un commit |

Ejemplos del repositorio: `feat(loans): add the borrower loan list, loan details and local currency values`, `test: add reentrancy, fuzz and invariant suites for the loan book` y `fix: apply the phase 5 code review findings`.

#### 7.1.3. Source Code Style Guide & Conventions

El equipo aplica nomenclatura en inglés para todos los elementos del código (paquetes, clases, métodos, variables, eventos, endpoints y escenarios de prueba) en todos los lenguajes de la solución. Las convenciones se verifican de forma automática en la integración continua de cada repositorio.

| Lenguaje / tecnología | Guía de referencia | Convenciones aplicadas | Verificación automática |
|---|---|---|---|
| Kotlin (Android) | [Kotlin Coding Conventions](https://kotlinlang.org/docs/coding-conventions.html) y [Android Kotlin Style Guide](https://developer.android.com/kotlin/style-guide) | Estilo oficial de Kotlin (`kotlin.code.style=official`), clases y composables en UpperCamelCase, funciones y variables en lowerCamelCase, paquete base `com.latifi.wallet` organizado por funcionalidad (`ui/home`, `ui/feed`, `ui/loans`, `data`, `core`). | Android Lint en el job `ci` (falla ante errores). |
| Java (LatiFi API) | [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html) | Formato con google-java-format 1.36.1, paquete base `com.latifi.api` organizado por bounded context (`identity`, `ledger`, `reputation`, `exchangerate`) y por capas (`domain`, `application`, `interfaces`, `infrastructure`). | Spotless en `./mvnw verify`. |
| Solidity (Smart Contracts) | [Solidity Style Guide](https://docs.soliditylang.org/en/latest/style-guide.html) | Contratos y eventos en UpperCamelCase (`LoanBook`, `LoanRequested`), funciones en lowerCamelCase, compilador fijado en 0.8.35, errores personalizados en lugar de mensajes de texto, `nonReentrant` en toda función que mueve fondos, líneas de máximo 100 caracteres. | `forge fmt --check`, `forge lint` y reglas propias del repositorio (`check-lint.sh`). |
| HTML5 / CSS3 / JavaScript (Landing Page) | [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html) y [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html) | HTML semántico con atributo `lang`, skip link, un solo landmark `main` y alternativas `hreflang` en cada página; sin scripts, estilos ni eventos en línea; contraste según WCAG 2.1 AA. | Nu HTML Checker, guardas de i18n/a11y y de CSP, verificación de contraste y Lighthouse (Accessibility y SEO de 90 o más). |
| OpenAPI | [OpenAPI Specification 3.0.3](https://spec.openapis.org/oas/v3.0.3) | Rutas bajo `/api/v1` en minúsculas, `operationId` en lowerCamelCase (`issueChallenge`, `getReputation`, `listLoans`) y códigos de error en UPPER_SNAKE_CASE (`INVALID_ADDRESS`). | Pruebas que comparan el código con el contrato `openapi/latifi-api.v0.yaml`. |
| Gherkin (archivos `.feature`) | [Gherkin Conventions for Readable Specifications](https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/) y [Gherkin Reference](https://cucumber.io/docs/gherkin/reference/) | Un archivo `.feature` por funcionalidad con una descripción breve, escenarios redactados como comportamiento observable, pasos `Given`/`When`/`Then` en tercera persona y tags `@op-<operationId>` que vinculan cada escenario con la operación del contrato OpenAPI que prueba. | `FeatureCoverageTest` falla si una operación no tiene escenario o si un tag nombra una operación inexistente. |

#### 7.1.4. Software Deployment Configuration

La solución se despliega en cuatro destinos, uno por producto digital: la landing page en GitHub Pages, los smart contracts en la red de pruebas Polygon Amoy, LatiFi API en el VPS del equipo administrado con Dokploy, y la aplicación móvil como APK para teléfonos Android. En todos los casos el despliegue parte de la rama `main` del repositorio correspondiente, que solo recibe releases, y ningún secreto (llaves, contraseñas o URLs con API keys) se guarda en los repositorios.

##### Landing Page

| Elemento | Configuración |
|---|---|
| Repositorio | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-landing |
| Destino | GitHub Pages |
| Disparador | Push a `main` (merge de un release) o ejecución manual del workflow |
| Workflow | `.github/workflows/pages.yml` |
| URL publicada | https://arquitectura-de-softwares-emergentes.github.io/latifi-landing/ (inglés) y https://arquitectura-de-softwares-emergentes.github.io/latifi-landing/es/ (español) |

Pasos para el despliegue:

1. En el repositorio, ir a **Settings > Pages** y seleccionar **GitHub Actions** como fuente de publicación (configuración única).
2. Integrar el release en `main` mediante un pull request desde `release/<versión>`, con los checks `ci` y `commit-lint` en verde.
3. El workflow `Deploy Pages` se ejecuta automáticamente: descarga el código, prepara Node.js 22 y copia al directorio `_site` solo los archivos permitidos (páginas HTML, `css/`, `js/`, `img/`, `robots.txt` y `sitemap.xml`) con el script `scripts/stage-site.mjs` en modo estricto, que falla si falta algún archivo esperado.
4. El job `deploy` publica el sitio en GitHub Pages por HTTPS.
5. Al final, el workflow comprueba que la URL publicada responda; si no responde, el despliegue se marca como fallido.

Los pull requests nunca despliegan; solo un merge a `main` publica el sitio.

##### Smart Contracts

| Elemento | Configuración |
|---|---|
| Repositorio | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-contracts |
| Destino | Polygon Amoy (testnet, chain id 80002) |
| Herramienta | Foundry v1.8.7 (`forge`, `cast`) |
| Contratos | `MockStablecoin` (stablecoin de prueba de 6 decimales) y `LoanBook` (libro de préstamos) |
| Release desplegado | `v0.2.0`, verificado en Sourcify con coincidencia exacta |
| Registro del despliegue | `deployments/amoy.json`, fuente única de direcciones y ABIs para la API y la aplicación |

Pasos para el despliegue (guía completa en `docs/DEPLOY-AMOY.md`):

1. Instalar Foundry v1.8.7 (`foundryup --install v1.8.7`) y clonar el repositorio con sus submódulos (`git submodule update --init --recursive`).
2. Importar la llave del deployer a un keystore cifrado de Foundry, que vive fuera del repositorio: `cast wallet import latifi-deployer --interactive`.
3. Cargar POL de prueba en la billetera del deployer desde el faucet de Polygon (al menos 0.15 POL).
4. Ejecutar dos simulaciones sin enviar transacciones: una en memoria y otra contra un fork de Amoy, para confirmar las direcciones y el gas estimado.
5. Desplegar con la cuenta del keystore y las comisiones que exige Amoy:

```bash
export AMOY_RPC_URL=https://polygon-amoy-bor-rpc.publicnode.com
forge script script/Deploy.s.sol:Deploy --rpc-url amoy --account latifi-deployer \
  --sender 0x5577fc66c64e4749eed2e09E6Cd5A2b0e7F970D6 --broadcast --slow \
  --priority-gas-price 30gwei --with-gas-price 35gwei
```

6. Verificar el código de ambos contratos en Sourcify:

```bash
forge verify-contract <LOANBOOK_ADDRESS> src/LoanBook.sol:LoanBook --chain 80002 --verifier sourcify --watch
forge verify-contract <TOKEN_ADDRESS> src/MockStablecoin.sol:MockStablecoin --chain 80002 --verifier sourcify --watch
```

7. Generar el registro del despliegue y validarlo:

```bash
bash scripts/record-deployment.sh broadcast/Deploy.s.sol/80002/run-latest.json v0.2.0 > deployments/amoy.json
bash scripts/check-deployment.sh
```

8. Ejecutar el ciclo completo de prueba (solicitud, fondeo y dos pagos) con las billeteras de demostración: `bash scripts/cycle.sh`. El resultado esperado es `cycle-ok`.

Los scripts solo aceptan las redes 80002 (Amoy) y 31337 (local), y una guarda en la integración continua rechaza cualquier referencia a la red principal o a llaves en el código.

##### Web Services (LatiFi API)

| Elemento | Configuración |
|---|---|
| Repositorio | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-api |
| Destino | VPS de Hetzner administrado con Dokploy (ADR-0006) |
| Runtime | Java 21, Spring Boot 3.5.16, construcción con Maven |
| Base de datos | PostgreSQL 16 en el mismo servidor, con migraciones automáticas de Flyway al iniciar |
| Disparador | Push a `main` mediante la integración de Dokploy con GitHub |
| Health check | `GET /actuator/health` |
| Documentación | Swagger UI en `/swagger-ui.html` y OpenAPI en `/v3/api-docs` |

Pasos para el despliegue:

1. En Dokploy, crear el proyecto **LatiFi** y, dentro de él, un servicio de base de datos **PostgreSQL 16** con usuario `latifi` y una contraseña generada por Dokploy.
2. Crear una aplicación conectada al repositorio `latifi-api` en GitHub, rama `main`, con el tipo de build Nixpacks, que detecta el proyecto Maven y Java 21.
3. Configurar las variables de entorno en la sección **Environment** de la aplicación. Los secretos se guardan solo en Dokploy:

| Variable | Valor |
|---|---|
| `SPRING_DATASOURCE_URL` | URL JDBC interna del servicio PostgreSQL del proyecto |
| `SPRING_DATASOURCE_USERNAME` | `latifi` |
| `SPRING_DATASOURCE_PASSWORD` | Contraseña de la base de datos (secreto) |
| `LATIFI_JWT_SECRET` | Secreto de firma de los tokens de sesión, de al menos 32 bytes (secreto) |
| `LATIFI_AUTH_DOMAIN` | Dominio público de la API |
| `LATIFI_AUTH_URI` | URL pública de la API con HTTPS |
| `LATIFI_TRUST_FORWARDED_FOR` | `true`, porque la API corre detrás del proxy de Dokploy |
| `LATIFI_RPC_URL` | Nodo de Polygon Amoy (por ejemplo, `https://polygon-amoy-bor-rpc.publicnode.com`) |
| `LATIFI_LOANBOOK_ADDRESS` | `0xcCb8ad15a4954138c987a77924ceAb468A843266` (release `v0.2.0`) |
| `LATIFI_INDEXER_START_BLOCK` | Bloque del primer evento a indexar |
| `LATIFI_SWAGGER_ENABLED` | `true` |

4. En la sección **Domains**, asignar el subdominio de la API al puerto 8080 y activar HTTPS con un certificado de Let's Encrypt.
5. Activar el despliegue automático para que cada push a `main` construya y publique una nueva versión.
6. Ejecutar el primer despliegue y comprobar que `GET /actuator/health` responde `UP` y que Swagger UI carga en `/swagger-ui.html`.

##### Mobile Application (LatiFi Wallet)

| Elemento | Configuración |
|---|---|
| Repositorio | https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-android |
| Destino | Teléfonos Android 8.0 o superior (minSdk 26), mediante APK |
| Construcción | Gradle 9.6.1 con JDK 21 |
| Integración continua | El job `ci` genera el APK de debug en cada pull request y lo publica como artefacto |
| Distribución | APK de release adjunto a un GitHub Release y enlazado desde el botón de descarga de la landing page |

Pasos para el despliegue:

1. Configurar los valores del modo Live en el archivo `local.properties` (ignorado por Git) o como variables de entorno:

```properties
reown.projectId=<ID del proyecto en Reown Cloud>
api.baseUrl=<URL pública de LatiFi API>/api/v1/
amoy.rpcUrl=https://polygon-amoy-bor-rpc.publicnode.com
landing.url=https://arquitectura-de-softwares-emergentes.github.io/latifi-landing/
```

2. Generar el APK de release: `./gradlew assembleRelease`. Un build de release se niega a iniciar en modo Demo, por lo que exige el ID de Reown y la URL de la API.
3. Firmar el APK con la llave de firma del equipo (keystore de Android guardado fuera del repositorio).
4. Crear un GitHub Release con el tag de la versión (por ejemplo, `v0.2.0`) y adjuntar el APK firmado.
5. Actualizar el enlace del botón **Descargar para Android** de la landing con la URL del APK, en las versiones en inglés y en español.

##### Deployment Diagram (C4 Model)

El siguiente diagrama muestra los nodos de despliegue de la solución. La aplicación se instala en el teléfono del usuario y se comunica con su billetera mediante Reown (WalletConnect). La llave privada nunca sale de la billetera, y el Android Keystore solo guarda la sesión cifrada. LatiFi API y PostgreSQL corren en el VPS con Dokploy, los smart contracts viven en Polygon Amoy y la landing page se publica en GitHub Pages desde GitHub Actions.

<div align="center">
  <img src="resources/Cap7/7.1.4-deployment-diagram.png" alt="Deployment Diagram de LatiFi" width="90%"/>
</div>


### 7.2. Solution Implementation

Esta sección registra la implementación de los productos digitales de LatiFi organizada por sprint. Para cada sprint se presentan la planificación, el backlog y las evidencias de desarrollo, pruebas, ejecución, documentación de servicios, despliegue y colaboración del equipo.
#### 7.2.1. Sprint 1

El Sprint 1 abarcó la primera versión funcional de los cuatro productos digitales, registrada en los repositorios entre el 29 de octubre y el 11 de noviembre de 2026. En este sprint se implementó el ciclo completo del microcrédito en el smart contract `LoanBook`, desplegado y verificado en Polygon Amoy (release `v0.2.0`); LatiFi API con sus diez endpoints, el indexador de eventos y el cálculo de reputación; la aplicación móvil con los flujos de prestatario y prestamista; y la landing page bilingüe.
##### 7.2.1.1. Sprint Planning 1.

El Sprint Planning Meeting del Sprint 1 se realizó de forma virtual con los cuatro integrantes del equipo. En la reunión se revisaron los resultados de las entregas anteriores (TB1 y TP1), se acordó el objetivo del sprint y se seleccionaron las user stories del Product Backlog según su prioridad. Como el objetivo del proyecto es demostrar el ciclo completo del microcrédito, el equipo decidió incluir las 23 historias del backlog, organizadas por producto digital: smart contracts, LatiFi API, aplicación móvil y landing page.

| Sprint # | Sprint 1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|---|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background** |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Date | 2026-10-28                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Time | 08:00 PM                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Location | Reunión virtual en Microsoft Teams                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Prepared By | Angulo Abud, Juan Carlos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Attendees (to planning meeting) | Angulo Abud, Juan Carlos / Quiroz Zambrano, Fabrizio Javier / Burga Loarte, Anaely / Vilca Valverde, Fiorella Angela                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Sprint 0 Review Summary | En las entregas TB1 y TP1 el equipo completó la investigación y el diseño de la solución: entrevistas a prestatarios y prestamistas, User Personas, Empathy Maps, escenarios As-Is y To-Be, Product Backlog con 23 historias (103 story points), diseño estratégico y táctico con cinco bounded contexts y diagramas C4, y la guía de estilos, arquitectura de información y mock-ups de la landing page y la aplicación. El feedback recibido destacó la claridad del problema y pidió pasar del diseño a una implementación demostrable. |
| Sprint 0 Retrospective Summary | Como aciertos, el equipo resaltó el uso de GitFlow y Conventional Commits en el repositorio del informe y la trazabilidad entre entrevistas, historias y diseño. Como oportunidades de mejora, acordó repartir mejor las tareas entre los integrantes, registrar cada tarea en Trello y vincularla a su pull request, y adelantar la revisión de los entregables para no concentrar el trabajo al final.                                                                                                                                   |
| **Sprint Goal & User Stories** |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Sprint 1 Goal | Nuestro foco está en implementar el ciclo completo del microcrédito P2P en Polygon Amoy. Creemos que esto permite que un prestatario no bancarizado solicite un préstamo sin colateral y que un prestamista lo fondee con información de reputación verificable. Esto se confirmará cuando un prestatario conecte su billetera, publique una solicitud, un prestamista la fondee, el prestatario pague sus cuotas y su reputación se actualice automáticamente a partir de los eventos on-chain, todo desde la aplicación móvil.           |
| Sprint 1 Velocity | 105 story points                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Sum of Story Points | 103 story points                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

##### 7.2.1.2. Sprint Backlog 1.


  <img src="resources/Cap7/TrelloSCREEN.png" alt="Trello Screenshot" width="90%"/>


**URL pública del board:** https://trello.com/b/YDJ16JNs/latifi

| Sprint # | Sprint 1 | | | | | | |
|---|---|---|---|---|---|---|---|
| **User Story Id** | **User Story Title** | **Work-Item / Task Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status (To-do / In-Process / To-Review / Done)** |
| US-AUTH-01 | Conexión de billetera digital | T-01 | Onboarding, conexión e inicio de sesión | Pantallas de conexión de billetera, inicio de sesión y selección de rol (latifi-android, PR #9). | 8 | Juan Angulo | Done |
| US-AUTH-01 | Conexión de billetera digital | T-02 | Gateway de billetera con Reown AppKit | Conexión real con la billetera del usuario mediante Reown AppKit (latifi-android, PR #18). | 10 | Juan Angulo | Done |
| US-AUTH-02 | Firma no custodial de transacciones | T-03 | Spike de almacenamiento seguro de llaves | Prueba de cifrado de la sesión con Android Keystore y su workflow en emulador (latifi-android, PR #2). | 6 | Juan Angulo | Done |
| US-AUTH-02 | Firma no custodial de transacciones | T-04 | Sesión sellada y firma desde la billetera | Firma de transacciones en la billetera del usuario y sesión cifrada con AES-256-GCM (latifi-android, PR #18). | 10 | Juan Angulo | Done |
| TS-API-05 | Autenticación de solicitudes REST por firma de wallet | T-05 | Endpoint de challenge de inicio de sesión | Emisión del mensaje de desafío que firma la billetera y base de pruebas BDD (latifi-api, PR #5). | 6 | Juan Angulo | Done |
| TS-API-05 | Autenticación de solicitudes REST por firma de wallet | T-06 | Verificación de firmas y tokens de sesión | Recuperación del firmante con web3j y emisión de tokens de sesión de 15 minutos (latifi-api, PR #8). | 10 | Juan Angulo | Done |
| US-IDEN-01 | Registro de perfil ligero | T-07 | Pantalla y validación del perfil | Puerta de perfil, formulario, pestaña de perfil y configuración de idioma (latifi-android, PR #10). | 6 | Juan Angulo | Done |
| US-IDEN-02 | Exposición de perfil vía API propia | T-08 | Endpoints de perfil de la billetera | Lectura pública del nombre y escritura solo por el dueño de la billetera (latifi-api, PR #9). | 6 | Juan Angulo | Done |
| US-LAND-01 | Landing page orientada a segmentos | T-09 | Estructura bilingüe de la landing | Esqueleto HTML en inglés y español con guardas de i18n y accesibilidad (latifi-landing, PR #1). | 4 | Juan Angulo (implementación) / Anaely Burga (wireframe de la landing, 6.3.1) | Done |
| US-LAND-01 | Landing page orientada a segmentos | T-10 | Landing page bilingüe | Contenido completo de la landing con secciones por segmento y descarga (latifi-landing, PR #4). | 12 | Juan Angulo (implementación) / Anaely Burga (mock-up de la landing, 6.3.2) | Done |
| US-AUTH-03 | Onboarding progresivo en lenguaje simple | T-11 | Tema de marca y guardas de lenguaje | Tokens de color y tipografía, y pruebas que impiden jerga cripto en la interfaz (latifi-android, PR #6). | 6 | Juan Angulo (implementación) / Fabrizio Quiroz (guía de estilos, 6.1) | Done |
| US-AUTH-03 | Onboarding progresivo en lenguaje simple | T-12 | Flujo de onboarding | Pantallas de bienvenida que explican el modelo P2P antes de conectar la billetera (latifi-android, PR #9). | 8 | Juan Angulo (implementación) / Fabrizio Quiroz (investigación del segmento prestatario, 2.2) | Done |
| US-LEND-01 | Publicación de solicitud de préstamo | T-13 | Interfaz de eventos del préstamo | Eventos `LoanRequested`, `LoanFunded`, `LoanRepaid` y `LoanDefaulted` con su ABI (latifi-contracts, PR #4). | 4 | Juan Angulo (implementación) / Anaely Burga (EventStorming y Domain Storytelling, 4.2) | Done |
| US-LEND-01 | Publicación de solicitud de préstamo | T-14 | Solicitud de préstamo en el contrato | Ruta de solicitud en `LoanBook` y stablecoin de prueba (latifi-contracts, PR #9). | 8 | Juan Angulo | Done |
| US-LEND-01 | Publicación de solicitud de préstamo | T-15 | Flujo de solicitud en la app | Pantalla de solicitud con cálculo de cuotas y envío de la transacción (latifi-android, PR #16). | 8 | Juan Angulo | Done |
| US-LEND-03 | Fondeo de solicitud vía Smart Contract | T-16 | Ciclo de vida del préstamo | Fondeo con transferencia directa, pago en cuotas e incumplimiento en `LoanBook` (latifi-contracts, PR #11). | 12 | Juan Angulo | Done |
| US-LEND-03 | Fondeo de solicitud vía Smart Contract | T-17 | Detalle de solicitud y flujo de fondeo | Detalle de la solicitud para el prestamista y transacción de fondeo (latifi-android, PR #14 y PR #16). | 8 | Juan Angulo | Done |
| US-AUTH-04 | Retroalimentación de estado de transacción | T-18 | Coordinador de transacciones | Estados pendiente, confirmando, confirmada y fallida, con recuperación y hoja de estado (latifi-android, PR #15). | 10 | Juan Angulo | Done |
| TS-API-03 | Indexado de eventos on-chain del Smart Contract | T-19 | Ingesta de eventos del contrato | Lectura de los eventos de `LoanBook` y registro en la tabla `chain_event` (latifi-api, PR #11). | 10 | Juan Angulo | Done |
| TS-API-03 | Indexado de eventos on-chain del Smart Contract | T-20 | Indexador resiliente | Manejo de reorganizaciones de la cadena y caídas del nodo (latifi-api, PR #12). | 12 | Juan Angulo | Done |
| TS-API-03 | Indexado de eventos on-chain del Smart Contract | T-21 | Réplica de préstamos | Proyección de los eventos en el modelo de lectura de préstamos (latifi-api, PR #13). | 8 | Juan Angulo | Done |
| TS-API-04 | Checkpoint de último bloque procesado | T-22 | Checkpoint del indexador | Registro del último bloque procesado para reanudar sin perder ni duplicar eventos (latifi-api, PR #11 y PR #12). | 4 | Juan Angulo | Done |
| US-LEND-02 | Feed de solicitudes con reputación visible | T-23 | Endpoint del feed de préstamos | Feed filtrable y paginado con la reputación de cada prestatario (latifi-api, PR #15). | 8 | Juan Angulo | Done |
| US-LEND-02 | Feed de solicitudes con reputación visible | T-24 | Feed de inversión en la app | Pantalla del prestamista con filtros, orden y contador de resultados (latifi-android, PR #13). | 8 | Juan Angulo (implementación) / Fiorella Vilca (investigación del segmento prestamista, 2.2) | Done |
| US-LEND-04 | Pago de préstamo desde la app | T-25 | Flujo de pago de cuotas | Pago de la siguiente cuota vía `LoanBook` con aprobación de monto exacto (latifi-android, PR #16). | 8 | Juan Angulo | Done |
| US-LEND-05 | Consulta de estado del préstamo | T-26 | Endpoint de detalle de préstamo | Consulta de un préstamo por id con su estado y cronograma (latifi-api, PR #15). | 4 | Juan Angulo | Done |
| US-LEND-05 | Consulta de estado del préstamo | T-27 | Préstamos del prestatario y portafolio | Lista y detalle de préstamos del prestatario, y portafolio e inversiones del prestamista (latifi-android, PR #11 y PR #14). | 10 | Juan Angulo | Done |
| US-LAND-02 | SEO, i18n y accesibilidad básica | T-28 | SEO, i18n y accesibilidad de la landing | Meta tags, hreflang, sitemap, contraste WCAG y verificación con Lighthouse (latifi-landing, PR #4). | 6 | Juan Angulo (implementación) / Anaely Burga (diseño de la landing, 6.3) | Done |
| US-API-02 | Conversión a moneda local vía API propia | T-29 | Endpoints de tipo de cambio | Caché de tasas y endpoints de conversión y listado de monedas (latifi-api, PR #16). | 8 | Juan Angulo | Done |
| US-LEND-06 | Visualización en moneda local | T-30 | Montos en moneda local en la app | Visualización de montos en stablecoin y su equivalente en moneda local (latifi-android, PR #11). | 4 | Juan Angulo (implementación) / Fabrizio Quiroz (hallazgo H4 de las entrevistas, 2.2.3) | Done |
| US-REP-01 | Actualización automática de reputación | T-31 | Cálculo del puntaje de reputación | Cronograma del préstamo y cálculo determinista del puntaje (latifi-api, PR #10). | 8 | Juan Angulo | Done |
| US-REP-01 | Actualización automática de reputación | T-32 | Reputación derivada de eventos | Recalculo del puntaje con cada evento de préstamo indexado (latifi-api, PR #14). | 8 | Juan Angulo | Done |
| US-REP-02 | Reputación híbrida on-chain/off-chain | T-33 | Señal off-chain del perfil | Combinación del perfil completo con las señales de pago on-chain (latifi-api, PR #14). | 6 | Juan Angulo (implementación) / Fabrizio Quiroz (hallazgo H6 de las entrevistas, 2.2.3) | Done |
| US-REP-02 | Reputación híbrida on-chain/off-chain | T-34 | Inicio y reputación en la app | Pantallas de inicio y reputación con lectura de la cadena (latifi-android, PR #12). | 8 | Juan Angulo | Done |
| US-API-01 | Endpoint de historial de reputación | T-35 | Historial de reputación | Endpoint con los eventos detrás del puntaje, filtrable y paginado (latifi-api, PR #14). | 4 | Juan Angulo | Done |
| US-REP-03 | Feed ordenado/destacado por reputación | T-36 | Orden del feed por reputación | Orden por defecto del feed según la reputación del prestatario (latifi-api, PR #15; latifi-android, PR #13). | 4 | Juan Angulo (implementación) / Fiorella Vilca (hallazgo H9 de las entrevistas, 2.2.3) | Done |
| US-REP-04 | Decaimiento/recuperación gradual de reputación | T-37 | Reglas de penalización y recuperación | Penalización por pagos tardíos e incumplimiento, y recuperación gradual con pagos puntuales (latifi-api, PR #10 y PR #14). | 6 | Juan Angulo | Done |
| n/a | Tarea técnica | T-38 | Configuración del repositorio de contratos | Esqueleto de Foundry, CI, commit-lint y guía de contribución (latifi-contracts, PR #1 y PR #2). | 4 | Juan Angulo | Done |
| n/a | Tarea técnica | T-39 | Guarda de red de pruebas | Bloqueo de redes principales y de secretos en el repositorio (latifi-contracts, PR #3). | 3 | Juan Angulo | Done |
| n/a | Tarea técnica | T-40 | Billeteras de demostración | Scripts y runbook del pool de billeteras de prueba (latifi-contracts, PR #5). | 4 | Juan Angulo | Done |
| n/a | Tarea técnica | T-41 | Lint y cobertura de contratos | Reglas de lint propias y perfiles de CI (latifi-contracts, PR #10). | 4 | Juan Angulo | Done |
| n/a | Tarea técnica | T-42 | Suites de seguridad del contrato | Pruebas de reentrancy, fuzz e invariantes de `LoanBook` (latifi-contracts, PR #12). | 10 | Juan Angulo | Done |
| n/a | Tarea técnica | T-43 | Despliegue en Polygon Amoy | Herramientas de despliegue, ensayo local y registro del despliegue `v0.2.0` (latifi-contracts, PR #13 y PR #14). | 8 | Juan Angulo | Done |
| n/a | Tarea técnica | T-44 | Configuración del repositorio de la API | Esqueleto de Spring Boot, CI y commit-lint (latifi-api, PR #1). | 4 | Juan Angulo | Done |
| n/a | Tarea técnica | T-45 | Contrato OpenAPI | Borrador OpenAPI v0 y su actualización a 0.2.0 con la fórmula de reputación (latifi-api, PR #4 y PR #6). | 6 | Juan Angulo | Done |
| n/a | Tarea técnica | T-46 | Errores localizados | Catálogo de errores en en-US y es-419 según el encabezado Accept-Language (latifi-api, PR #7). | 4 | Juan Angulo | Done |
| n/a | Tarea técnica | T-47 | Swagger y cierre de la API | Swagger generado desde el código, guardas de seguridad y réplica del ciclo en Amoy (latifi-api, PR #17). | 6 | Juan Angulo | Done |
| n/a | Tarea técnica | T-48 | Correcciones de revisión de la API | Correcciones de la revisión de código de la fase 4 (latifi-api, PR #19). | 4 | Juan Angulo | Done |
| n/a | Tarea técnica | T-49 | Configuración del repositorio Android | Esqueleto Kotlin con Compose, CI y commit-lint (latifi-android, PR #1). | 4 | Juan Angulo | Done |
| n/a | Tarea técnica | T-50 | Stack Android y APK | Fijado de dependencias, arranque de la app y artefacto APK en CI (latifi-android, PR #5). | 6 | Juan Angulo | Done |
| n/a | Tarea técnica | T-51 | Núcleo de dominio de la app | Montos, cálculo del préstamo, modelos de dominio y codificadores de la cadena (latifi-android, PR #7). | 8 | Juan Angulo | Done |
| n/a | Tarea técnica | T-52 | Navegación por rol | Estructura de navegación por rol, componentes base y registro de rutas (latifi-android, PR #8). | 8 | Juan Angulo (implementación) / Fabrizio Quiroz (sistema de navegación, 6.2.5) | Done |
| n/a | Tarea técnica | T-53 | Capa de datos en vivo | Cliente de la API y del nodo RPC detrás de las interfaces existentes (latifi-android, PR #17). | 10 | Juan Angulo | Done |
| n/a | Tarea técnica | T-54 | Correcciones de revisión de la app | Correcciones de la revisión de código de la fase 5 (latifi-android, PR #19). | 4 | Juan Angulo | Done |


##### 7.2.1.3. Development Evidence for Sprint Review.

Durante el Sprint 1 se implementó la primera versión funcional de los cuatro productos digitales:

- **Smart Contracts:** interfaz de eventos del préstamo, contrato `LoanBook` con el ciclo de solicitud, fondeo, pago en cuotas e incumplimiento, stablecoin de prueba `MockStablecoin` y despliegue verificado en Polygon Amoy (release `v0.2.0`).
- **LatiFi API:** autenticación por firma de billetera con tokens de sesión, perfil ligero, indexador de eventos resiliente a reorganizaciones de la cadena, réplica de préstamos, reputación híbrida con su historial, conversión a moneda local y documentación Swagger.
- **Mobile Application:** tema visual de marca, onboarding, conexión de billetera e inicio de sesión, selección de rol, perfil, préstamos del prestatario, feed de inversión del prestamista, coordinador de transacciones y flujos de solicitud, pago y fondeo, con capa de datos conectada a la API y a la red.
- **Landing Page:** sitio bilingüe en inglés y español con verificaciones de accesibilidad, SEO y seguridad.

Los feature branches se integran en `develop` por squash, por lo que cada commit de la tabla corresponde a un pull request integrado en esa rama.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
|---|---|---|---|---|---|
| Arquitectura-de-Softwares-Emergentes/latifi-landing | develop | 7881351 | Initial commit | n/a | 08/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-landing | develop | 10b368e | build: add bilingual html skeleton, ci and gitflow kit (#1) | feat: add bilingual html skeleton with i18n and aria guard | 29/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-landing | develop | 0e60d14 | feat(landing): bilingual landing page (#4) | feat(landing): add bilingual tracer slice with language persistence | 11/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | cf9f019 | Initial commit | n/a | 08/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | f55041a | ci: add foundry skeleton, ci workflow and commit-lint (#1) | build: add foundry skeleton with solc 0.8.35 pinned | 29/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | e41a887 | docs: add contributing guide, pr template and commit-lint fixtures (#2) | docs: add contributing guide and pull request template | 29/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | 5940d03 | ci: add testnet-only and secret guard (#3) | check-testnet-only.sh rejects chain ids 1 and 137, mainnet RPC hosts and key-shaped literals in tracked files | 29/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | d5e2db9 | feat: add v0 loan event interface and abi (#4) | feat: add v0 loan event interface and abi | 29/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | 8682853 | feat: add demo wallet pool scripts and runbook (#5) | feat: add demo wallet pool scripts with chain id guard | 29/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | f1da82e | feat: add loan request path, mock stablecoin and pinned openzeppelin (#9) | build: pin openzeppelin contracts v5.7.0 and add foundry profiles | 31/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | 51e90da | ci: add lint, coverage and ci profile gates (#10) | ci: add repo lint rules with a mutation self-test | 31/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | 4b86baf | feat: add the loan lifecycle with installments and default (#11) | feat: add fund with wallet to wallet transfer and a fixed total due | 31/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | a97a2bd | test: add reentrancy, fuzz and invariant suites for the loan book (#12) | test: add malicious receiver reentrancy and fee on transfer suites | 31/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | 698191e | feat: add deploy tooling, a local rehearsal and the amoy runbook (#13) | feat: add the cycle script and a local rehearsal in the foundry image | 31/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | 2a0ed34 | feat(deploy): record the Polygon Amoy deployment for v0.2.0 (#14) | feat(deploy): record the Polygon Amoy deployment for v0.2.0 | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | f7a8541 | Initial commit | n/a | 08/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | cfcfed8 | build: add spring boot skeleton, ci and gitflow kit (#1) | build: add spring boot 3.5 skeleton with postgres and spotless | 29/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 2849aac | docs: add openapi v0 draft with ci validation (#4) | docs(api): add openapi v0 skeleton with the challenge endpoint | 30/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | eb002c0 | feat: add the bdd harness and the wallet challenge endpoint (#5) | build: pin the api stack and add the bdd harness | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | b660b98 | docs: amend the openapi draft to 0.2.0 and describe the reputation formula (#6) | docs: amend the openapi draft to 0.2.0 | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | f253336 | feat: localize api errors and complete the error catalog (#7) | feat: resolve error message language from accept-language | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 274834d | feat: verify wallet signatures and issue session tokens (#8) | feat: verify wallet signatures and issue session tokens | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 7ffb709 | feat: add the wallet profile endpoints (#9) | feat: store and read the wallet profile | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 8cad6d9 | feat: add the loan schedule and the reputation score fold (#10) | test: describe the loan schedule arithmetic | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 874ed83 | feat: add the event indexer ingestion (#11) | feat: mirror contract logs into chain_event with a checkpoint | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 6f0845f | feat: make the event indexer resilient to reorgs and outages (#12) | feat: reconcile the reorg window inside the batch transaction | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 52799cc | feat: mirror loans from chain events (#13) | feat: project chain events into the loan read model | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 534516c | feat: serve the hybrid reputation score and its history (#14) | feat: derive and serve the reputation score from chain events | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | faa74af | feat: serve the loan feed and loan detail (#15) | feat: serve a mirrored loan by id | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 67ce006 | feat: add the exchange rate cache and conversion endpoints (#16) | feat: convert stablecoin amounts with cached exchange rates | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | ad55104 | feat: close the api surface with swagger, guards and the amoy replay (#17) | feat: serve swagger from the code and guard it against the contract | 09/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | bedf16e | fix: address phase 4 review findings CR-01, WR-03, WR-06, WR-07, WR-10 (#19) | fix: limit auth routes by decoded path so encoded segments cannot skip the rate limit | 09/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | b14f4e5 | Initial commit | n/a | 08/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 8a9a07a | build: add kotlin android skeleton, ci and gitflow kit (#1) | build: add kotlin android skeleton with compose and pinned toolchain | 29/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 70b5154 | test: add keystore envelope spike and emulator workflow (#2) | test: add keystore envelope spike for secp256k1 wallet keys | 29/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 98edda4 | build: pin the android stack, boot the app and add the apk artifact (#5) | build: pin the android stack and the jitpack groups | 09/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | ba639f0 | feat(theme): add brand tokens, fonts and copy guards (#6) | build: bundle the sora and inter variable fonts with their licenses | 09/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 579ee92 | feat(core): add loan math, money, domain models and the chain encoders (#7) | feat(core): add token amounts and the loan math of the contract | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 7ac37df | feat(nav): add the role shell, base components and the routes registry (#8) | build: import the material symbols icon set with attribution | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | f25b0f4 | feat(onboarding): add onboarding, connect, sign-in and role selection (#9) | fix(ui): give the dialog safe action its initial focus from inside the dialog | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 14abf59 | feat(profile): add the profile gate, the profile tab and language settings (#10) | feat(profile): add the profile repository, gate and validator | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 1d91f60 | feat(loans): add the borrower loan list, loan details and local currency values (#11) | feat(loans): add the loan and exchange rate interfaces with fakes | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 016bb86 | feat(home): add home and reputation with chain read and reputation interfaces (#12) | feat(chain): add the chain read interface, the fee policy and a scriptable fake | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 5f86753 | feat(feed): add the lender invest feed with filters, sort and a counter (#13) | feat(feed): map filter chips to the loan query | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 224d34c | feat(lender): add request details, the portfolio list and investment details (#14) | refactor(reputation): share the history row component | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 70dad77 | feat(tx): add the transaction coordinator, recovery and the status sheet (#15) | feat(tx): add the rpc interface, the receipt poller and a scriptable fake | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | bf24282 | feat(flows): add request, pay, fund and test coin flows with a demo chain simulator (#16) | feat(tx): build exact-amount transaction plans and guard against unlimited approvals | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 5644232 | feat(api): add the live api and rpc data layer behind the existing interfaces (#17) | feat(api): add the contract dtos, the retrofit client and the error mapping | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | a8245a7 | feat(wallet): add the live reown gateway, the sealed session and the device checklist (#18) | feat(wallet): add the appkit adapter and the wallet gateway with request ids | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 656c094 | fix: apply the phase 5 code review findings (#19) | fix(config): refuse to start a release build in demo mode | 10/11/2026 |

##### 7.2.1.4. Testing Suite Evidence for Sprint Review.

En el Sprint 1 cada producto incorporó su conjunto de pruebas automatizadas, que se ejecutan en el job `ci` de GitHub Actions en cada pull request:

| Producto | Tipo de prueba | Herramienta | Alcance |
|---|---|---|---|
| Web Services (LatiFi API) | Unit Tests | JUnit 5 | Reglas de dominio y adaptadores de cada bounded context. |
| Web Services (LatiFi API) | Integration y Acceptance Tests (BDD) | Cucumber + Testcontainers (PostgreSQL 16) | 9 archivos `.feature` con 117 escenarios que recorren los diez endpoints contra una base de datos real y un nodo de blockchain simulado. |
| Smart Contracts | Unit, fuzz e invariant tests | Foundry (`forge test`) | 160 pruebas sobre `LoanBook`, `MockStablecoin` y la ABI de eventos, incluidas pruebas de ataques de reentrada. |
| Mobile Application | Unit Tests | JUnit + kotlinx-coroutines-test | 102 clases de prueba sobre ViewModels, reglas de negocio y capa de datos. |
| Mobile Application | Instrumented UI Tests | Compose UI Test en emulador Android | 24 clases de prueba sobre las pantallas principales y su accesibilidad. |
| Landing Page | Verificaciones automatizadas | Nu HTML Checker, Lighthouse, Chrome sin interfaz | Validez del HTML, accesibilidad, SEO, contraste, seguridad (CSP) y escenarios de navegación. |

**Unit Tests**

| Test | Repositorio | Clase relacionada | Comportamiento probado |
|---|---|---|---|
| `LoanScheduleTest` | latifi-api | `LoanSchedule` | El total adeudado coincide con el cálculo de `LoanBook`, el interés se redondea hacia abajo y no hay desbordamiento con montos grandes. |
| `ScoreLedgerTest` | latifi-api | `ScoreLedger` | El puntaje parte del valor inicial y sigue los ejemplos de la fórmula de reputación, incluida la penalización por incumplimiento. |
| `ReputationLevelTest` | latifi-api | `ReputationLevel` | Los umbrales de cada nivel siguen la escala definida en el informe. |
| `Web3jSignatureVerifierTest` | latifi-api | `Web3jSignatureVerifier` | Recupera la dirección de la billetera que firmó y detecta un mensaje alterado. |
| `LoanFolderTest` | latifi-api | `LoanFolder` | Reconstruye el estado de un préstamo a partir de sus eventos on-chain. |
| `ConversionTest` | latifi-api | Conversión de montos (`exchangerate`) | Convierte montos en stablecoin a soles y respeta los decimales de cada moneda. |
| `LoanBook.request.t.sol` | latifi-contracts | `LoanBook` | Límites de monto, plazo y cuotas de una solicitud de préstamo. |
| `LoanBook.fund.t.sol` | latifi-contracts | `LoanBook` | Fondeo con transferencia directa del prestamista al prestatario y total adeudado fijo. |
| `LoanBook.repay.t.sol` | latifi-contracts | `LoanBook` | Pago en cuotas, pagos tardíos e incumplimiento. |
| `LoanBook.reentrancy.t.sol` | latifi-contracts | `LoanBook` | Un atacante no puede reingresar en `fund`, `repay` ni `markDefaulted`. |
| `LoanBook.invariant.t.sol` | latifi-contracts | `LoanBook` | El contrato nunca retiene tokens, los tokens se conservan y lo pagado nunca supera lo adeudado. |
| `LoanMathTest` | latifi-android | `LoanMath` | La app reproduce el interés, la división en cuotas y las fechas de vencimiento del contrato. |
| `TokenAmountTest` | latifi-android | `TokenAmount` | Lectura y formato de montos con 6 decimales. |
| `TransactionCoordinatorTest` | latifi-android | `TransactionCoordinator` | Seguimiento del estado de una transacción y su recuperación ante fallas. |
| `NoUnlimitedApproveTest` | latifi-android | `TxPlans` | La app nunca solicita aprobaciones ilimitadas de tokens. |
| `ProfileValidatorTest` | latifi-android | `ProfileValidator` | Validación de los datos del perfil ligero. |

**Integration Tests y Acceptance Tests (BDD)**

Los archivos `.feature` de LatiFi API están en https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-api/tree/develop/src/test/resources/features. Cada escenario lleva el tag `@op-<operationId>` de la operación del contrato OpenAPI que prueba.

| Archivo `.feature` | Escenarios | User Stories relacionadas |
|---|---|---|
| `auth.feature` | 18 | TS-API-05 |
| `profiles.feature` | 12 | US-IDEN-01, US-IDEN-02 |
| `loans.feature` | 15 | US-LEND-02, US-LEND-05, US-REP-03 |
| `reputation.feature` | 19 | US-REP-01, US-REP-02, US-REP-04, US-API-01 |
| `fx.feature` | 17 | US-API-02, US-LEND-06 |
| `indexer.feature` | 17 | TS-API-03, TS-API-04 |
| `loan_mirror.feature` | 11 | TS-API-03, US-LEND-05 |
| `amoy_fixture.feature` | 1 | TS-API-03 |
| `errors.feature` | 7 | Transversal: mensajes de error localizados en en-US y es-419 |

A continuación se muestra un fragmento de tres de ellos.

`auth.feature`:

```gherkin
@auth
Feature: Wallet sign-in challenge
  A wallet asks for a challenge, signs it, and later trades the signature for a session.
  This feature covers the first half: issuing the challenge.

  @op-issueChallenge
  Scenario: A valid address receives a challenge
    Given a wallet address generated at run time
    When the client requests a sign-in challenge for that address
    Then the response status is 200
    And the challenge response conforms to the API contract
    And the challenge message is a well formed sign-in text for that address
    And the stored challenge matches the response
```

`profiles.feature`:

```gherkin
@profiles
Feature: Wallet profile
  A wallet owner stores a display name and a contact. Everybody reads the name, only the owner
  reads the contact, and only the owner writes.

  @op-upsertProfile @op-getProfile
  Scenario: An owner creates a profile and the public sees only the name
    Given the wallet A is generated at run time
    And the wallet A is logged in
    When the wallet A saves its own profile with name "Ana Quispe" and EMAIL contact "ana@example.org"
    Then the response status is 201
    And the profile response conforms to the API contract
    When an anonymous client reads the profile of A
    Then the response status is 200
    And the profile response conforms to the API contract
    And the profile body has the display name "Ana Quispe"
    And the profile body has no contact key
    When the wallet A reads the profile of A
    Then the response status is 200
    And the profile body has the contact EMAIL "ana@example.org"
    And the profile row of A has the lowercase address

  @op-upsertProfile
  Scenario: Nobody writes another wallet's profile
    Given the wallet A is generated at run time
    And the wallet B is generated at run time
    And the wallet A is logged in
    When the wallet A saves the profile of B with name "Intruder" and EMAIL contact "intruder@example.org"
    Then the response status is 403
    And the response is an ApiError with code "FORBIDDEN_NOT_OWNER"
```

`reputation.feature`:

```gherkin
@reputation
Feature: Reputation
  The score of an address is derived from the indexed chain events and from the profile. Each
  completed installment, each default and the completed profile is one entry of a ledger, and the
  API serves the score and the entries behind it.

  Scenario: An on-time installment raises the score
    Given the wallet W is generated at run time
    And the wallet W is logged in
    And the node has 20 blocks
    And loan 7 of 1000000000 units in 3 installments over 90 days is requested at block 10
    And loan 7 is funded at the time 1800000000 at block 12
    And a payment of 341552511 units on loan 7 is emitted at block 14 with the block time 1802500000 and the flag onTime
    When the indexer runs once
    And the wallet W reads the reputation of "borrower"
    Then the response status is 200
    And the reputation response conforms to the API contract
    And the reputation is score 520 and level BUILDING with 1 on time, 0 late and 0 defaults
    And the reputation has profileComplete false
    And the reputation was updated at the timestamp of block 14
    And the ledger row of the borrower carries the transaction hash and log index of the repayment of loan 7 and the score after 520
```

**Repositorios de testing:**

- Web Services: https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-api (pruebas en `src/test`)
- Smart Contracts: https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-contracts (pruebas en `test`)
- Mobile Application: https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-android (pruebas en `app/src/test` y `app/src/androidTest`)
- Landing Page: https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-landing (verificaciones en `scripts`)

Las pruebas se integraron junto con la funcionalidad que verifican, en el mismo pull request. La tabla muestra el subcommit de pruebas de cada uno:

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
|---|---|---|---|---|---|
| Arquitectura-de-Softwares-Emergentes/latifi-landing | develop | 0e60d14 | feat(landing): bilingual landing page (#4) | test(landing): scope header link count and wait for hash scroll | 11/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | d5e2db9 | feat: add v0 loan event interface and abi (#4) | test: pin loan event selectors and the json abi | 29/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | f1da82e | feat: add loan request path, mock stablecoin and pinned openzeppelin (#9) | test: cover request boundaries and mock stablecoin caps | 31/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-contracts | develop | a97a2bd | test: add reentrancy, fuzz and invariant suites for the loan book (#12) | test: add malicious receiver reentrancy and fee on transfer suites | 31/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | b660b98 | docs: amend the openapi draft to 0.2.0 and describe the reputation formula (#6) | test: guard the openapi 0.2.0 invariants | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 7ffb709 | feat: add the wallet profile endpoints (#9) | test: prove profile ownership, visibility and privacy | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 8cad6d9 | feat: add the loan schedule and the reputation score fold (#10) | test: describe the loan schedule arithmetic | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 874ed83 | feat: add the event indexer ingestion (#11) | test: prove restarts, duplicates, scheduling and the abi guard | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 52799cc | feat: mirror loans from chain events (#13) | test: describe the loan fold rules | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 534516c | feat: serve the hybrid reputation score and its history (#14) | test: prove the reputation rules, history and reorg repair | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 67ce006 | feat: add the exchange rate cache and conversion endpoints (#16) | test: prove the exchange rate cache, stale fallback and provider adapter | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | ad55104 | feat: close the api surface with swagger, guards and the amoy replay (#17) | test: replay the planned amoy cycle and add the optional live smoke | 09/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 70b5154 | test: add keystore envelope spike and emulator workflow (#2) | test: add keystore envelope spike for secp256k1 wallet keys | 29/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 98edda4 | build: pin the android stack, boot the app and add the apk artifact (#5) | test: prove the stack with abi, config and launch tests | 09/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | ba639f0 | feat(theme): add brand tokens, fonts and copy guards (#6) | test(theme): assert the contrast table and the type tokens | 09/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 579ee92 | feat(core): add loan math, money, domain models and the chain encoders (#7) | test(chain): guard the deployment constants and the event signature | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 7ac37df | feat(nav): add the role shell, base components and the routes registry (#8) | test(nav): cover the tab model, large text mode and the scaffold | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | f25b0f4 | feat(onboarding): add onboarding, connect, sign-in and role selection (#9) | test(auth): cover the wait timer, sign-in, coordinator and start rules | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 14abf59 | feat(profile): add the profile gate, the profile tab and language settings (#10) | test(profile): cover the validator, the gate and the form state | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 1d91f60 | feat(loans): add the borrower loan list, loan details and local currency values (#11) | test(loans): cover the loan list and the loan details on an emulator | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 016bb86 | feat(home): add home and reputation with chain read and reputation interfaces (#12) | test(home): cover home and reputation on an emulator | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 5f86753 | feat(feed): add the lender invest feed with filters, sort and a counter (#13) | test(feed): cover the invest feed on an emulator | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 224d34c | feat(lender): add request details, the portfolio list and investment details (#14) | test(lender): cover request details, portfolio and investment details on an emulator | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 70dad77 | feat(tx): add the transaction coordinator, recovery and the status sheet (#15) | test(tx): cover the transaction status sheet on an emulator | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | bf24282 | feat(flows): add request, pay, fund and test coin flows with a demo chain simulator (#16) | test(flows): cover the coins and request screens on an emulator | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | 5644232 | feat(api): add the live api and rpc data layer behind the existing interfaces (#17) | test(api): guard the contract version, the operation ids and the fixtures | 10/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-android | develop | a8245a7 | feat(wallet): add the live reown gateway, the sealed session and the device checklist (#18) | test(wallet): cover the gateway events, response classification and request params | 10/11/2026 |

##### 7.2.1.5. Execution Evidence for Sprint Review.

Al cierre del Sprint 1, la landing page está publicada en GitHub Pages en inglés y español, y la aplicación móvil LatiFi Wallet ejecuta los flujos completos de prestatario y prestamista: onboarding, conexión de la billetera, elección de rol, perfil ligero, solicitud de préstamo, pago de cuotas, feed de inversión, fondeo, portafolio y reputación. La aplicación funciona en dos modos: el modo Demo, que simula la red y no necesita billetera ni conexión, y el modo Live, que se conecta a la billetera real del usuario, a LatiFi API y a los smart contracts desplegados en Polygon Amoy.

**Landing Page**

La sección principal presenta la propuesta de valor, los accesos para cada segmento y un ejemplo de préstamo con cifras ilustrativas. Debajo se resumen los cuatro diferenciadores: el usuario guarda sus llaves, la reputación es visible para los prestamistas, las reglas están escritas en un contrato y los montos se muestran también en soles.

<div align="center">
  <img src="resources/Cap7/7.2.1.5-landing-es-top.png" alt="Landing page: sección principal" width="80%"/>
</div>

La sección "¿Cómo funciona?" explica el ciclo del préstamo en pasos, y la sección de beneficios muestra que las condiciones son claras desde la primera pantalla:

<div align="center">
  <img src="resources/Cap7/7.2.1.5-landing-es-como-funciona.png" alt="Landing page: cómo funciona" width="80%"/>
  <br/><br/>
  <img src="resources/Cap7/7.2.1.5-landing-es-beneficios.png" alt="Landing page: beneficios" width="80%"/>
</div>

La sección de seguridad explica el modelo no custodial, y las preguntas frecuentes resuelven las dudas más comunes de ambos segmentos:

<div align="center">
  <img src="resources/Cap7/7.2.1.5-landing-es-seguridad.png" alt="Landing page: seguridad" width="80%"/>
  <br/><br/>
  <img src="resources/Cap7/7.2.1.5-landing-es-faq.png" alt="Landing page: preguntas frecuentes" width="80%"/>
</div>

La sección de descarga dirige al visitante a la aplicación para Android:

<div align="center">
  <img src="resources/Cap7/7.2.1.5-landing-es-descarga.png" alt="Landing page: descarga" width="80%"/>
</div>

La página está disponible en inglés (en_US) y se adapta a pantallas de teléfono, con el menú de navegación agrupado en un botón:

| Versión en inglés | Versión móvil |
|---|---|
| <img src="resources/Cap7/7.2.1.5-landing-en-hero.png" alt="Landing page en inglés" width="420"/> | <img src="resources/Cap7/7.2.1.5-landing-es-movil.png" alt="Landing page en móvil" width="200"/> |

**URL de la landing page:** https://arquitectura-de-softwares-emergentes.github.io/latifi-landing/

**Mobile Application (LatiFi Wallet)**

Las capturas se tomaron en un Pixel 9a con la compilación debug de la rama `develop`, en modo Demo. En ese modo la billetera es simulada y los datos son de ejemplo: los montos están en tUSD, dólares de prueba sin valor real, y los nombres son ficticios.

El usuario conoce el modelo P2P en el onboarding, conecta su billetera, confirma que es el dueño firmando un mensaje (sin costo y sin mover dinero) y elige su rol:

| Onboarding | Conectar billetera | Firmar para entrar | Elegir rol |
|---|---|---|---|
| <img src="resources/Cap7/7.2.1.5-app-01-onboarding.png" alt="Onboarding" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-02-conectar.png" alt="Conectar billetera" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-03-firma.png" alt="Firmar para entrar" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-04-rol.png" alt="Elegir rol" width="180"/> |

El prestatario completa su perfil ligero y, desde su inicio, ve su saldo, su reputación y su próxima cuota. Para solicitar un préstamo elige el monto, la tasa, el plazo y las cuotas, y revisa el total a devolver en tUSD y en soles antes de publicar:

| Perfil ligero | Inicio del prestatario | Solicitar préstamo | Revisar solicitud |
|---|---|---|---|
| <img src="resources/Cap7/7.2.1.5-app-05-perfil.png" alt="Perfil ligero" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-06-inicio-prestatario.png" alt="Inicio del prestatario" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-07-solicitar.png" alt="Solicitar préstamo" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-08-revisar-solicitud.png" alt="Revisar solicitud" width="180"/> |

Cuando la red confirma la transacción, la solicitud queda abierta para los prestamistas. Después, el prestatario paga sus cuotas desde su propia billetera, y cada pago a tiempo sube su puntaje de reputación:

| Solicitud publicada | Pagar cuota | Cuota pagada | Reputación |
|---|---|---|---|
| <img src="resources/Cap7/7.2.1.5-app-09-solicitud-publicada.png" alt="Solicitud publicada" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-10-pagar-cuota.png" alt="Pagar cuota" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-11-cuota-pagada.png" alt="Cuota pagada" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-12-reputacion.png" alt="Reputación" width="180"/> |

El prestamista ve en su inicio las solicitudes abiertas y el próximo pago que recibirá. En el feed puede ordenar y filtrar por riesgo, plazo y monto, y en el detalle de cada solicitud revisa el historial de pagos del prestatario antes de fondear:

| Inicio del prestamista | Feed de inversión | Detalle de la solicitud | Confirmar fondeo |
|---|---|---|---|
| <img src="resources/Cap7/7.2.1.5-app-13-inicio-prestamista.png" alt="Inicio del prestamista" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-14-feed.png" alt="Feed de inversión" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-15-detalle-solicitud.png" alt="Detalle de la solicitud" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-16-fondear.png" alt="Confirmar fondeo" width="180"/> |

El fondeo se hace en dos pasos: primero se autoriza el monto exacto y luego se fondea la solicitud. La inversión aparece en el portafolio con su retorno esperado y el calendario de cuotas. Desde el perfil, cualquier usuario puede pedir monedas de prueba para probar la aplicación:

| Fondeo confirmado | Portafolio | Detalle de la inversión | Monedas de prueba |
|---|---|---|---|
| <img src="resources/Cap7/7.2.1.5-app-17-fondeo-confirmado.png" alt="Fondeo confirmado" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-18-portafolio.png" alt="Portafolio" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-19-detalle-inversion.png" alt="Detalle de la inversión" width="180"/> | <img src="resources/Cap7/7.2.1.5-app-20-monedas-prueba.png" alt="Monedas de prueba" width="180"/> |

##### 7.2.1.6. Services Documentation Evidence for Sprint Review.

En el Sprint 1 se documentaron con OpenAPI 3.0 los diez endpoints de LatiFi API, que cubren la autenticación por firma de billetera, el perfil ligero, la reputación, los préstamos y la conversión a moneda local. El contrato `openapi/latifi-api.v0.yaml` (versión 0.2.0) se escribió antes que el código y es la fuente común de la API y de la aplicación móvil: una prueba de la API falla si el código se aparta del contrato, y otra prueba de la aplicación falla si su cliente Retrofit deja de coincidir con él. La documentación se publica con Swagger UI, generada desde el código con springdoc-openapi.

Todos los endpoints están bajo la ruta base `/api/v1`. Salvo los de autenticación y la lectura pública de perfiles, requieren el token de sesión en el encabezado `Authorization: Bearer <token>`. El encabezado opcional `Accept-Language` (`en_US` o `es_419`) define el idioma de los mensajes de error. Los montos y los identificadores de préstamo viajan como texto en unidades base de la stablecoin de prueba (6 decimales), para no perder precisión.

| Endpoint | Acción implementada | Verbo HTTP | Sintaxis de llamada | Parámetros | Ejemplo de response y explicación | Enlace a la documentación |
|---|---|---|---|---|---|---|
| `/auth/challenge` | Emitir el mensaje de inicio de sesión que firma la billetera | POST | `POST /api/v1/auth/challenge` | Body: `address` (dirección de la billetera) | `200`: `{"challengeId": "3f2b8c1e-...", "nonce": "9c1d4f7a...", "message": "latifi.example wants you to sign in...", "issuedAt": "2026-01-01T12:00:00Z", "expiresAt": "2026-01-01T12:05:00Z"}`. Devuelve un mensaje de un solo uso que vence en 5 minutos y no genera ninguna transacción. | http://localhost:8080/swagger-ui.html#/Auth/issueChallenge |
| `/auth/verify` | Verificar la firma y emitir el token de sesión | POST | `POST /api/v1/auth/verify` | Body: `challengeId`, `address`, `signature` | `200`: `{"accessToken": "eyJhbGciOiJIUzI1NiJ9...", "tokenType": "Bearer", "expiresIn": 900, "address": "0x1111..."}`. Si la firma corresponde a la dirección, entrega un token válido por 15 minutos; si no, responde `401`. | http://localhost:8080/swagger-ui.html#/Auth/verifyChallenge |
| `/profiles/{address}` | Consultar el perfil ligero de una dirección | GET | `GET /api/v1/profiles/0x1111...` | Path: `address`. Token opcional | `200`: `{"address": "0x1111...", "displayName": "Sample User", "contact": {"type": "EMAIL", "value": "user@example.org"}, "createdAt": "...", "updatedAt": "..."}`. Cualquiera ve el nombre; el contacto solo lo ve el dueño de la billetera. `404` si no existe. | http://localhost:8080/swagger-ui.html#/Profiles/getProfile |
| `/profiles/{address}` | Crear o actualizar el perfil propio | PUT | `PUT /api/v1/profiles/0x1111...` | Path: `address`. Body: `displayName`, `contact` (`type`: `EMAIL` o `PHONE`, `value`) | `201` al crear y `200` al actualizar, con el perfil completo. Responde `403` si la dirección no es la del usuario autenticado. | http://localhost:8080/swagger-ui.html#/Profiles/upsertProfile |
| `/reputation/{address}` | Consultar el puntaje de reputación | GET | `GET /api/v1/reputation/0x1111...` | Path: `address` | `200`: `{"address": "0x1111...", "score": 620, "level": "TRUSTED", "onTimeCount": 3, "lateCount": 1, "defaultCount": 0, "profileComplete": true, "updatedAt": "..."}`. Puntaje de 0 a 1000 con nivel `NEW`, `BUILDING`, `TRUSTED` o `EXCELLENT`, calculado a partir de los eventos on-chain y del perfil. | http://localhost:8080/swagger-ui.html#/Reputation/getReputation |
| `/reputation/{address}/history` | Listar los eventos detrás del puntaje | GET | `GET /api/v1/reputation/0x1111.../history?type=REPAID_ON_TIME&page=0&size=20` | Path: `address`. Query: `type` (`PROFILE_COMPLETED`, `REPAID_ON_TIME`, `REPAID_LATE`, `DEFAULTED`), `page`, `size` | `200`: `{"items": [{"id": 41, "loanId": "7", "type": "REPAID_ON_TIME", "delta": 20, "scoreAfter": 620, "txHash": "0x2222...", "occurredAt": "..."}], "page": 0, "size": 20, "totalItems": 1}`. Cada evento indica cuánto cambió el puntaje y la transacción que lo originó. | http://localhost:8080/swagger-ui.html#/Reputation/getReputationHistory |
| `/loans` | Listar préstamos con filtros y orden (feed del prestamista) | GET | `GET /api/v1/loans?status=OPEN&minLevel=TRUSTED&sort=reputation&page=0&size=20` | Query: `status` (`OPEN`, `ACTIVE`, `REPAID`, `DEFAULTED`), `minAmount`, `maxAmount`, `maxTermDays`, `minLevel`, `borrower`, `lender`, `sort` (`reputation`, `amount`, `term`, `rate`, `recent`, `nextDue`), `page`, `size` | `200`: `{"items": [{"loanId": "7", "borrower": "0x1111...", "principal": "250000000", "interestRateBps": 1000, "termDays": 30, "installments": 3, "status": "OPEN", "totalDue": "...", "borrowerReputation": {"score": 620, "level": "TRUSTED"}}], "page": 0, "size": 20, "totalItems": 1}`. Por defecto ordena por la reputación del prestatario. | http://localhost:8080/swagger-ui.html#/Loans/listLoans |
| `/loans/{loanId}` | Consultar un préstamo con su estado y cronograma | GET | `GET /api/v1/loans/7` | Path: `loanId` | `200`: un préstamo con monto, tasa, cuotas pagadas, total adeudado, próxima fecha de pago y reputación del prestatario. `404` si el préstamo no existe. | http://localhost:8080/swagger-ui.html#/Loans/getLoan |
| `/exchange-rate/convert` | Convertir un monto de stablecoin a moneda local | GET | `GET /api/v1/exchange-rate/convert?amount=250000000&currency=PEN` | Query: `amount` (unidades base), `currency` (`PEN`, `COP`, `MXN`, `ARS`, `BRL` o `CLP`) | `200`: `{"amount": "250000000", "currency": "PEN", "value": "859.51", "rate": "3.438038", "asOf": "...", "stale": false}`. Convierte 250 USD de prueba a soles. `stale: true` indica que se usó la última tasa guardada porque el proveedor no respondió. | http://localhost:8080/swagger-ui.html#/ExchangeRate/convertAmount |
| `/exchange-rate/rates` | Listar las tasas disponibles y su antigüedad | GET | `GET /api/v1/exchange-rate/rates` | Ninguno | `200`: `[{"base": "USD", "quote": "PEN", "rate": "3.438038", "asOf": "...", "stale": false}, ...]`, con las seis monedas soportadas. `503` si no hay tasas en caché ni proveedor disponible. | http://localhost:8080/swagger-ui.html#/ExchangeRate/listRates |

**Interacción con la documentación**

La vista general de Swagger UI agrupa los endpoints por contexto (Auth, Profiles, Reputation, Loans y ExchangeRate) y muestra con un candado los que requieren token de sesión. El botón **Authorize** permite registrar el token obtenido en `/auth/verify` para probar los demás endpoints.

<div align="center">
  <img src="resources/Cap7/7.2.1.6-swagger-overview.png" alt="Vista general de Swagger UI de LatiFi API" width="80%"/>
</div>

Al solicitar un challenge, la documentación muestra el cuerpo esperado con una dirección de ejemplo y la respuesta con el mensaje que la billetera debe firmar:

<div align="center">
  <img src="resources/Cap7/7.2.1.6-swagger-auth-challenge.png" alt="Swagger UI: POST /auth/challenge" width="70%"/>
</div>

El feed de préstamos documenta todos sus filtros, el orden por reputación y la paginación, junto con un préstamo de ejemplo que incluye la reputación de su prestatario:

<div align="center">
  <img src="resources/Cap7/7.2.1.6-swagger-loans-list.png" alt="Swagger UI: GET /loans" width="70%"/>
</div>

La consulta de reputación muestra el puntaje, el nivel y los contadores de pagos a tiempo, tardíos e incumplidos, además de las respuestas de error con su código y mensaje localizado:

<div align="center">
  <img src="resources/Cap7/7.2.1.6-swagger-reputation.png" alt="Swagger UI: GET /reputation/{address}" width="70%"/>
</div>

La conversión de moneda muestra el monto en unidades base, la moneda de destino y el valor convertido con la tasa utilizada:

<div align="center">
  <img src="resources/Cap7/7.2.1.6-swagger-exchange-convert.png" alt="Swagger UI: GET /exchange-rate/convert" width="70%"/>
</div>

**Repositorio de Web Services:** https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-api

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
|---|---|---|---|---|---|
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | 2849aac | docs: add openapi v0 draft with ci validation (#4) | docs(api): add openapi v0 skeleton with the challenge endpoint | 30/10/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | b660b98 | docs: amend the openapi draft to 0.2.0 and describe the reputation formula (#6) | docs: amend the openapi draft to 0.2.0 | 08/11/2026 |
| Arquitectura-de-Softwares-Emergentes/latifi-api | develop | ad55104 | feat: close the api surface with swagger, guards and the amoy replay (#17) | feat: serve swagger from the code and guard it against the contract | 09/11/2026 |

##### 7.2.1.7. Software Deployment Evidence for Sprint Review.

Durante el Sprint 1 el equipo dejó cada producto digital con su propio camino de integración y despliegue automatizado, desde la creación de las cuentas hasta la verificación en producción. Todo el código vive en la organización de GitHub del equipo, y cada repositorio ejecuta GitHub Actions con dos controles en cada pull request: `ci`, que compila y prueba, y `commit-lint`, que rechaza mensajes fuera de Conventional Commits. Las cuentas y los recursos creados en proveedores externos son estos:

| Proveedor | Para qué lo usa el equipo | Producto |
|---|---|---|
| GitHub (organización, Actions, Pages y GHCR) | Repositorios, integración continua, alojamiento de la landing y registro de la imagen de contenedor | Todos |
| Cloudflare DNS | Registro `latifi-api.juan-tech.com`, solo DNS, hacia el servidor | Web Services |
| Hetzner con Dokploy | Servidor que construye y ejecuta la API con HTTPS | Web Services |
| Let's Encrypt | Certificado HTTPS de la API, emitido desde Dokploy | Web Services |
| Alchemy (plan gratuito) | Nodo RPC de Polygon Amoy que lee el indexador | Web Services y Smart Contracts |
| Polygon Amoy | Red de pruebas donde viven los contratos | Smart Contracts |
| Firebase App Distribution | Canal de testers de la app Android | Mobile Application |

Las llaves de acceso, las contraseñas y los tokens viven en variables de entorno de Dokploy y de GitHub Actions. Ninguno aparece en un repositorio ni en este informe.

##### Landing Page

1. El equipo activó GitHub Pages en el repositorio `latifi-landing` con origen en GitHub Actions.
2. El workflow `pages.yml` se ejecuta en cada push a `main`: copia solo los archivos permitidos del sitio (páginas, estilos, scripts, imágenes, `robots.txt` y `sitemap.xml`), falla si falta alguno, publica el sitio en GitHub Pages y comprueba con `curl` que la URL responde. El workflow `ci.yml` corre aparte las verificaciones de accesibilidad, SEO, i18n y contraste en cada pull request.
3. La rama `develop` recibe los cambios por pull request y solo llega a `main` mediante una rama `release/*`, con la etiqueta de versión. La landing lleva las versiones `v0.1.0` a `v0.5.1`.
4. La última ejecución de Deploy Pages sobre `main` terminó en `success`: https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-landing/actions/runs/43630621531
5. Verificación: el sitio responde `200` en https://arquitectura-de-softwares-emergentes.github.io/latifi-landing/ y muestra la versión en inglés y en español (capturas en 7.2.1.5).

##### Web Services

1. El equipo creó el registro DNS `latifi-api.juan-tech.com` en Cloudflare, en modo solo DNS, apuntando al servidor de Hetzner.
2. En Dokploy creó el proyecto `latifi`, con una base de datos PostgreSQL 17 administrada por Dokploy y la aplicación `latifi-api`, con origen en la rama `main` del repositorio, construcción con el `Dockerfile` y un dominio con HTTPS y certificado de Let's Encrypt.
3. Configuró las variables de entorno de la aplicación en Dokploy a partir de `deploy/dokploy/app.env.example`: conexión a la base de datos (`SPRING_DATASOURCE_*`), secreto de firma de los tokens de sesión (`LATIFI_JWT_SECRET`), dominio de autenticación, URL del nodo RPC de Alchemy (`LATIFI_RPC_URL`), dirección del contrato (`LATIFI_LOANBOOK_ADDRESS`), bloque de inicio del indexador (`LATIFI_INDEXER_START_BLOCK`) y Swagger habilitado (`LATIFI_SWAGGER_ENABLED`).
4. Publicó la versión `v0.2.0` con el flujo GitFlow: pull request de `feature/deployment` a `develop` (#20), rama `release/0.2.0` hacia `main` (#21) y etiqueta anotada `v0.2.0`. El workflow `publish-image.yml` construyó y publicó la imagen `ghcr.io/arquitectura-de-softwares-emergentes/latifi-api` con las etiquetas `0.2.0`, `0.2` y `latest`.
5. Dokploy construyó el commit de la etiqueta y arrancó el contenedor con el indexador de eventos embebido.
6. Verificación desde un equipo externo al servidor y sin token, registrada en [docs/evidence/live-checks.txt](docs/evidence/live-checks.txt): `GET /actuator/health` devuelve `200` con `{"status":"UP"}`, la Swagger UI responde `200` en https://latifi-api.juan-tech.com/swagger-ui/index.html y `/v3/api-docs` devuelve la versión `0.2.0` con la URL pública como servidor. Las capturas de la Swagger UI están en 7.2.1.6.

##### Mobile Application

1. El repositorio `latifi-android` ejecuta tres workflows por pull request: `ci` (lint, pruebas unitarias y compilación de la app y de las pruebas instrumentadas), `android-instrumented` (pruebas instrumentadas en un emulador) y `android-instrumented-api30` (las mismas pruebas sobre Android 11). La última ejecución sobre `develop` de los tres terminó en `success`.
2. El paquete de la aplicación es `com.latifi.wallet`, con `minSdk` 26 y `compileSdk` 37, y la conexión no custodial con la billetera usa Reown AppKit.
3. El equipo compiló la versión debug en modo Demo y la instaló en un Pixel 9a para grabar las capturas de 7.2.1.5 y los videos del prototipo de 6.5.
4. Distribuye el APK firmado a los testers con Firebase App Distribution, en el grupo `latifi-demo` del proyecto `latifi-wallet-app`, con el script `distribute.sh` y la versión 15.29.0 del CLI de Firebase fijada en el repositorio. El enlace de invitación del grupo está en [docs/evidence/deployment-facts.json](docs/evidence/deployment-facts.json) y en la landing page.

##### Smart Contracts

1. El repositorio `latifi-contracts` compila y prueba con Foundry y rechaza en CI las cadenas principales y las llaves escritas en el código (`check-testnet-only.sh`).
2. El equipo desplegó `LoanBook` y `MockStablecoin` en Polygon Amoy (chain id 80002) con la release `v0.2.0` y guardó las direcciones en `deployments/amoy.json`.
3. Verificación: `LoanBook` en https://amoy.polygonscan.com/address/0xccb8ad15a4954138c987a77924ceab468a843266 y `MockStablecoin` en la dirección `0x66757f1cc66b278bfc0eefad7e3cac1d70fd4f8b`.

##### 7.2.1.8. Team Collaboration Insights during Sprint.

El Sprint 1 empezó con el Sprint Planning del 28/10/2026 y llegó hasta el 15/11/2026. Juan Angulo desarrolló los cuatro productos digitales y las 54 tareas del Sprint Backlog 1 quedaron terminadas. Anaely Burga, Fabrizio Quiroz y Fiorella Vilca aportaron el diseño de la aplicación, la investigación de los segmentos, el Capítulo VII y las secciones de experiencia de usuario en el repositorio del informe. La tabla siguiente resume la actividad de cada repositorio.

| Repositorio | Commits en `develop` | Pull requests integrados | Contribuidores |
|---|---|---|---|
| latifi-landing | 13 | 12 | Juan Angulo (13) |
| latifi-api | 19 | 20 | Juan Angulo (19) |
| latifi-contracts | 13 | 14 | Juan Angulo (13) |
| latifi-android | 21 | 21 | Juan Angulo (21) |
| latifi-report | 79 | 10 | Juan Angulo (55), Anaely Burga (10), Fabrizio Quiroz (10), Fiorella Vilca (4) |

Cada pull request integrado equivale a un commit en `develop`. Las cifras corresponden al 15/11/2026. En el repositorio del informe, Anaely Burga subió los 45 wireframes de 6.4.1, Fabrizio Quiroz redactó el borrador del Capítulo VII, y Fiorella Vilca mantuvo el perfil del equipo y registró la entrevista del segmento prestamista.

Las capturas siguientes muestran el historial de commits de la rama `develop` de cada repositorio en GitHub, tomadas el 15/11/2026. Los analíticos de colaboración completos están en `https://github.com/Arquitectura-de-Softwares-Emergentes/<repositorio>/graphs/contributors`.

**Landing Page**

![Historial de commits de la rama develop de latifi-landing](resources/Cap7/analytics/commits-latifi-landing.png)

**Web Services (LatiFi API)**

![Historial de commits de la rama develop de latifi-api](resources/Cap7/analytics/commits-latifi-api.png)

**Smart Contracts**

![Historial de commits de la rama develop de latifi-contracts](resources/Cap7/analytics/commits-latifi-contracts.png)

**Mobile Application**

![Historial de commits de la rama develop de latifi-android](resources/Cap7/analytics/commits-latifi-android.png)

**Informe del proyecto**

![Historial de commits de la rama develop de latifi-report](resources/Cap7/analytics/commits-latifi-report.png)


### 7.3. Validation Interviews

Las entrevistas de validación ponen la landing page y la aplicación LatiFi Wallet frente a personas de los dos segmentos objetivo: el prestatario no bancarizado y el prestamista con capital ocioso. Cada persona recorre la landing, ejecuta las tareas de sus user flows y comenta en voz alta lo que entiende y lo que no. El equipo graba cada sesión con consentimiento, corrige los problemas de usabilidad que detecta y los clasifica con las heurísticas de 7.3.3. Esta sección diseña las sesiones (7.3.1), registra cada entrevista con su video (7.3.2) y evalúa el producto según heurísticas (7.3.3).

#### 7.3.1. Diseño de Entrevistas

Las entrevistas de validación buscan comprobar si los usuarios de los dos segmentos objetivo entienden la propuesta de valor de LatiFi en la landing page y si pueden completar sus tareas principales en la aplicación móvil sin ayuda. A diferencia de las entrevistas de descubrimiento del Capítulo II, en estas sesiones el entrevistado interactúa con el producto mientras expresa en voz alta lo que piensa (técnica *think aloud*), y el equipo observa dónde duda, se equivoca o abandona.

**Objetivos de la validación**

1. Verificar que la landing page comunica con claridad qué es LatiFi, para quién es y por qué es seguro.
2. Medir si los usuarios completan los user flows principales de la aplicación sin asistencia.
3. Identificar problemas de usabilidad, diseño inclusivo y arquitectura de información para la evaluación heurística (7.3.3).
4. Contrastar las hipótesis del Lean UX Canvas sobre confianza y reputación con la reacción real de los usuarios.

**Modalidad de las sesiones**

| Aspecto | Detalle |
|---|---|
| Número de entrevistas | 3 a 5 por segmento |
| Duración | 20 a 25 minutos por sesión |
| Modalidad | Virtual por Microsoft Teams, con pantalla compartida, o presencial con el teléfono del entrevistador |
| Producto evaluado | Landing page publicada en GitHub Pages y aplicación LatiFi Wallet instalada en un teléfono Android |
| Registro | Grabación en video con consentimiento del entrevistado, publicada en Microsoft Stream |
| Roles del equipo | Un entrevistador que guía la sesión y un observador que registra tiempos, errores y comentarios |
| Métrica de éxito | Tarea completada sin ayuda, tiempo empleado y número de errores |

##### Segmento 1: Prestatario no bancarizado

**Criterios de selección:** personas de 20 a 55 años que trabajan de forma independiente o tienen un pequeño negocio (comercio, delivery, transporte u oficios), que no tienen historial crediticio formal o reciben montos bajos del banco, que usan un smartphone Android y billeteras como Yape o Plin, y que no tienen experiencia previa con criptomonedas.

**Elementos a validar**

- **Landing page:** la sección principal con la propuesta de valor, el simulador de microcrédito, la sección "¿Cómo funciona?" y la sección de seguridad.
- **Aplicación:** el onboarding en lenguaje simple, la conexión de la billetera, la solicitud de un microcrédito con su resumen en moneda local, la consulta del préstamo y el pago de una cuota.

**User flows a validar**

| Tarea | User flow (6.4.4) | Criterio de éxito |
|---|---|---|
| T1. Explicar con sus palabras qué ofrece LatiFi después de recorrer la landing | n/a | Menciona préstamos entre personas sin colateral |
| T2. Ingresar a la aplicación y conectar la billetera | User Flow 1 | Llega al inicio del prestatario sin ayuda |
| T3. Solicitar un préstamo de S/ 500 a 3 cuotas | User Flow 2 | Publica la solicitud y entiende el monto de cada cuota |
| T4. Pagar la primera cuota del préstamo | User Flow 3 | Completa el pago y encuentra su reputación actualizada |

**Guion de preguntas**

*Introducción (2 minutos)*

1. ¿A qué te dedicas y cómo manejas el dinero de tu trabajo o negocio?
2. ¿Has pedido algún préstamo antes? ¿A quién y cómo te fue?

*Landing page (5 minutos)*

3. Recorre la página con calma. ¿Qué crees que ofrece LatiFi?
4. ¿Para quién crees que es este servicio? ¿Te sientes parte de ese grupo?
5. ¿Qué te daría confianza o desconfianza para usarlo?

*Aplicación (12 minutos)*

6. Realiza la tarea indicada y dime en voz alta lo que piensas mientras avanzas.
7. ¿Hubo algún paso o palabra que no entendiste?
8. Antes de confirmar la solicitud, ¿sabías cuánto pagarías en total y en cada cuota?
9. ¿Qué entiendes por "reputación" en la aplicación? ¿Cómo crees que puedes mejorarla?
10. Si una transacción fallara, ¿sabrías qué hacer con lo que muestra la pantalla?

*Cierre (3 minutos)*

11. Del 1 al 5, ¿qué tan fácil fue usar la aplicación? ¿Por qué?
12. ¿Usarías LatiFi para financiar tu negocio? ¿Qué cambiarías?
13. ¿Nos autorizas a usar un fragmento de tu opinión en el video del producto?

##### Segmento 2: Prestamista con capital ocioso

**Criterios de selección:** personas de 25 a 50 años con ingresos estables y excedentes de dinero, con estudios superiores, que ya han prestado dinero a conocidos o invierten en algún instrumento, y que usan o están dispuestas a usar una billetera digital.

**Elementos a validar**

- **Landing page:** la sección principal, la propuesta de valor para el prestamista, la sección de seguridad (modelo no custodial y reputación híbrida) y las preguntas frecuentes.
- **Aplicación:** la conexión de la billetera, el feed de solicitudes con sus filtros, el detalle de una solicitud con la reputación del prestatario, el fondeo y el portafolio.

**User flows a validar**

| Tarea | User flow (6.4.4) | Criterio de éxito |
|---|---|---|
| T1. Explicar cómo LatiFi protege su dinero después de recorrer la landing | n/a | Menciona que LatiFi no custodia los fondos y que el contrato ejecuta los pagos |
| T2. Ingresar a la aplicación como prestamista | User Flow 1 | Llega al inicio del prestamista sin ayuda |
| T3. Encontrar la solicitud con mejor reputación de 3 meses o menos | User Flow 4 | Usa los filtros y el orden por reputación |
| T4. Fondear esa solicitud y revisarla en su portafolio | User Flow 4 | Completa el fondeo y ubica la inversión en Portafolio |

**Guion de preguntas**

*Introducción (2 minutos)*

1. ¿Has prestado dinero alguna vez? ¿Cómo decidiste a quién prestarle?
2. ¿Qué haces hoy con el dinero que no usas?

*Landing page (5 minutos)*

3. Recorre la página. ¿Qué entiendes que ganarías al usar LatiFi?
4. ¿Qué te dice la página sobre la seguridad de tu dinero? ¿Es suficiente?
5. ¿Qué información te falta para animarte a probarla?

*Aplicación (12 minutos)*

6. Realiza la tarea indicada y dime en voz alta lo que piensas mientras avanzas.
7. ¿La información de reputación te basta para decidir si prestar? ¿Qué agregarías?
8. ¿Te quedó claro cuánto recibirías de vuelta y en qué plazo?
9. ¿Fue fácil encontrar y usar los filtros del feed?
10. Después de fondear, ¿sabías dónde seguir el estado de tu inversión?

*Cierre (3 minutos)*

11. Del 1 al 5, ¿qué tan fácil fue usar la aplicación? ¿Por qué?
12. ¿Pondrías dinero real en una plataforma así? ¿Bajo qué condiciones?
13. ¿Nos autorizas a usar un fragmento de tu opinión en el video del producto?

#### 7.3.2. Registro de Entrevistas

_[Por completar: de 3 a 5 entrevistas por segmento, registradas en video.]_

##### Segmento 1: _[Nombre del segmento]_

###### Entrevista 1

| Nombres y apellidos | Edad | Distrito | Video (Microsoft Stream) | Inicio | Duración |
|---|---|---|---|---|---|
| _[...]_ | _[...]_ | _[...]_ | _[URL]_ | _[mm:ss]_ | _[mm:ss]_ |

_[Screenshot de un cuadro del video]_

**Resumen:** _[Principales apreciaciones del entrevistado sobre las tareas asignadas.]_

##### Segmento 2: _[Nombre del segmento]_

###### Entrevista 1

| Nombres y apellidos | Edad | Distrito | Video (Microsoft Stream) | Inicio | Duración |
|---|---|---|---|---|---|
| _[...]_ | _[...]_ | _[...]_ | _[URL]_ | _[mm:ss]_ | _[mm:ss]_ |

_[Screenshot de un cuadro del video]_

**Resumen:** _[Principales apreciaciones del entrevistado sobre las tareas asignadas.]_

#### 7.3.3. Evaluaciones según heurísticas

**UX Heuristics & Principles Evaluation**
**Usability – Inclusive Design – Information Architecture**

| Campo | Detalle |
|---|---|
| Carrera | Ingeniería de Software |
| Curso | Arquitecturas de Software Emergentes |
| Sección | _[Código de la sección]_ |
| Profesores | _[...]_ |
| Auditor | _[Nombre del grupo que ejecuta la sesión de evaluación]_ |
| Cliente(s) | _[Nombres de las personas que participan en la sesión]_ |

**SITE o APP A EVALUAR:** _[Nombre de la app]_

**TAREAS A EVALUAR:** el alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. _[...]_
2. _[...]_

No están incluidas en esta versión de la evaluación las siguientes tareas:

1. _[...]_
2. _[...]_

**ESCALA DE SEVERIDAD:**

| Nivel | Descripción |
|---|---|
| 1 | Problema superficial: puede ser fácilmente superado por el usuario u ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2 | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja de cara al siguiente release. |
| 3 | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo. Es importante que sea corregido y se le debe asignar una prioridad alta. |
| 4 | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento. |

**TABLA RESUMEN:**

| # | Problema | Escala de severidad | Heurística / Principio violado(a) |
|---|---|---|---|
| 1 | _[...]_ | _[1-4]_ | _[Usability / Inclusive Design / Information Architecture: ...]_ |

**DESCRIPCIÓN DE PROBLEMAS:**

**PROBLEMA #1:** _[Título del problema]_

- **Severidad:** _[1-4]_
- **Heurística violada:** _[...]_
- **Problema:** _[Descripción, con captura de pantalla que ilustre el problema.]_
- **Recomendación:** _[...]_

### 7.4. Video About-the-Product

El video About-the-Product presenta LatiFi Wallet a los visitantes de la landing page y a los futuros usuarios de la aplicación. Muestra el problema que resuelve: emprendedores y trabajadores independientes que no acceden al crédito formal por falta de historial bancario, y personas con dinero ahorrado que no tienen una forma segura de prestarlo. Luego explica la propuesta de LatiFi: préstamos entre personas con reglas escritas en un smart contract, montos mostrados también en soles y una reputación que crece con cada pago puntual.

El video recorre la aplicación desde los dos roles. El prestatario conecta su billetera, solicita un préstamo y paga sus cuotas, y el prestamista revisa las solicitudes, compara la reputación de cada prestatario y fondea la que prefiere. Mantiene el mismo tono cercano y claro de la landing page y de la aplicación, sin tecnicismos, e incluye el testimonio de un usuario de las entrevistas de validación. Al final invita a descargar la aplicación desde la landing page.

<div align="center">
  <a href="https://www.youtube.com/watch?v=e3YCgq88J7c">
    <img src="https://img.youtube.com/vi/e3YCgq88J7c/maxresdefault.jpg" alt="Video About-the-Product de LatiFi Wallet" width="80%"/>
  </a>
</div>

| Elemento | Detalle                                     |
|---|---------------------------------------------|
| Video en YouTube (incrustado en la landing page) | https://www.youtube.com/watch?v=e3YCgq88J7c |
| Duración | 01:42                                       |
# Avance de Conclusiones

Con las cuatro entrevistas realizadas, tres del segmento prestatario y una del prestamista, el equipo contrasta de forma preliminar los supuestos del Capítulo I. Los tres prestatarios confirman que el crédito formal les ofrece montos bajos o les exige documentos que no tienen, y que en esos casos recurren a su familia, a juntas o a un prestamista del barrio que, en un caso, cobra cerca de 10% semanal. Eso respalda el problema de acceso al crédito formal. En el segmento prestamista, el entrevistado ya presta excedentes a conocidos con una tasa base desde el 5% mensual y ahorra en stablecoins, lo que respalda la existencia de capital ocioso dispuesto a colocarse.

Ambos segmentos coinciden en un punto que sustenta la propuesta de valor: la confianza depende de señales verificables. Los prestatarios proponen demostrar que son de fiar con pagos puntuales, calificaciones en aplicaciones de reparto o el testimonio de sus clientes y proveedores, y el prestamista exige ver préstamos anteriores y un indicador claro de cumplimiento antes de prestar a un desconocido. Los prestatarios piden además condiciones explicadas sin tecnicismos y con el costo total a la vista, y el prestamista rechaza que la plataforma custodie los fondos, lo que es coherente con la decisión de una wallet non-custodial.

Estos resultados provienen de cuatro entrevistas, por lo que no permiten generalizar. Como siguientes pasos, el equipo completará el registro de entrevistas hasta el mínimo por segmento, con prioridad en el segmento prestamista, y validará el modelo de reputación con prototipos para contrastar el resto de las hipótesis del Lean UX Canvas.

Con el Sprint 1, LatiFi pasó del diseño a un producto en funcionamiento. Los contratos `LoanBook` y `MockStablecoin` operan en Polygon Amoy, LatiFi API responde en https://latifi-api.juan-tech.com con el indexador de eventos activo, la landing page está publicada en GitHub Pages y la aplicación Android completa el ciclo de solicitud, fondeo, pago y reputación en modo Demo. Las 54 tareas del Sprint Backlog 1 quedaron terminadas. La lección principal es de organización: el siguiente sprint debe repartir la implementación entre todos los integrantes.

<div style="page-break-after: always;"></div>

# Bibliografía

- Gan@Más. (2025). *Inclusión financiera en Perú sube al 61.6% en el segundo trimestre de 2025*. https://revistaganamas.com.pe/inclusion-financiera-en-peru-sube-al-616-en-el-segundo-trimestre-de-2025/
- Gestión / INEI. (s.f.). *4 de cada 10 peruanos está fuera del sistema financiero*. https://gestion.pe/tu-dinero/4-de-cada-10-peruanos-esta-fuera-del-sistema-financiero-inei-prestamos-informales-noticia/
- World Bank Global Findex. (2025). *Financial inclusion at record high, but 1.3 billion still unbanked*. https://www.biia.com/financial-inclusion-at-record-high-but-1-3-billion-still-unbanked-world-bank-global-findex-2025-report/
- INEI. (2025). *Informalidad en Perú: Encuesta Permanente de Empleo Nacional*. https://gestion.pe/economia/informalidad-en-peru-cayo-pero-en-10-ciudades-la-situacion-fue-otra-como-entenderlo-empleo-en-peru-puestos-de-trabajo-inei-mercado-laboral-noticia/
- ComexPerú. (2024). *Mypes representaron el 99.7% de las empresas en Perú y más del 14% del PBI nacional en 2024*. Forbes Perú. https://forbes.pe/economia-y-finanzas/2025-07-16/mypes-representaron-el-997-de-las-empresas-en-peru-y-mas-del-14-del-pbi-nacional-en-2024/
- Infobae. (2025). *Perú supera el millón de usuarios de criptomonedas y escala al puesto 42 en el ranking mundial*. https://www.infobae.com/peru/2025/09/13/peru-supera-el-millon-de-usuarios-de-criptomonedas-y-escala-al-puesto-42-en-el-ranking-mundial/
- Forbes Perú. (2026). *Mercado cripto en Perú crece ante auge de las stablecoins*. https://forbes.pe/activos-digitales/2026-01-05/mercado-cripto-en-peru-crece-ante-auge-de-las-stablecoins-las-criptoapps-aumentan-sus-usuarios-y-la-banca-estudia-su-incursion/
- Gemini. (s.f.). *GFI Token & Goldfinch crypto loans without collateral*. https://www.gemini.com/cryptopedia/gfi-token-goldfinch-crypto-loans-without-collateral
- Goldfinch Foundation. (s.f.). *Emerging market opportunities*. Medium. https://medium.com/goldfinch-fi/emerging-market-opportunities-aa842c89b5e7
- DL News. (2026). *Goldfinch borrower Lend East defaults, says Warbler Labs*. https://www.dlnews.com/articles/defi/goldfinch-borrower-lend-east-defaults-says-warbler-labs/
- BitKE. (2026). *The Goldfinch case study*. https://bitcoinke.io/2026/06/the-goldfinch-case-study/
- Mad Devs. (s.f.). *DeFi case study: RociFi: Under-collateralized credit protocol on Polygon*. https://maddevs.io/case-studies/rocifi/
- CoinDesk. (2022). *RociFi Labs raises $2.7M to enable on-chain credit scoring for DeFi*. https://www.coindesk.com/business/2022/04/12/rocifi-labs-raises-27m-to-enable-on-chain-credit-scoring-for-defi
- CryptoTotem. (s.f.). *RociFi NFCS ratings*. https://cryptototem.com/rocifi-nfcs/
- Aave. (s.f.). *Credit Delegation*. Documentación oficial. https://aave.com/docs/aave-v3/guides/credit-delegation
- Messari. (s.f.). *Aave announces Credit Delegation, enabling uncollateralized lending*. https://messari.io/report/aave-announces-credit-delegation-enabling-uncollateralized-lending
- Yellow.com. (2026). *Decentralized lending 2026: Aave on-chain money markets*. https://yellow.com/research/decentralized-lending-2026-aave-on-chain-money-markets
- Driessen, V. (2010). *A successful Git branching model*. nvie.com. https://nvie.com/posts/a-successful-git-branching-model/
- Preston-Werner, T. (s.f.). *Semantic Versioning 2.0.0*. https://semver.org/
- Conventional Commits. (s.f.). *Conventional Commits 1.0.0*. https://www.conventionalcommits.org/en/v1.0.0/
- Brown, S. (s.f.). *The C4 model for visualising software architecture*. https://c4model.com/
- JetBrains. (s.f.). *Coding conventions*. Kotlin Documentation. https://kotlinlang.org/docs/coding-conventions.html
- Google. (s.f.). *Kotlin style guide*. Android Developers. https://developer.android.com/kotlin/style-guide
- Google. (s.f.). *Google Java Style Guide*. https://google.github.io/styleguide/javaguide.html
- Google. (s.f.). *Google HTML/CSS Style Guide*. https://google.github.io/styleguide/htmlcssguide.html
- Google. (s.f.). *Google JavaScript Style Guide*. https://google.github.io/styleguide/jsguide.html
- Solidity Team. (s.f.). *Style Guide*. Solidity Documentation. https://docs.soliditylang.org/en/latest/style-guide.html
- SpecFlow. (s.f.). *Gherkin conventions for readable specifications*. https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/
- Cucumber. (s.f.). *Gherkin reference*. https://cucumber.io/docs/gherkin/reference/
- OpenAPI Initiative. (2021). *OpenAPI Specification v3.0.3*. https://spec.openapis.org/oas/v3.0.3
- springdoc. (s.f.). *springdoc-openapi*. https://springdoc.org/
- Spring. (s.f.). *Spring Boot reference documentation*. https://docs.spring.io/spring-boot/
- Foundry. (s.f.). *Foundry Book*. https://getfoundry.sh/
- OpenZeppelin. (s.f.). *OpenZeppelin Contracts documentation*. https://docs.openzeppelin.com/contracts/5.x/
- Polygon Labs. (s.f.). *Polygon Amoy testnet*. Polygon Knowledge Layer. https://docs.polygon.technology/pos/
- Reown. (s.f.). *AppKit for Android*. Reown Docs. https://docs.reown.com/appkit/android/core/installation
- Google. (s.f.). *Jetpack Compose*. Android Developers. https://developer.android.com/compose
- Dokploy. (s.f.). *Dokploy documentation*. https://docs.dokploy.com/
- W3C. (2018). *Web Content Accessibility Guidelines (WCAG) 2.1*. https://www.w3.org/TR/WCAG21/
- Nielsen, J. (1994). *10 usability heuristics for user interface design*. Nielsen Norman Group. https://www.nngroup.com/articles/ten-usability-heuristics/

<div style="page-break-after: always;"></div>

# Anexos

## Anexo A. Videos de Exposiciones

| Entrega | Enlace privado en Microsoft Stream | Archivo |
|---|---|---|
| TB1 | _Pendiente de agregar: el enlace se obtiene al publicar el video de exposición en Microsoft Stream_ | upc-pre-202602-si728-2620-9046-latifi-expo-tb1.mp4 |
| TB2 | _Pendiente de agregar: el enlace se obtiene al publicar el video de exposición en Microsoft Stream_ | upc-pre-202602-si728-2620-9046-latifi-expo-tb2.mp4 |
