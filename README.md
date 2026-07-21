# 🛒 Electronic Store

A full-stack Electronic Store application built using **Spring Boot**, **Spring Security**, **Spring Data JPA**, **MySQL**, and **JWT Authentication**. This project provides a complete e-commerce backend with user authentication, product management, category management, cart functionality, order processing, and image upload support.

---

## 🚀 Features

- User Registration & Login
- JWT Authentication & Authorization
- Spring Security Integration
- Product Management (CRUD)
- Category Management
- Shopping Cart
- Order Management
- Product Image Upload
- Pagination & Sorting
- Search Products
- REST APIs
- Exception Handling
- Validation
- MySQL Database Integration
- Docker Support

---

## 🛠️ Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring Security
- Spring Data JPA (Hibernate)
- JWT Authentication
- Maven

### Database
- MySQL

### Tools
- IntelliJ IDEA / Eclipse
- Postman
- Git
- GitHub
- Docker

---

## 📂 Project Structure

```
ElectronicStore
│── src
│   ├── main
│   │   ├── java
│   │   ├── resources
│   ├── test
│── images
│── pom.xml
│── Dockerfile
│── docker-compose.yml
```

---

## ⚙️ Getting Started

### Clone Repository

```bash
git clone https://github.com/kuldeepdev09/ElectronicStore.git
```

### Go to Project

```bash
cd ElectronicStore
```

### Configure Database

Update your database configuration in:

```
src/main/resources/application.properties
```

Example:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/electro_test
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD
```

### Build Project

```bash
mvn clean install
```

### Run Application

```bash
mvn spring-boot:run
```

---

## 📡 API Features

- Authentication APIs
- User APIs
- Category APIs
- Product APIs
- Cart APIs
- Order APIs
- Image Upload APIs

---

## 🔐 Security

- JWT Authentication
- Password Encryption (BCrypt)
- Role-Based Authorization
- Spring Security

---

## 🐳 Docker

Run using Docker Compose

```bash
docker-compose up
```

---

## 📸 Screenshots

Add screenshots of:

- Login API
- User Registration
- Product APIs
- Categories
- Cart
- Orders
- Swagger / Postman

---

## 👨‍💻 Author

**Kuldeep Sharma**

GitHub:
https://github.com/kuldeepdev09

---

## ⭐ Support

If you like this project, don't forget to ⭐ the repository.
