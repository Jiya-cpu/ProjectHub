# ProjectHub — Collaborative Project Management Backend

A robust, scalable RESTful API backend for collaborative project and task management. Built with **Node.js**, **Express.js**, and **MongoDB**, this project features secure user authentication workflows, role-based access control (RBAC), and modular backend architecture.

---

## 🚀 Key Features

* **Authentication & Authorization:**
  * JWT-based authentication using Access and Refresh tokens.
  * Secure workflows for email verification and password resets.
  * Role-Based Access Control (RBAC) to protect sensitive project resources and endpoints.

* **Project & Task Management:**
  * Full CRUD operations for Projects, Tasks, Subtasks, and Team Members.
  * Hierarchical task breakdown to support collaborative team workflows.

* **Modular Backend Architecture:**
  * Strict separation of concerns with reusable Controllers, Middleware, Validators, and Mongoose Schemas.
  * Standardized error handling and clean response formatting across all endpoints.

---

## 🛠️ Tech Stack

* **Runtime:** Node.js
* **Framework:** Express.js
* **Database:** MongoDB with Mongoose ORM
* **Authentication:** JSON Web Tokens (JWT) & bcrypt
* **Code Quality:** Prettier & ESLint
