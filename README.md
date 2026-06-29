# Task Manager REST API

A Spring Boot REST API for managing tasks with full CRUD operations.

## Tech Stack
- Java 21, Spring Boot 3.5, Spring Data JPA, H2 Database, Maven

## How to Run
```
./mvnw spring-boot:run
```

## API Endpoints
| Method | URL | Description |
|--------|-----|-------------|
| GET | /api/tasks | List all tasks |
| GET | /api/tasks/{id} | Get task by ID |
| POST | /api/tasks | Create a task |
| PUT | /api/tasks/{id} | Update a task |
| DELETE | /api/tasks/{id} | Delete a task |