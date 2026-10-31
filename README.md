# dbase

Empty Spring Boot 2.0 project (Java 8) with Data JPA, Data REST and Web starters. It contains only the application class and no entities or configuration. The class is named `sadasdDatabaseApplication` while `main` refers to `DatabaseApplication`, so it does not compile as-is.

## Build
```bash
./mvnw spring-boot:run
```
A datasource must be configured in `src/main/resources/application.properties`.
