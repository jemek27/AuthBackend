# AuthBackend

**AuthBackend** is a backend authentication and authorization service designed to provide secure access control for applications. Built with Java and Spring Boot,
it offers robust features for managing user authentication, authorization, and related services.

## Features

- **User Authentication**: Secure login and registration functionalities.
- **Role-Based Authorization**: Assign roles to users to control access to different parts of the application.
- **Token-Based Security**: Implements JWT (JSON Web Tokens) for stateless authentication.
- **RESTful API**: Provides a set of RESTful endpoints for integration with frontend applications.
- **Docker Support**: Easily deployable using Docker and Docker Compose.

## Technologies Used

- **Java 17**: Core programming language.
- **Spring Boot**: Framework for building the application.
- **Spring Security**: Handles authentication and authorization.
- **JWT (JSON Web Tokens)**: For secure token-based authentication.
- **Docker**: Containerization of the application.
- **Maven**: Build and dependency management.

## How to Run

1. Clone the repository:  
   ```sh
   git clone https://github.com/jemek27/AuthBackend.git
   cd AuthBackend
2. Use Docker Compose to run all services
   ```sh
   docker-compose up --build -d
