# CRUD_Operation
# CRUD_Operation

# CRUD Operation - User Management Application

This project is a simple **CRUD (Create, Read, Update, Delete)** application built using the **MERN stack** (MongoDB, Express.js, React, Node.js). It allows you to manage user information including name, email, and address.

---

## Features

- **Create User:** Add new users by providing their name, email, and address.
- **Read Users:** View a list of all users stored in the database.
- **Update User:** Modify existing user details.
- **Delete User:** Remove users from the database.
- **Form Validation:** Basic client-side validation to ensure proper input.
- **Notifications:** Success and error toasts for better user feedback.

---

## Technology Stack

- **Frontend:** React.js, React Router, Axios, react-hot-toast, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (with Mongoose ODM)
- **API:** RESTful endpoints for all CRUD operations

---

## Project Structure
/client - React frontend
/server - Node.js backend with Express routes and MongoDB models/controllers

yaml
Copy
Edit

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/VisheshChoudhary139/CRUD_Operation.git

cd server
npm install
node index.js  # Runs backend server on port 8000

cd ../client
npm install
npm start  # Runs React app on port 3000
