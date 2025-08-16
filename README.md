# EMS

Event Management System backend built with Spring Boot 3, MongoDB and JWT authentication.

## Requirements

- Java 17
- Maven
- MongoDB

## Configuration

Set these environment variables before running:

| Variable | Description |
| --- | --- |
| `MONGODB_URI` | MongoDB connection string (defaults to `mongodb://localhost:27017/Event_Management_DB`) |
| `JWT_SECRET` | Base64 encoded secret used to sign JWTs |
| `MAIL_USERNAME` | SMTP username |
| `MAIL_PASSWORD` | SMTP password |

## Run

```bash
mvn spring-boot:run
```

API docs are available at `/swagger-ui.html` once the app is running.

## Test

```bash
mvn test
```
