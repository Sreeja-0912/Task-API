# Task Management API

Simple Spring Boot REST API with:
- JWT Authentication
- MongoDB
- Docker
- GitHub Actions
- Unit Test
- Free Deployment Ready

## Run

```bash
mvn clean install
mvn spring-boot:run
```

## APIs

### Register
POST /auth/register

### Login
POST /auth/login

### Get Tasks
GET /tasks

### Add Task
POST /tasks