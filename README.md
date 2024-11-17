# Products Microservice

This microservice is built to manage products as part of a scalable services project. It is implemented using **Spring Boot** and uses **PostgreSQL** as the database.

---

## Features
- **CRUD Operations** for Products:
  - Create a product
  - Retrieve product(s)
  - Update a product
  - Delete a product
- RESTful API design
- Postman collection for testing API endpoints

---

## Prerequisites
1. **Java Development Kit (JDK)**: Ensure JDK 17+ is installed.
2. **Maven**: Used to manage dependencies and build the project.
3. **PostgreSQL Database**: Ensure PostgreSQL is installed and running.

---

## Setup Instructions

### 1. Clone the Repository
git clone <your-repo-url>
cd products-microservice
mvn clean install
mvn spring-boot:run

---

## Application properties

# Application name
spring.application.name=products

# Database configuration
spring.datasource.url=jdbc:postgresql://localhost:5432/productdb
spring.datasource.username=postgres
spring.datasource.password=postgres
spring.datasource.driver-class-name=org.postgresql.Driver

# JPA and Hibernate configurations
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

# Logs SQL queries in the console
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect


----
