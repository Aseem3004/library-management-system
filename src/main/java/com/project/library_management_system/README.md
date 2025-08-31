# Library Management System API

This is a RESTful API for a simple library management system, developed as a portfolio project to demonstrate proficiency in Java and Spring Boot.

## 🚀 Features

* **Create:** Add a new book to the library database.
* **Retrieve:** Get a list of all books or fetch a single book by its ID.
* **Update:** Modify the details of an existing book.
* **Delete:** Remove a book from the database.

## 💻 Technologies Used

* **Java 17:** The core programming language.
* **Spring Boot 3:** The framework for building the API.
* **Spring Data JPA:** For database interaction and object-relational mapping.
* **H2 Database:** An in-memory database used for development and testing.
* **Maven:** The build automation and dependency management tool.
* **RESTful API:** The architectural style used for the web services.

## 🛠️ How to Run the Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Aseem3004/library-management-system.git](https://github.com/Aseem3004/library-management-system.git)
    ```
2.  **Open in Eclipse:** Import the project as an **Existing Maven Project**.
3.  **Run the application:** In Eclipse, right-click the `LibraryManagementSystemApplication.java` file and select **Run As > Spring Boot App**.
4.  The application will start on port `8081`.

## 📌 API Endpoints

Use a tool like Postman to test the following endpoints:

| Method | URL | Description |
| :--- | :--- | :--- |
| `POST` | `/api/books` | Creates a new book record. |
| `GET` | `/api/books` | Retrieves all books. |
| `GET` | `/api/books/{id}` | Retrieves a single book by its ID. |
| `PUT` | `/api/books/{id}` | Updates an existing book. |
| `DELETE` | `/api/books/{id}` | Deletes a book by its ID. |

---

## Author

* **Aseem Gulbarga** - [https://github.com/Aseem3004](https://github.com/Aseem3004)