# **SpringSecurityWithOneRole**

Spring Security implemented with just one role (**"USER"**).

## **Features**
- User authentication using JWT.
- Secured endpoints with role-based access control.
- Custom JWT implementation for authentication.

## **Technologies Used**
- **Spring Boot**
- **Spring Security**
- **JWT (JSON Web Token)**
- **Oracle Database**

## **Endpoints**
| HTTP Method | Endpoint   | Description |
|------------|------------|-------------|
| POST       | `/register` | Registers a new user. |
| POST       | `/login` | Authenticates user and returns a JWT token. |
| GET        | `/product` | Accessible by users with role `USER`. |
| POST       | `/product` | Adds a new product, accessible by `USER`. |

## **Installation and Setup**
1. Clone the repository.
2. Update application.properties with necessary configurations.
3. Run the application using `mvn spring-boot:run`.
4. Use tools like **Postman** to test API endpoints.

## **Conclusion**
This project demonstrates how to implement authentication and authorization in a Spring Boot application with a single role (**USER**) using JWT.

---

