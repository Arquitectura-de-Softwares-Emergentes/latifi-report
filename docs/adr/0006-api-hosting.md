# ADR-0006: API hosting on the team's Dokploy VPS

- Status: Accepted
- Date: 2026-10-29
- Deciders: Juan Angulo and the team

## Context

LatiFi API (Spring Boot, Java 21, PostgreSQL) and its embedded event indexer need a public place to run for the live demos. The course statement lists example providers, and the project owner already runs a self-hosted Dokploy instance on a Hetzner VPS.

That provider is not in the statement's example list. The acceptance comes from the project owner's decision and the course's acceptance of a VPS as a deployment target, not from the list.

## Decision

Host the API on the project owner's self-hosted Dokploy instance on a Hetzner VPS. Deploy through Dokploy's Git integration, so a merge to the deployment branch triggers a build. PostgreSQL runs on the same instance.

No migration plan and no container-portability requirement apply, because a VPS is an accepted deployment target for the course.

### Framework version note

Spring Initializr no longer offers Spring Boot 3.5.x, only 4.0.0 and later. The skeleton in Phase 1 plan 03 therefore pins the `spring-boot-starter-parent` to 3.5.16, the newest 3.5.x release on Maven Central. The open source support window of the 3.5 branch may have ended in June 2026, so security fixes for it are not guaranteed. The team has to check the Spring Boot support table before Phase 4 and decide whether to stay on 3.5.16 for the course or move to 4.x.

## Consequences

- The team owns operations: updates of the host, backups of the database and the Dokploy configuration.
- One machine hosts the demo, so a VPS outage is a demo risk. Phase 7 rehearses recovery.
- Secrets live in Dokploy environment settings and never in the repositories.
- The Spring Boot version question stays open until the Phase 4 check.

## Reversibility

Reversible. The API builds with Maven from a Git repository, so moving to another host means pointing a new deployment at the same repository and database dump.

## Source

ROADMAP decision 2 (resolved by the user on 2026-10-08).
