# CLAUDE.md - webtools-service-registry

## Build and Run Commands
- Build: `./mvnw clean install`
- Run: `./mvnw spring-boot:run`
- Test: `./mvnw test`
- Package: `./mvnw package`

## Coding Guidelines
- **Language**: Java 21
- **Framework**: Spring Boot 3.4.2, Spring Cloud 2024.0.0
- **Style**: 
  - Follow standard Spring Boot project structure.
  - Use descriptive variable and method names.
  - Ensure all new features are covered by unit tests.
- **Configuration**: 
  - Primary configuration in `src/main/resources/application.yaml`.
  - Environment-specific overrides in `application-public.yaml` and `application-private.yaml`.

## Project Context
- This project is a Netflix Eureka Server used for service discovery in the `webtools` microservices architecture.
- It allows other `webtools` services to register and locate each other without hardcoding network locations.
