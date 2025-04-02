Spring Security with Single Role (USER)

Introduction

This project demonstrates Spring Boot security with a single role (USER). It includes JWT authentication and authorization mechanisms.

Technologies Used

Spring Boot

Spring Security

JWT (JSON Web Token)

Java 17+

Features

User authentication using JWT

Secured API endpoints

Role-based access control

Endpoints

Method

Endpoint

Description

POST

/register

Register a new user

POST

/login

Authenticate user and generate JWT

GET

/product

Access products (Requires USER role)

POST

/product

Add new product (Requires USER role)

Security Implementation

JWT Generation: The JwtService generates tokens for authentication.

Authentication Filter: JwtAuthenticationFilter validates and processes JWTs.

Security Configuration: Configured in SecurityConfig using SecurityFilterChain.

Conclusion

This project is a simple demonstration of Spring Security with JWT authentication for a single role (USER). It ensures secured access to API endpoints based on user roles.
