# Student Management System

A web-based Student Management System developed using **Java, Spring Boot, Spring MVC, Spring Data JPA, and MySQL**. The application provides functionality to manage student records efficiently through CRUD operations, with pagination and sorting for easier data management.

## Tech Stack

- **Java** (JDK 17/21)
- **Spring Boot**
- **Spring MVC**
- **Spring Data JPA (Hibernate)**
- **Thymeleaf**
- **Spring Security**
- **MySQL**
- **Maven / Gradle**

## Features

- ✅ Student CRUD operations (Create, Read, Update, Delete)
- ✅ Server-side form validation
- ✅ Pagination and Sorting
- ✅ Login and Authorization using Spring Security
- ✅ Global Exception Handling
- ✅ DTO and Entity separation
- ✅ Responsive UI using Thymeleaf templates
- ✅ Dashboard for student management

## Key Concepts Demonstrated

- Spring Boot application development
- Dependency Injection and IoC
- MVC architecture
- Repository pattern using Spring Data JPA
- Database integration with MySQL
- Data Transfer Objects (DTOs)
- Pagination and sorting
- Form handling and validation

## Getting Started

### Prerequisites

- Java JDK 17 or 21
- MySQL Server
- Maven or Gradle
- IDE such as IntelliJ IDEA or Eclipse

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Varshit2448/Student-Management-System.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Student-Management-System
   ```

3. Create a MySQL database for the application.

4. Configure your database credentials in `application.properties`:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/student_management
   spring.datasource.username=your_username
   spring.datasource.password=your_password

   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true
   ```

5. Run the application:

   **Using Maven:**

   ```bash
   mvn spring-boot:run
   ```

   **Using Gradle:**

   ```bash
   ./gradlew bootRun
   ```

6. Open your browser and access:

   ```text
   http://localhost:8080
   ```

## Project Structure

```text
src/
 └── main/
     ├── java/
     │   └── com/example/
     │       ├── controller/
     │       ├── service/
     │       ├── repository/
     │       ├── entity/
     │       ├── dto/
     │       └── exception/
     │
     └── resources/
         ├── templates/
         ├── static/
         └── application.properties
```

*Note: Package names and folders may vary depending on the actual implementation.*

## Future Enhancements

- Student profile management
- Advanced search and filtering
- Export student records
- Role-based access control

## Author

**Mekala Varshith Reddy**

GitHub: [Varshit2448](https://github.com/Varshit2448)

---

⭐ If you find this project useful, consider giving it a star!
