# Fruits Logistics Backend

Spring Boot REST API for Java 21. Initialize PostgreSQL using the `database` repository before checking database health. Set `DB_PASSWORD` to the local database password. `DB_USER` defaults to `fruits_logistics` and `DB_URL` defaults to `jdbc:postgresql://localhost:5432/fruits_logistics`.

```powershell
.\mvnw.cmd verify
.\mvnw.cmd spring-boot:run
```

On macOS/Linux, use `./mvnw` instead. Request `GET http://localhost:8080/api/health` to check API and database availability. The database baseline is managed separately.
