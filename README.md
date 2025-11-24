# 🚀 Job Management System – Backend API

A secure **RESTful API** for managing job applications. Users can **register, log in**, and manage their job records with full **CRUD operations**. Each job is linked to the authenticated user for **data privacy** and secure access control.

---

## 🔐 Features
- **JWT Authentication** for secured APIs  
- **Hashed passwords** using bcrypt  
- **Create, Read, Update, Delete** job entries  
- **Job status tracking** (pending, interview, declined)  
- Jobs scoped to authenticated users only  
- Built with **MongoDB + Mongoose**

---

## 🛠️ Tech Stack
- **Node.js**
- **Express.js**
- **MongoDB (Mongoose)**
- **JWT**
- **HTTP Status Code-based responses**

---

## 📌 API Endpoints

| Method | Endpoint        | Description |
|--------|----------------|-------------|
| POST   | `/auth/register` | Create a user account |
| POST   | `/auth/login`    | Authenticate & receive token |
| GET    | `/jobs`          | List all jobs of logged-in user |
| POST   | `/jobs`          | Create a new job |
| GET    | `/jobs/:id`      | Fetch job details |
| PATCH  | `/jobs/:id`      | Update an existing job |
| DELETE | `/jobs/:id`      | Delete a job |

---

## ⚙️ Setup & Installation

1. Clone the repository  
   ```sh
   git clone <repository-url>
   cd job-management-system
