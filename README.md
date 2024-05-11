# Spring Boot Product API

This is a CRUD (Create, Read, Update, Delete) API for managing products, built with Spring Boot and PostgreSQL.

## Prerequisites

- Java 8 or higher
- Maven
- PostgreSQL

## Built With

- Spring Boot
- PostgreSQL
- Maven
- Hibernate

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:

   ```sh
   git clone <repository-url> 
   ```

2. Navigate to the project directory:

    ```sh
    cd <project-directory> 
    ```
    
3. Update the database connection configuration in application.properties:

    ```sh
    spring.datasource.url=jdbc:postgresql://localhost:5432/products-api
    spring.datasource.username=USER_NAME
    spring.datasource.password=USER_PASSWORD
    spring.jpa.hibernate.ddl-auto=update
    spring.jpa.properties.hibernate.jdbc.lob.non_contextual_creation=true
    ```

4. Build the project:
    ```sh
    mvn clean install
    ```
5. Run the application:
    ```sh
    java -jar target/<project-name>.jar
    ```
## API Endpoints

- POST/products
- GET/products
- GET/products/{id}
- PUT/products/{id}
- DELETE/products/{id}


##### Replace `<repository-url>`, `<project-directory>`, `<project-name>`, with appropriate values.
##### Make sure to have Java, Maven, and PostgreSQL installed before running the project. You can configure the database connection details in `application.properties`.

