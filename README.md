# FitTrack – Personal Fitness Tracker

FitTrack is a web-based fitness tracking application developed using **Java, Spring Boot, and MySQL**. It helps users manage their fitness activities and keep track of their workout routines through a simple and user-friendly interface.

 Features

- **User Registration:** Create a new account.
- **User Login:** Secure authentication using JWT.
- **Workout Management:** Add, view, update, and delete workout records.
- **Dashboard:** View workout information and fitness statistics.
- **REST APIs:** Backend functionality implemented using Spring Boot.
- **Database Integration:** Store user and workout information using MySQL.

## 🛠️ Tech Stack

**Backend**
- Java
- Spring Boot
- Spring Security
- JWT Authentication
- Spring Data JPA
- Hibernate

**Database**
- MySQL

**Frontend**
- HTML
- CSS
- JavaScript

**Tools**
- Spring Tool Suite (STS)
- Maven
- Git & GitHub
- Postman

Project Structure

```text
FitTrack/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── com/Vaibhav/fittrack/
│       │       ├── controller/
│       │       ├── service/
│       │       ├── repository/
│       │       ├── entity/
│       │       ├── dto/
│       │       └── security/
│       │
│       └── resources/
│           ├── static/
│           │   ├── index.html
│           │   ├── style.css
│           │   └── script.js
│           │
│           └── application.properties
│
├── pom.xml
└── README.md
```

 Getting Started

 Prerequisites

Make sure you have installed:

- Java JDK 17 or compatible project version
- MySQL
- Maven
- Spring Tool Suite (STS) or any Java IDE

Clone the Repository

```bash
git clone https://github.com/vaibhavv110/FitTrackerapp.git
```

### 2. Open the Project

Import the project into Spring Tool Suite as an existing Maven project.

### 3. Configure MySQL

Create a database in MySQL:

```sql
CREATE DATABASE fittrack;
```

Update your `application.properties` with your MySQL credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/fittrack
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
```

### 4. Run the Application

Run the main Spring Boot application class from STS.

Alternatively, use Maven:

```bash
mvn spring-boot:run
```

### 5. Open the Application

Visit:

```text
http://localhost:8080
```

 Authentication

FitTrack uses JWT-based authentication to secure user access to protected resources.

Users can register, log in, and access authenticated application functionality.

## 🔮 Future Enhancements

- Workout history and progress tracking
- Personalized fitness goals
- Improved workout analytics
- Deployment to a cloud platform

 Author

**Vaibhav Vimal**

GitHub: https://github.com/vaibhavv110

---

⭐ If you find this project useful, feel free to explore the repository.
