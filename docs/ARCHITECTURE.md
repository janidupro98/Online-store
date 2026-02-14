# System Architecture

## Overview
The Premium Online Store is built using a **Layered Architecture Pattern** (N-Tier), ensuring clear separation of concerns, scalability, and maintainability.

---

## 🏗️ Layer Hierarchy

### 1. Presentation Layer (Thymeleaf)
- **Responsibility:** Rendering the User Interface and capturing user input.
- **Technologies:** HTML5, modern CSS (Glassmorphism), JavaScript.
- **Key Files:** `src/main/resources/templates/*.html`

### 2. Controller Layer (REST/Web)
- **Responsibility:** Handling HTTP requests, validating input, and routing to services.
- **Key Files:** `com.store.controller.*`

### 3. Service Layer (Business Logic)
- **Responsibility:** Implementing core business rules, transaction management, and coordinating between repositories.
- **Key Files:** `com.store.service.*`

### 4. Repository Layer (Data Access)
- **Responsibility:** Interacting with the H2/MySQL database using Spring Data JPA.
- **Key Files:** `com.store.repository.*`

### 5. Domain Layer (Entities)
- **Responsibility:** Representing the database schema as Java objects.
- **Key Files:** `com.store.entity.*`

---

## 🔒 Security Architecture
- **Framework:** Spring Security
- **Authentication:** Session-based (Stateful)
- **Authorization:** Role-Based Access Control (RBAC) - `ADMIN` and `USER` roles.
- **Encoder:** BCrypt for password hashing.
- **CSRF:** Enabled on all state-changing forms.

---

## 💾 Data Strategy
- **Primary DB:** H2 In-Memory (for rapid prototyping/grading).
- **ORM:** Hibernate.
- **Initialization:** Automated via `ProductDataInitializer` to ensure grading starts with a full catalog.
