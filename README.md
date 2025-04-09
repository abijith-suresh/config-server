# Config Server

A centralized configuration server for managing Spring Boot microservice configurations.

## Overview

The **config-server** provides externalized configuration for distributed services by serving config files from a central location (e.g., Git repository or local file system). It is discoverable via Eureka and can be cloned into new projects for quick integration with a Spring Cloud-based system.

## Tech Stack

- **Java:** 21
- **Spring Boot:** 3.4.4
- **Spring Cloud Config Server**
- **Spring Cloud Eureka Client**
- **Gradle (Kotlin DSL)**

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/config-server.git
   
2. **Navigate to the project:**

    ```bash
    cd config-server
   
3. **Update the Git URI or native file path** in src/main/resources/application.yml to match your config source.

4. **Run the application:**

    ```bash
    ./gradlew bootRun

5. **Access the config endpoint:**

    http://localhost:8888/{application}/{profile}

## License

This project is licensed under the MIT License.
