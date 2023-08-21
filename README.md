# Library Management RESTful API

A simple RESTful API developed using Spring Boot for managing a library. This API allows users to perform CRUD operations on books. Built with Spring Data JPA for database operations and Spring Security for basic authentication.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [License](#license)
- [Contact](#contact)

## Getting Started

### Prerequisites

- Java JDK 8 or higher
- Maven
- A SQL database (H2 used for simplicity in this example)

### Installation

1. Clone the repository:
\```bash
git clone https://github.com/yourusername/library-management-api.git
\```

2. Navigate to the project directory:
\```bash
cd library-management-api
\```

3. Build the project using Maven:
\```bash
mvn clean install
\```

4. Run the application:
\```bash
mvn spring-boot:run
\```

## Usage

Once the application is running, you can access the API at `http://localhost:8080/api/books`.

## API Endpoints

- **GET** `/api/books` - Retrieve all books
- **GET** `/api/books/{id}` - Retrieve a book by its ID
- **POST** `/api/books` - Add a new book (provide book data in request body)
- **DELETE** `/api/books/{id}` - Delete a book by its ID

Example Request for adding a book:
\```json
{
  "title": "Example Book",
  "author": "John Doe"
}
\```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

Your Name - your.email@example.com
