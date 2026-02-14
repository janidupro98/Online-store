# Premium Online Store  
**Enterprise-Grade E-Commerce Application**  

A high-end, scalable E-commerce system built using Spring Boot, Thymeleaf, and modern UI technologies.  
Designed with a Layered Architecture and structured for a 10-member collaborative development team.

---

## 🎯 Goal & Originality
Build a unique, production-style web application that solves real-world e-commerce workflows. This project goes beyond basic CRUD by implementing advanced security, state management, and specialized "Beyond CRUD" features.

## 🚀 "Beyond CRUD" Features (Selected)
We have selected and implemented the following features to exceed standard requirements:
1.  **File Uploads:** Dynamic product image uploads with server-side validation and storage.
2.  **Advanced Search & Filtering:** Multi-criteria search (keyword, price, category) for product discovery.
3.  **Audit Trail & Reporting:** Structured order history and sales metrics for administrators.
4.  **Global Error Handling:** Centralized exception handling with custom UI for 404, 403, and 500 status codes.

---

## 🏗️ Project Structure & Team Assignments
The project is divided into 4 Phases and 10 Independent Modules. Each member works within their own dedicated folder.

### **Phase 1: Infrastructure & Security**
*   **Member 01: Setup & Infrastructure** (`Member_01_Setup_Infra`)
    *   Architecture design, lead Maven configuration, and core project settings.
*   **Member 02: Backend Security** (`Member_02_Security_Back-end`)
    *   Spring Security, Authentication, RBAC (Role-Based Access Control), and Session management.
*   **Member 03: User Management UI** (`Member_03_Auth_Frontend`)
    *   Premium Login and Registration interfaces with animated backgrounds and modern UX.

### **Phase 2: Product & Catalog**
*   **Member 04: Product Backend** (`Member_04_Product_Back-end`)
    *   JPA Entities, Service layer, and high-performance Repository operations.
*   **Member 05: Product Frontend** (`Member_05_Product_Frontend`)
    *   Dynamic Product Grid, Detail views, and luxury-themed UI layouts.

### **Phase 3: Commerce & Search**
*   **Member 06: Shopping Cart** (`Member_06_Shopping_Cart`)
    *   Session-based cart logic, real-time quantity updates, and persistent state handling.
*   **Member 07: Orders & Checkout** (`Member_07_Orders_Check-out`)
    *   Transactional checkout flow, Order generation, and billing systems.
*   **Member 08: Search & Uploads** (`Member_08_Search_Uploads`)
    *   Search prioritization, image processing, and persistent data initialization.

### **Phase 4: Analytics & Reliability**
*   **Member 09: QA & Validation** (`Member_09_Validation_QA`)
    *   Global Exception Handling, Bean Validation (@Valid), and Custom Error Pages.
*   **Member 10: Reporting & Notifications** (`Member_10_Reporting_Notifications`)
    *   Sales reporting system, dashboard analytics, and notification placeholders.

---

## 🛠️ Technical Stack
*   **Backend:** Spring Boot (Controller -> Service -> Repository -> Entity)
*   **Database:** H2 (Development) / MySQL (Production) via Spring Data JPA
*   **Security:** Spring Security (Sessions/Cookies, CSRF Protection)
*   **Frontend:** Thymeleaf, Vanilla CSS (Glassmorphism), JavaScript
*   **Validation:** Bean Validation (Hibernate Validator)

## 📋 Non-Functional Requirements
*   **Security:** Password encryption using BCrypt and protection against common vulnerabilities.
*   **Reliability:** Graceful handling of edge cases (unauthorized access, missing resources).
*   **Performance:** Optimized database queries and efficient static resource handling.
*   **Code Quality:** Strictly typed entities, clear package naming, and modular separation.

---

## 🏁 Submission Package
- [x] GitHub repository with clear, descriptive commit history.
- [x] Comprehensive README.md (This file).
- [x] Postman Collection (In `/docs` folder).
- [x] Modularized project structure for 10 developers.

## 💻 How to Run
1.  **Clone the repository.**
2.  **Navigate to a member's module:** `cd Member_XX_FolderName`
3.  **Run with Maven:** `./mvnw spring-boot:run`
4.  **Access:** `http://localhost:8080` (Admin: `admin@store.com` / `password123`)

---
**Built with Precision. Designed for Scale. Engineered for Excellence.**
