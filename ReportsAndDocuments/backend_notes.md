# Backend Development Notes – Insecure by Design

## Overview
This document summarizes the backend planning and early setup work completed for the “Insecure by Design” Spring Boot MVC application. It outlines the structure, configuration, and upcoming implementation tasks for backend vulnerabilities.

---

## 1. Project Structure (Initial Setup)

The backend follows a standard Spring Boot MVC layered architecture:

- **Controller Layer** – Handles incoming HTTP requests  
- **Service Layer** – Contains business logic  
- **Repository Layer** – Manages database interactions using Spring Data JPA  
- **Model Layer** – Represents application entities  

Initial folders created: /controller /service /repository /model

Basic placeholder classes have been added to prepare for vulnerability implementation.

---

## 2. Database Configuration

### **H2 Database Setup**
- Configured in `application.properties`
- Verified successful connection during application startup
- Tested basic routing and database initialization

Example configuration:

spring.datasource.url=jdbc:h2:mem:testdb 
spring.datasource.driverClassName=org.h2.Driver 
spring.jpa.hibernate.ddl-auto=create


---

## 3. Planned Vulnerability Implementations (Backend)

### **SQL Injection**
**Location:** Login or search functionality  
**Approach:**  
- Use insecure string concatenation in repository queries  
- Demonstrate how malicious input manipulates SQL logic  

### **Broken Authentication**
**Location:** Login controller and session handling  
**Approach:**  
- Weak password validation  
- Missing session checks  
- Hardcoded credentials for demonstration  

### **Insecure Direct Object Reference (IDOR)**
**Location:** Profile or user resource endpoints  
**Approach:**  
- Expose predictable user IDs  
- Skip authorization checks  

---

## 4. Backend Tasks Completed So Far
- Created initial Spring Boot project skeleton  
- Added controller, service, and repository placeholders  
- Configured H2 database and verified connectivity  
- Tested application startup and routing  
- Reviewed SQL Injection patterns for Java applications  
- Prepared notes for upcoming vulnerability implementation  

---

## 5. Next Steps
- Implement SQL Injection vulnerability in the login or search feature  
- Add insecure authentication logic for Broken Auth  
- Create user entity and repository for IDOR demonstration  
- Connect backend logic to frontend templates once available  

---

## Notes
This document will be updated as backend vulnerabilities are implemented and tested.