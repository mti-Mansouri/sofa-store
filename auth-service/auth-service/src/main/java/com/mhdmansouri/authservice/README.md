# Auth Service

This is a Spring Boot-based authentication microservice for the Sofa-Store project.

## Folders and Responsibilities

- `controller/` - Contains REST controllers like `AuthController` to handle endpoints.
- `dto/` - Contains request/response data classes, like `RegisterRequest`.
- `model/` - Contains JPA entities, like `User`.
- `repository/` - Contains Spring Data JPA interfaces for database access.
- `jwt/` - JWT utilities and filter for token verification.
- `config/` - Security configuration and password encoder setup.

## Endpoints
- `POST /auth/register` - Register a new user
