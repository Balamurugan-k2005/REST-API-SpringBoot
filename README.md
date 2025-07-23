# 🧾 Task Manager REST API - Spring Boot

This is a backend REST API built using **Spring Boot** for managing daily tasks. It provides full CRUD operations and connects with a MySQL database. You can integrate this backend with a React frontend or use it independently with tools like Postman.

---

## 📌 Features

- Create a task
- View all tasks
- Update existing tasks
- Delete tasks
- Connects to MySQL using Spring Data JPA
- Easily integratable with any frontend (React recommended)

---

## ⚙ Technologies Used

- Java 21
- Spring Boot 3.5.3
- Spring Data JPA
- MySQL
- Maven
- Lombok

---

## 🛠 How to Run the Project

### 🔧 Prerequisites

- Java 17 or above
- Maven
- MySQL Server running locally

### ⚙️ Configuration - `application.properties`

```properties
spring.application.name=task-manager
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url=jdbc:mysql://localhost:3306/task_db
spring.datasource.username=root
spring.datasource.password=root123
spring.jpa.show-sql=true
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
