# CashCard API

A RESTful API for managing cash cards, built with Spring Boot.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Usage](#usage)
  - [API Endpoints](#api-endpoints)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The CashCard API is designed to manage cash cards, allowing users to perform CRUD (Create, Read, Update, Delete) operations securely and efficiently. This project was developed as a practice exercise to enhance skills in building RESTful services using the Spring Framework.

## Features

- Create, retrieve, update, and delete cash card records
- Secure endpoints with Spring Security
- In-memory H2 database for testing and development
- Comprehensive test coverage with JUnit

## Technologies Used

- Java
- Spring Boot
- Spring Web
- Spring Security
- H2 Database
- JUnit

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Java Development Kit (JDK) 8 or higher
- Gradle or Maven build tool

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AbdelrehmanElhaj/cashcard-api.git
   cd cashcard-api
   ```

2. Build the project:

   If you're using Gradle:

   ```bash
   ./gradlew build
   ```

   Or with Maven:

   ```bash
   mvn clean install
   ```

### Running the Application

Start the application using:

```bash
./gradlew bootRun
```

Or with Maven:

```bash
mvn spring-boot:run
```

The API will be accessible at `http://localhost:8080`.

## Usage

### API Endpoints

- `GET /cashcards`: Retrieve all cash cards
- `GET /cashcards/{id}`: Retrieve a specific cash card by ID
- `POST /cashcards`: Create a new cash card
- `PUT /cashcards/{id}`: Update an existing cash card
- `DELETE /cashcards/{id}`: Delete a cash card

For detailed request and response examples, refer to the API documentation or use tools like Postman to interact with the endpoints.

## Testing

Run tests using:

```bash
./gradlew test
```

Or with Maven:

```bash
mvn test
```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.

