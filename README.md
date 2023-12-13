# Student Management System

## Overview

Student Management System allows user to manage 
disciplines, classrooms, students and their grades.

## Features

- User can manage disciplines
- User can manage classrooms
- User can manage students
- User can manage grades

## Technologies
- Java
- Swing
- JDBC
- SQLite

## Getting Started

### Prerequisites

* Java 17+

### Installing

Clone the project

```bash
  git clone https://github.com/AugustoRavazoli/student-management-system.git
```

Go to the project directory

```bash
  cd student-management-system
```

Start the application

```bash
  ./gradlew run --args="developmentMode databaseName"
```

Where `developmentMode` should be `DEV` or `PROD` and `databaseName` should be a custom file name.

### Tests

The application has some integration tests, use the following command to run them.

```bash
  ./gradlew test
```

## License

This project is unlicensed and all rights are reserved to its owners.
