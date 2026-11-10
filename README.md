# 📓 Journal App - Backend API

A secure and scalable RESTful backend service for a personal Journaling application, built with **Java** and **Spring Boot**. It allows users to create, update, retrieve, and delete personal journal entries with user authentication and data persistence.

---

## 🚀 Tech Stack

- **Language:** Java
- **Framework:** Spring Boot (Spring Web, Spring Security, Spring Data)
- **Security:** Spring Security, OAuth2 (Google Login), Password Encoding
- **Database:** MongoDB / MySQL
- **Build Tool:** Apache Maven
- **Architecture:** Controller-Service-Repository (MVC Pattern)

---

## ✨ Features

- **User Management & Authentication:** Secure signup/login and Google OAuth2 integration.
- **Journal Entries (CRUD):** Users can create, view, update, and delete their daily journal entries.
- **Role-Based Access Control:** Separate roles for standard users and admins.
- **Data Validation & Exception Handling:** Structured HTTP response codes and clean error messages.

---

## 🛠️ API Endpoints Overview

### Public & Auth
- `POST /public/signup` — Register a new user
- `POST /public/login` — Authenticate user
- `GET /auth/google` — Google OAuth2 authentication flow

### Journal Entries
- `GET /journal` — Get all journal entries for the authenticated user
- `POST /journal` — Create a new journal entry
- `GET /journal/id/{myId}` — Get a specific journal entry by ID
- `PUT /journal/id/{myId}` — Update an existing journal entry
- `DELETE /journal/id/{myId}` — Delete a journal entry

---

## 💻 Setup & Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/arsalanali2023-sketch/journalApp.git](https://github.com/arsalanali2023-sketch/journalApp.git)
