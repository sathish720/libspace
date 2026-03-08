# LibSpace - A Robust Backend for Library Operations

> LibSpace is a backend API project designed to teach the fundamentals of authentication and CRUD operations using Node.js, Express, and MongoDB. The system allows users to securely register and log in to receive a JSON Web Token (JWT). Authenticated users can then manage a digital library by adding new books, viewing the entire collection, fetching specific books by ID, updating book details, and deleting entries, ensuring that sensitive data modification is protected by secure token verification.

## 👥 Team Members

This project was collaboratively developed by:
* **Chandra Sekar G** (Team Lead)
* **Bharath H** (Member)
* **Bhuvaneswaran G** (Member)
* **Boopathi B L** (Member)

---

## 🚀 About the Project

### Key Features
* **Secure User Authentication:** User registration, secure login with password hashing, account deletion, and safe logout functionality.
* **Library Management (CRUD):** * **Create:** Add new books to the database.
  * **Read:** View a list of all available books or search for a specific book by its ID.
  * **Update:** Modify existing book details.
  * **Delete:** Remove books from the library collection.
* **Route Protection:** All library modification routes are strictly protected by JSON Web Token (JWT) verification.

---

## 🛠️ Built With

* **Node.js** - JavaScript runtime environment
* **Express.js** - Web framework for backend routing
* **MongoDB** - NoSQL Database for storing user and book collections
* **JSON Web Token (JWT)** - For secure authentication and authorization
* **Bcrypt** - For secure password hashing

---

## 💻 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Before you begin, ensure you have the following installed:
* Node.js (v14 or higher)
* npm (Node Package Manager)
* MongoDB (Local server or MongoDB Atlas URI)

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone [https://github.com/Carlous1010/libspace-api.git](https://github.com/Carlous1010/libspace-api.git)
   cd libspace-api

 * Install dependencies
   npm install

 * Configure Environment Variables
   * Create a .env file in the root directory.
   * Add the following variables (replace with your actual data):
     MONGO_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_super_secret_key

 * Run the Application
   npm start

   The server should now be running and connected to the database!
<!-- end list -->
