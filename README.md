# Project Name: TodoList

## Overview

TodoList is a task management application built with Spring Boot, allowing you to easily manage your tasks and to-dos. This README provides information on how to set up and use the application.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Java 17
- Maven
- Your favorite Java IDE (e.g., VSCode, IntelliJ IDEA, Eclipse)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/giovanniclopes/todolist.git
   ```

2. Navigate to the project directory:

   ```bash
   cd todolist
   ```

3. Build and run the application:

   ```bash
   mvn spring-boot:run
   ```

4. Open a web browser and go to [http://localhost:8080](http://localhost:8080) to access the TodoList application.

## Features

- Create, update, and delete tasks
- Mark tasks as completed
- User authentication and authorization
- Secure password hashing with bcrypt
- In-memory H2 database for easy testing
- Swagger API documentation

## Technologies Used

- [Spring Boot](https://spring.io/projects/spring-boot) - Framework for building Java applications
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa) - Simplified data access using the JPA specification
- [H2 Database](https://www.h2database.com/html/main.html) - In-memory database
- [Bcrypt](https://github.com/patrickfav/bcrypt) - Password hashing library
- [Lombok](https://projectlombok.org/) - Reducing boilerplate code in Java
- [Swagger](https://swagger.io/) - API documentation

## Contributing

We welcome contributions from the community! If you'd like to contribute to TodoList, please follow these steps:

1. Fork the project.
2. Create your feature branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Create a pull request.