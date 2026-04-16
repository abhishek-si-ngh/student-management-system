# 🎓 Student Management System (Spring Boot)

A RESTful backend application for managing student records, built using **Spring Boot**, **MySQL**, and deployed on **Render**.
This project demonstrates a complete backend workflow including API development, database integration, and cloud deployment.

---

## 🚀 Live Demo

🔗 **API Base URL**
https://student-management-system-jift.onrender.com

🔗 **Swagger UI (API Docs)**
https://student-management-system-jift.onrender.com/swagger-ui/index.html

---

## 📌 Features

* ✅ Create student records
* ✅ Retrieve all students
* ✅ Delete student by ID
* ✅ RESTful API design
* ✅ Swagger UI for API testing
* ✅ MySQL database integration (Railway)
* ✅ Cloud deployment (Render)
* 🔒 Secure configuration using environment variables

---

## 🛠️ Tech Stack

| Layer        | Technology                  |
| ------------ | --------------------------- |
| Backend      | Spring Boot (Java 17)       |
| Database     | MySQL (Railway)             |
| ORM          | Spring Data JPA (Hibernate) |
| API Docs     | Swagger (OpenAPI)           |
| Build Tool   | Maven                       |
| Deployment   | Render                      |
| Version Ctrl | Git & GitHub                |

---

## 📂 Project Structure

```bash
src/main/java/com/abhishek/student
│
├── controller        # REST Controllers
├── service           # Business Logic
├── repository        # JPA Repositories
├── model             # Entity Classes
└── StudentApplication.java

src/main/resources
└── application.properties
```

---

## ⚙️ Setup Instructions (Local)

### 1️⃣ Clone the repository

```bash
git clone https://github.com/abhishek-si-ngh/student-management-system.git
cd student-management-system
```

---

### 2️⃣ Configure environment variables

```bash
DB_URL=jdbc:mysql://localhost:3306/your_db
DB_USER=root
DB_PASS=your_password
```

---

### 3️⃣ Run the application

```bash
./mvnw spring-boot:run
```

---

### 4️⃣ Access API

* Swagger UI:
  http://localhost:8080/swagger-ui/index.html

---

## 🔗 API Endpoints

| Method | Endpoint       | Description          |
| ------ | -------------- | -------------------- |
| GET    | /students      | Get all students     |
| POST   | /students      | Create a new student |
| DELETE | /students/{id} | Delete student by ID |

---

## 🧪 Sample Request

### POST /students

```json
{
  "name": "Abhishek",
  "marks": 95
}
```

---

## 🔐 Environment Variables (Production)

```properties
spring.datasource.url=${DB_URL}
spring.datasource.username=${DB_USER}
spring.datasource.password=${DB_PASS}
```

## 🚧 Future Improvements

* 🔄 Update student API
* 🔍 Get student by ID
* ✅ Input validation
* 🔐 Authentication (JWT)
* 🌐 Frontend integration (React)

---

## 👨‍💻 Author

**Abhishek Singh**

* GitHub: https://github.com/abhishek-si-ngh

---

## ⭐ Contributing

Feel free to fork this repository and contribute!

---

## 📜 License

This project is open-source and available under the MIT License.
