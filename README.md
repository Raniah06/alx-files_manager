# **Blog Platform (MERN Stack)**

A **full-stack blog platform** built with **React (frontend)** and **Node.js (backend)**.  
The application allows users to create, edit, delete, and read blog posts with authentication and image uploads.

# **Files Manager API**

A backend file management system built with **Node.js, Express, MongoDB, and Redis**. It provides authentication, file storage, and folder management functionalities.

---

## **Table of Contents**
- [Description](#description)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Project Structure](#project-structure)
- [Testing](#testing)
- [Troubleshooting](#troubleshooting)
- [Author](#author)

---

## **Description**
Files Manager is a RESTful API that allows users to:
- Authenticate using a token-based system.
- Upload and manage files (images, text, and other documents).
- Create and organize folders.
- Store metadata in MongoDB.
- Use Redis for session management and caching.

---

## **Features**
✔ User authentication via token-based sessions.  
✔ Create, retrieve, update, and delete files and folders.  
✔ Store metadata in MongoDB for efficient querying.  
✔ Redis caching for fast authentication lookups.  
✔ Robust API design with proper error handling.  

---

## **Technologies**
The project is built using:

| Technology  | Description |
|-------------|------------|
| Node.js     | JavaScript runtime for the backend |
| Express.js  | Lightweight web framework for APIs |
| MongoDB     | NoSQL database for storing user and file data |
| Redis       | In-memory database for caching and authentication |
| Mongoose    | ODM for MongoDB |
| UUID        | Generate unique identifiers for files |
| Multer      | Middleware for handling file uploads |
| Babel       | JavaScript transpiler (ES6+ support) |
| ESLint      | JavaScript linting and style guide |
| Jest        | Testing framework for unit tests |

---

## **Installation**

### **Prerequisites**
Before setting up the project, ensure the following installed:
- **Node.js**
- **MongoDB**
- **Redis**

#### **1. Clone the repository**
```bash
git clone https://github.com/Raniah06/files_manager.git
cd files_manager.

### **Steps to Set Up the Project**       - Install dependencies: npm install.      - Start redis: redis-server               - Start server: npx nodemon server.       - Start ckient: npm start.
