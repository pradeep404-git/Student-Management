# Student Management

Simple Spring Boot CRUD backend with exactly 4 APIs.

## Run

```bash
mvn spring-boot:run
```

Application:
http://localhost:8080

## APIs

### Create student
POST /students

```json
{
  "name": "Pradeep",
  "email": "pradeep@gmail.com",
  "age": 22,
  "course": "Java"
}
```

### Get all students
GET /students

### Update student
PUT /students/{id}

```json
{
  "name": "Pradeep Sankonatti",
  "email": "pradeep@gmail.com",
  "age": 23,
  "course": "Spring Boot"
}
```

### Delete student
DELETE /students/{id}
