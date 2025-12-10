# Spring Boot + PostgreSQL

This project is a Spring Boot application using PostgreSQL database.

## Requirements
- Java 17+
- Maven or Gradle
- PostgreSQL

## Database Configuration

Set database URL, username, and password in:
`application.properties` or `application.yml`

Example:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/demo
spring.datasource.username=postgres
spring.datasource.password=password

Run Application

./mvnw spring-boot:run

or

./gradlew bootRun

Build

./mvnw clean package


---

Endpoints examples

(coming soon)
