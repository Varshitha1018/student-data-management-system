# 🎓 Student Data Management System

A RESTful web application for managing student data, built with 
Java and Spring Boot.

---

## 📋 About The Project

Student Data Management System is a backend REST API application 
that enables full management of student records through a clean 
MVC architecture. Built using Spring Boot with MySQL database 
integration and validated using Postman.

---

## ✨ Features

- 📝 Full CRUD operations for student records
- 🏗️ MVC Architecture with clean separation of concerns
- 🗄️ MySQL database integration with Spring Data JPA
- 🔗 RESTful API endpoints
- ✅ API testing and validation with Postman
- 📦 Maven build management

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| Java | Backend language |
| Spring Boot | Web framework |
| Spring Data JPA | Database layer |
| MySQL | Database |
| Maven | Build tool |
| Postman | API testing |

---

## 📁 Project Structure

student-data-management-system/
├── src/                    # Main source code
├── controller/             # REST controllers
├── service/                # Business logic
├── repository/             # Data access layer
├── .mvn/wrapper/           # Maven wrapper
└── pom.xml                 # Project dependencies

---

## 🚀 Getting Started

### Prerequisites
- Java 17+
- MySQL
- Maven

### Installation

```bash
# Clone the repository
git clone https://github.com/Varshitha1018/student-data-management-system.git

cd student-data-management-system

# Configure database in src/main/resources/application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=root
spring.datasource.password=your_password

# Run the application
./mvnw spring-boot:run
```

### API Testing
Import the project into Postman and test the REST endpoints for:
- GET all students
- GET student by ID
- POST create student
- PUT update student
- DELETE student

---

## 👩‍💻 Author

**Varshitha Edula**  
🔗 [LinkedIn](https://www.linkedin.com/in/varshitha-edula)  
📧 varshithareddyedula@gmail.com
