# Build-your-own-RESTFUL-API

Blog Manager with RESTful API is a full-stack web application that enables users to create, read, update, and delete blog posts. It features a custom-built RESTful API using Node.js and Express on the backend, and a dynamic frontend rendered with EJS templates.
The backend (index.js) serves as an in-memory API that handles HTTP requests for blog data, while the frontend server (server.js) uses Axios to communicate with the API and render pages like the blog homepage, post creation, and editing forms.
Users can browse all blog entries, add new posts, edit existing ones, and delete posts with just a few clicks. The user interface is clean and simple, with styling provided via static CSS files.
The project demonstrates RESTful design principles, clear route handling, modular architecture, and integration between frontend and backend services—making it a great learning project for aspiring full-stack developers.

A full-stack blog application that allows users to **Create**, **Read**, **Update**, and **Delete** (CRUD) blog posts using a custom-built **RESTful API** and dynamic rendering with **Express** and **EJS**.

---

# 📌 Features

- View all blog posts
- Create a new post
- Edit an existing post
- Delete a post
- Backend API for data operations
- Clean and responsive UI

# 🧠 What is a RESTful API?

A **RESTful API** (Representational State Transfer) is an architectural style for designing networked applications. It uses standard HTTP methods like `GET`, `POST`, `PATCH`, and `DELETE` to perform CRUD operations on resources, which are represented by URIs.

### 🛠️ RESTful Design in This Project

| HTTP Method | Endpoint           | Description                  |
|-------------|--------------------|------------------------------|
| GET         | `/posts`           | Fetch all posts              |
| GET         | `/posts/:id`       | Fetch a specific post        |
| POST        | `/posts`           | Create a new post            |
| PATCH       | `/posts/:id`       | Update fields of a post      |
| DELETE      | `/posts/:id`       | Delete a specific post       |

---

# 🏗️ Project Architecture

```plaintext
📦 blog-manager/
├── 📂 public/              # Static CSS files
│   └── styles/
├── 📂 views/               # EJS templates
│   ├── index.ejs
│   └── modify.ejs
├── 📄 index.js             # RESTful API server (port 4000)
├── 📄 server.js            # Frontend server using EJS (port 3000)
├── 📄 package.json
```
# 🚀 Getting Started
🔧 Prerequisites
Node.js (v14 or higher)

npm (comes with Node)

# 📦 Installation

git clone https://github.com/yourusername/blog-manager.git
cd blog-manager
npm install

# ▶️ Running the App

You need to run two servers:
1. Start the API Server (port 4000)
   node index.js
2. Start the Frontend Server (port 3000)
  In another terminal:
  node server.js

# 🌐 Access the App

Open your browser and go to:

http://localhost:3000

# ✨ Future Enhancements

Connect to a real database like MongoDB or PostgreSQL
Add user authentication
Add categories/tags to posts
Improve form validation and error handling
Enable markdown support for blog content

# 🙌 Acknowledgments

Express.js
Axios
EJS
Node.js
Design inspired by simple blogging UIs

# 📜 License
This project is licensed under the MIT License.
