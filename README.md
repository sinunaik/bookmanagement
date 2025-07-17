# 📚 Book Management System

A simple RESTful Book Management System built with Spring Boot. This application allows users to perform basic CRUD (Create, Read, Update, Delete) operations on a collection of books.

---

## 🚀 Features

- 🔍 View all books
- ➕ Add a new book
- 📝 Update book details
- ❌ Delete a book
- 📦 RESTful APIs using Spring Web
- 🗃️ In-memory H2 Database
- 🧪 Unit test ready

---

## 🛠️ Tech Stack

- **Backend**: Java, Spring Boot
- **Database**: H2 (in-memory)
- **Build Tool**: Maven
- **Other Tools**: Spring Data JPA, Spring Web

---

## 📂 Project Structure

bookmanagement
├── src
│ ├── main
│ │ ├── java
│ │ │ └── com.example.bookmanagement
│ │ │ ├── controller
│ │ │ ├── entity
│ │ │ ├── repository
│ │ │ └── BookmanagementApplication.java
│ │ └── resources
│ │ └── application.properties
└── pom.xml

---

## 🔗 API Endpoints

| Method | Endpoint        | Description           |
|--------|------------------|-----------------------|
| GET    | `/books`         | Get all books         |
| GET    | `/books/{id}`    | Get a book by ID      |
| POST   | `/books`         | Add a new book        |
| PUT    | `/books/{id}`    | Update book details   |
| DELETE | `/books/{id}`    | Delete a book         |

---

## 🧪 How to Run

1. Clone the repository:

2. Open in your IDE (IntelliJ, Eclipse, etc.)
3. Run the main class:
4. Access H2 Console:
- URL: `http://localhost:8080/h2-console`
- JDBC URL: `jdbc:h2:mem:testdb`

---

## 🧾 License

This project is licensed under the MIT License.
