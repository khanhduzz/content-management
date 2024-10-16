# Content Management System

## Overview
This project is an Content Management System built using Spring MVC, Thymeleaf, Spring Security, and Maven. It manages employee information and their associated accounts.

## ER Model

## Use cases

## Key Features
- User authentication and authorization using Spring Security
- User-friendly interface built with Thymeleaf

## Technology Stack
- **Spring MVC**: [Spring MVC](https://spring.io/projects/spring-mvc)
- **Thymeleaf**: [Thymeleaf](https://www.thymeleaf.org/)
- **Spring Security**: [Spring Security](https://spring.io/projects/spring-security)
- **Maven**: [Apache Maven](https://maven.apache.org/)
- **H2 database**: [H2 Database](https://www.h2database.com/html/main.html)
- **CI/CD with GitHub Actions**: [GitHub Actions](https://github.com/features/actions)
- **Docker image and DockerHub**: [Docker Hub](https://hub.docker.com/)

## Project Structure
- **src/main/java**: Contains Java source code for controllers, services, repositories, entities, and other components.
- **src/main/resources**: Contains configuration files (application.properties or application.yml), templates (Thymeleaf), and other resources.
- .github/workflows: Contains configuration files for GitHub pipelines and ci-cd

## Database Setup
1. Create a database with the specified name and schema.
2. Create tables for Employee and Account entities according to your database schema.
3. Configure database connection details in application.yml.
4. Configure variable in .env file

## Running the Application
1. Clone the repository.
2. Adding a new .env file to the project folder, then configure the information base on the .env sample
3. Build the project using Maven: `mvn clean install`
4. Run the application as a Spring Boot application.

## Dependencies
Specify necessary dependencies in the `pom.xml` file, including Spring MVC, Thymeleaf, Spring Security, database driver, and other required libraries.

## Security Configuration
- Configure requests and authorization in Spring Security configuration.
- Implement authentication and authorization logic.

## CI-CD
- Pipeline for check maven build project: merge on main
- Pipeline for build docker image and push to DockerHub: merge to ci-cd branch

## Contributing
If you want to contribute to this project, please fork the repository and submit a pull request.

## License
MIT license

## Contact
Provide contact information for project inquiries or support.

---
