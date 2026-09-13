# webtools-service-registry

`webtools-service-registry` is a service registry built with Spring Boot and Spring Cloud Netflix Eureka. It serves as the central discovery server for the webtools microservices ecosystem, allowing services to register themselves and discover other services dynamically.

## Tech Stack

- **Java 21**
- **Spring Boot 3.4.2**
- **Spring Cloud 2024.0.0**
- **Netflix Eureka Server**
- **Maven**

## Getting Started

### Prerequisites

- Java 21 JDK
- Maven (or use the provided `./mvnw` wrapper)

### Building the Project

To build the project and install the artifact to your local repository:

```bash
./mvnw clean install
```

### Running the Service Registry

To start the Eureka server:

```bash
./mvnw spring-boot:run
```

Once started, the Eureka dashboard is typically available at:
`http://localhost:8761`

## Project Structure

- `src/main/java`: Contains the Spring Boot application entry point.
- `src/main/resources`: Configuration files (`application.yaml`, etc.).
- `Dockerfile`: Instructions for containerizing the service registry.
- `Jenkinsfile`: CI/CD pipeline definition.
