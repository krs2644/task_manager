# 📝 RESTful Task Management API (Spring Boot)

A simple backend application built using Spring Boot to understand and implement RESTful APIs.  
This project demonstrates CRUD operations with a clean layered architecture and a basic UI using Thymeleaf.

---

## 🚀 Features

- Create, Read, Update, Delete (CRUD) tasks  
- RESTful API design  
- Layered architecture (Controller → Service → Repository)  
- In-memory database using H2  
- Simple UI using Thymeleaf  
- Embedded server (no external setup required)

---

## 🛠️ Tech Stack

- Java 17  
- Spring Boot  
- Spring Web  
- Spring Data JPA (Hibernate)  
- H2 Database  
- Thymeleaf  
- Maven  

---

## 📂 Project Structure
src/
┣ main/
┃ ┣ java/com/example/taskmanager/
┃ ┃ ┣ controller/
┃ ┃ ┣ service/
┃ ┃ ┣ repository/
┃ ┃ ┗ model/
┃ ┗ resources/
┃ ┣ templates/
┃ ┗ application.properties


---

## 🔗 API Endpoints

| Method | Endpoint        | Description        |
|--------|---------------|--------------------|
| GET    | /tasks        | Get all tasks      |
| GET    | /tasks/{id}   | Get task by ID     |
| POST   | /tasks        | Create new task    |
| PUT    | /tasks/{id}   | Update task        |
| DELETE | /tasks/{id}   | Delete task        |

---

## 📌 Note

This project was built for learning purposes to understand backend development concepts using Spring Boot.
