# ✅ Spring Boot To-Do Application

A complete **To-Do List web application** built using **Spring Boot**, **Thymeleaf**, **MySQL**, and **Bootstrap**. This project demonstrates a full-stack Java web application with MVC architecture, CRUD operations, and persistent data storage.

---

## 🚀 Features

- ➕ Add new tasks via web form
- ✅ Toggle task completion status
- ❌ Delete tasks
- 🔄 Tasks saved and retrieved from MySQL database
- 🎨 Clean UI using Bootstrap
- 🧠 MVC architecture with Controller, Service, Repository, and Model layers

---

## 🛠️ Tech Stack

| Layer         | Technology                      |
|---------------|----------------------------------|
| Backend       | Spring Boot, Spring MVC, JPA     |
| Frontend      | Thymeleaf (server-side template) |
| Database      | MySQL                            |
| Styling       | Bootstrap                        |
| Tools         | Maven, Lombok, IntelliJ IDEA     |
| Java Version  | Java 17 / 21 (configurable)      |

---

## 📂 Project Structure

src/
├── main/
│ ├── java/com/todoapp/
│ │ ├── controller/ # Web Controllers
│ │ ├── service/ # Business Logic
│ │ ├── model/ # Entity/Model Classes
│ │ └── repository/ # Data Access
│ ├── resources/
│ │ ├── templates/ # Thymeleaf HTML files
│ │ └── application.properties
└── pom.xml


2️⃣ Set Up MySQL Database
- Open MySQL Workbench.
- Create a schema named todo_app.

CREATE DATABASE todo_app;


3️⃣ Configure application.properties
# src/main/resources/application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/todo_app
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect

💡 Change username/password based on your local setup.

🌐 Access the App
Visit:
http://localhost:8080/

**From here, you can:**
Add new tasks
View all existing tasks
Toggle completion status
Delete tasks
