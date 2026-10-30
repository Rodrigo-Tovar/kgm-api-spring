# kgm-api-spring

## Requisitos

- JDK 21 o superior
- No es necesario instalar Maven: usa el wrapper incluido (`mvnw` / `mvnw.cmd`)

## Comandos

```bash
# Compilar y ejecutar pruebas
./mvnw verify          # Windows: mvnw.cmd verify

# Ejecutar la aplicación (http://localhost:8080)
./mvnw spring-boot:run

# Healthcheck
curl http://localhost:8080/actuator/health
```
API en springboot para el proyecto kgm
