# CHORN Java Spring Boot Development

This CHORN's repository project aims to explore the latest significant improvements in OpenJDK v21 and the Spring Boot
framework.

## Prerequisites

* JDK 21 installed
* Spring Boot 3.x installed

## Running

```
./mvnw spring-boot:run
```

## End Point Testing: `http://localhost:8080`

```
GET /

GET /hello?name=John

POST /users
{
    "name": "John",
    "email": "john@email.com",
    "age": 21
}

GET /users
```