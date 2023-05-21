# Eco-Exchange Backend

This repository contains the backend code for the Eco-Exchange application, developed using Spring Boot and MySQL.

## Development Plan

The backend development plan is divided into several phases, which include setting up the environment, developing core functionality, connecting with the frontend, and testing & debugging. 

### Getting Started

#### Prerequisites

- Java 17
- Maven
- MySQL

#### Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/eco-exchange-backend.git
    cd eco-exchange-backend
    ```

2. Update the `application.properties` file with your database credentials.

3. Build the project:

    ```bash
    mvn clean install
    ```

4. Run the application:

    ```bash
    mvn spring-boot:run
    ```

The application will start running at `http://localhost:8080`.

### API Endpoints

(List all the endpoints of your application here, with a brief explanation of their functionalities)

### Testing

Unit tests can be run with:

    ```bash
    mvn test
    ```

### Deployment

1. Build the project:

    ```bash
    mvn clean install
    ```

2. The generated JAR file can be deployed on the cloud service provider of your choice.

### Contributing

Explain how to contribute to your project, if applicable.
