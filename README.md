# 🎓 Student Management REST API

A RESTful API built with Java Spring Boot and PostgreSQL.
Performs full CRUD operations on student records.

## Tech Stack
- Java 21
- Spring Boot 3.5.14
- Spring Data JPA
- PostgreSQL 16
- Maven
- Lombok

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/students | Get all students |
| GET | /api/students/{id} | Get student by ID |
| POST | /api/students | Add new student |
| PUT | /api/students/{id} | Update student |
| DELETE | /api/students/{id} | Delete student |

## Sample Request (POST)
```json
{
    "name": "Ahmed Ali",
    "email": "ahmed@gmail.com",
    "course": "Computer Science",
    "marks": 85.5
}
```

## How to Run
1. Clone this repository
2. Create PostgreSQL database named `studentdb`
3. Copy `application.properties.example` to `application.properties`
4. Update database credentials
5. Run: `mvn spring-boot:run`
6. API runs on `http://localhost:8080`

## What I Learned
- REST API design with Spring Boot
- PostgreSQL database integration with JPA
- CRUD operations with Spring Data
- API testing with Thunder Client
