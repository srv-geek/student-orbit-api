# Student Orbit

## 📘 Project Overview
**Student Orbit** is a **Spring Boot REST API** project designed to streamline the process of managing student attendance in educational institutions. The system allows faculty members to efficiently record attendance for specific subjects and provides interfaces for viewing and managing these records. The project eliminates paperwork, improves accuracy, and simplifies attendance tracking.

---

## 🎯 Objectives
- **Automate Attendance Tracking:** Provide a REST API to simplify attendance management and system integration.
- **Ensure Data Accuracy:** Automate validation and ensure secure storage of attendance records to reduce errors.
- **Seamless Integration:** Integrate smoothly with educational platforms to improve faculty and administrative workflows.

---

## 📌 Scope
The **SamsTrack** project focuses on developing a REST API to manage attendance-related features for:
- **Students**
- **Subjects**
- **Faculty**
- **Attendance Records**

---

## 🛠 Tech Stack
- **Backend:** Spring Boot, Java  
- **Database:** MySQL  
- **ORM:** Hibernate (JPA)  
- **Security:** Spring Security  
- **Build Tool:** Maven  

---

## 🧭 Controllers
The project includes the following controllers:

### 1. **User Controller**
- Manages user authentication and role-based access.
- Handles user registration and login.

### 2. **Student Controller**
- CRUD operations for student management.
- Fetch student details.

### 3. **Subject Controller**
- Manage subject data and assign subjects to students.

### 4. **Student Attendance Controller**
- Mark and fetch attendance records.
- Generate student attendance reports.

---

## ⚙️ Installation and Setup

### ✅ Prerequisites
- Java 17+
- Maven
- MySQL/PostgreSQL

### 🚀 Steps
```sh
git clone https://github.com/your-repository/student-orbit.git
cd student-orbit
````

Update `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/student_orbit
spring.datasource.username=root
spring.datasource.password=yourpassword
```

Build and run the project:

```sh
mvn spring-boot:run
```

---

## 🔗 API Endpoints

| Controller               | Method | Endpoint                      | Description                  |
| ------------------------ | ------ | ----------------------------- | ---------------------------- |
| User Controller          | POST   | `/users/register`         | Register a new user          |
| User Controller          | POST   | `/users/login`            | Login user                   |
| Student Controller       | GET    | `/students`               | Get all students             |
| Student Controller       | POST   | `/students`               | Add a student                |
| Subject Controller       | GET    | `/subjects`               | Get all subjects             |
| Subject Controller       | POST   | `/subjects`               | Add a subject                |
| Student Attendance Ctrl. | POST   | `/attendance`             | Mark attendance              |
| Student Attendance Ctrl. | GET    | `/attendance/{studentId}` | Get attendance by student ID |

---

## 🤝 Contribution

Feel free to contribute by submitting pull requests or reporting issues.

---

## 📬 Contact

* **Email:** [vermashubham.srv@gmail.com](mailto:vermashubham.srv@gmail.com)
* **GitHub:** [srv-geek](https://github.com/srv-geek)



