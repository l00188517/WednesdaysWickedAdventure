# WednesdaysWickedAdventure
# Event Booking System - Spring Boot & MongoDB.

This project is a comprehensive event booking system built using Spring Boot and MongoDB. 
It provides a RESTful API for programmatic access. 
It uses MongoDB as the database.


## Overview

The Event Booking System allows users to manage events and bookings efficiently. Key features include event creation, modification, and deletion, as well as booking ticket reservations, updates, and cancellations. The system ensures data integrity and provides a seamless user experience.


## Features

-   **Event Management:**
    -   Create, read, update, and delete events.
    -   Create new events with details like name, date/time, and available tickets.
    -   View a list of all events with their details.
    -   Edit existing event information.
    -   Delete events.
-   **Booking Management:**
    -   Create, read, update, and delete bookings.
    -   View a list of all bookings.
    -   Book tickets for specific events.
    -   Check for available tickets before booking.
    -   Edit booking details, such as the number of tickets.
    -   Cancel bookings.
-   **RESTful API:**
    -   Provides endpoints for all event and booking operations.
    -   Supports JSON data format for requests and responses.
-   **MongoDB Integration:**
    -   Uses MongoDB for data storage, providing scalability and flexibility.
-   **Validation:**
    -   Implements data validation to ensure data integrity.

## Technologies Used

-   **Spring Boot:** Framework for building Java applications.
-   **Spring Data MongoDB:** For MongoDB integration.
-   **MongoDB:** NoSQL database.
-   **Java 17+:** Programming language.
-   **Maven/Gradle:** Build tools.
-   **JUnit & Mockito:** Testing and mocking objects.
-   **Sonarlint & Eclipse:** code Quality Check and Tests Coverage.
-   **Swagger:** RESTFul Endpoints UI.
-   **Sping Actuator:** for Monitoring.

## Prerequisites

-   Java 17 (or higher)
-   Maven or Gradle
-   MongoDB installed and running

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone [repository URL]
    cd [project directory]
    ```

2.  **Configure MongoDB:**

    -   Ensure MongoDB is running.
    -   Update the `application.properties` file with your MongoDB connection details.

    ```properties
    spring.data.mongodb.uri=mongodb://localhost:27017/eventbooking
    ```

3.  **Build the project:**

    -   **Maven:**

        ```bash
        ./mvnw clean install
        ```

4.  **Run the application:**

    -   **Maven:**

        ```bash
        ./mvnw spring-boot:run
        ```

5.  **Access the application:**

    -   **REST API:** Use a REST client (e.g., Postman, curl) to access the API endpoints.

## API Endpoints

-   `/v1/bookings/{id}` (DELETE)
-   `/v1/bookings/{id}` (GET)
-   `/v1/bookings` (GET)
-   `/v1/bookings` (POST)
-   `/v1/bookings/{id}` (PUT)

-   `/v1/events/{id}` (DELETE)
-   `/v1/events/{id}` (GET)
-   `/v1/events` (GET)
-   `/v1/events` (POST)
-   `/v1/events/{id}` (PUT)

## Application Properties

-   `spring.data.mongodb.uri`: MongoDB connection URI.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or create issues.

## License

This project is licensed under the Apache 2.0 Licence.
