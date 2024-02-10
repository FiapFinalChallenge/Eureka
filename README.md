# Eureka Microservice

This project is a Spring Cloud Eureka service discovery server.

## Prerequisites

* Java 17 or later
* Maven or Gradle
* Docker

## Building the Project

1. Clone this repository.
2. Navigate to the project directory:
   ```bash
   cd eureka
   ```

3. Build the project with Maven:
   ```bash
   mvn clean install
   ```

## Running with Docker

1. Build the Docker image:
   ```bash
   docker build -t my-eureka-server .
   ```

2.  Run the Docker container:
   ```bash
   docker run -p 8761:8761 -d my-eureka-server 
   ```

* Access the Eureka dashboard at: http://localhost:8761