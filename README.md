# Sensor Register Backend

Spring Boot REST API for CRUD operations on manual laboratory readings.

## Requirements
- Java 21
- Maven 3.9+ (or use the Maven wrapper once generated)
- MySQL 8+ for local persistence

## Local setup
1. Create a database named `sensor_register`.
2. Set `DB_URL`, `DB_USERNAME`, and `DB_PASSWORD` in your environment, or edit local-only configuration.
3. Run `mvn spring-boot:run`.
4. API base path: `http://localhost:8080/api`.

The endpoint contract is described in `../docs/PROJECT_BLUEPRINT.md`. Do not commit real credentials.
