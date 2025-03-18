# Blog Project

A simple blog application built with Spring Boot, by Arotiana.

## Overview

This project is a blog application that provides a platform for creating, reading, updating, and deleting blog posts. It uses Spring Boot as the main framework and incorporates various Spring features for a robust web application.

## Technologies

- **Java 8**
- **Spring Boot 1.5.2**
- **Spring Data JPA** - For database operations
- **Spring Web** - For REST endpoints
- **Spring Security** - For authentication and authorization
- **OAuth2** - For secure API authentication
- **Thymeleaf** - For server-side HTML rendering
- **H2 Database** - In-memory database for development

## Getting Started

### Prerequisites

- JDK 1.8
- Maven 3.x

### Setup & Running

1. Clone the repository
   ```
   git clone https://github.com/arotiana/blog.git
   cd blog
   ```

2. Build the project
   ```
   mvn clean install
   ```

3. Run the application
   ```
   mvn spring-boot:run
   ```

4. Access the application at `http://localhost:8080`

## Features

- User authentication and authorization
- Create, read, update, and delete blog posts
- Responsive UI using Thymeleaf templates
- RESTful API with OAuth2 security

## Database

The application uses H2 in-memory database for development. The H2 console can be accessed at `http://localhost:8080/h2-console` with the following default configuration:

- JDBC URL: `jdbc:h2:mem:testdb`
- Username: `sa`
- Password: (empty)

## Security

The application is secured using Spring Security and OAuth2. Authentication is required for creating, updating, and deleting blog posts.

## Development

This project uses Maven for dependency management and build processes. The Spring Boot Maven plugin is configured for easy deployment.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- Arotiana - [GitHub](https://github.com/arotiana)
