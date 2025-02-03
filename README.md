## 🚀 Project Overview
This project is a **Ticket Booking System** designed to strengthen backend development skills using **Java**. It follows best practices in **low-level design, object mapping, authentication, and data handling**.

## 🛠️ Technology Stack
- **Java 8+** (Utilizing Streams, Optional, Functional Interfaces)
- **Gradle** (Dependency Management)
- **IntelliJ IDEA** (IDE)
- **Jackson Library** (Object Mapping)
- **JUnit** (Testing Framework)

---

## 📌 Low-Level Design Concepts
- Focus on **class interactions and relationships**.
- Defined core **entities**: `User`, `Ticket`, and `Train`.
- Used **getters and setters** for **encapsulation**.
- Emphasis on **private attributes** for better security.

---

## 🔑 User Authentication & Data Storage
- Implemented **Login & Sign-up** system.
- Used **local JSON file** as a **temporary database** (No SQL/NoSQL integration yet).
- Applied **password hashing** to protect user credentials.

---

## 🔄 Object Mapping & Error Handling
- Used **Jackson ObjectMapper** to convert Java objects ↔ JSON.
- Handled **IOExceptions** using `try-catch` for smoother file operations.
- Explained **Java Type References** for handling generic types dynamically.

---

## 🏷️ Service Layer Implementation
- **User Booking Service**:
  - Handles **user login & authentication**.
  - Manages **ticket bookings & cancellations**.

- **Train Service**:
  - Retrieves **train schedules & availability**.
  - Connects with **User Booking Service** for reservations.

---

## 📊 Java Streams & Functional Programming
- **Streams API** used for **efficient data processing**.
- Implemented **lambda expressions** to simplify operations.
- Used **filters** for retrieving specific user/train data.

---

## ⚠️ Error Handling & Exceptions
- Implemented **try-catch blocks** to prevent runtime crashes.
- Used **Optional<> types** to avoid null pointer exceptions.
- Ensured **input validation** during authentication & booking.
