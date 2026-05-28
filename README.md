# Blog Platform with Comments

A full-stack MERN Blog Platform where users can register, login, create blog posts, manage posts, and interact through comments.

---

# Features

- User Registration & Login
- JWT Authentication
- Create Blog Posts
- Edit Blog Posts
- Delete Blog Posts
- Add Comments
- RESTful APIs
- MongoDB Integration
- Responsive UI
- Full Stack MERN Architecture

---

# Tech Stack

## Frontend
- React.js
- HTML5
- CSS3
- Bootstrap
- Axios
- React Router DOM

## Backend
- Node.js
- Express.js

## Database
- MongoDB

## Authentication
- JWT Authentication

---

# Project Structure

blog-platform/
│
├── backend/
│   ├── models/
│   │   ├── User.js
│   │   ├── Post.js
│   │   └── Comment.js
│   │
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── postRoutes.js
│   │   └── commentRoutes.js
│   │
│   ├── middleware/
│   │   └── authMiddleware.js
│   │
│   ├── node_modules/
│   ├── .env
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   │   ├── Home.js
│   │   │   ├── Login.js
│   │   │   ├── Register.js
│   │   │   └── CreatePost.js
│   │   │
│   │   ├── App.js
│   │   ├── App.css
│   │   └── index.js
│   │
│   ├── package.json
│   └── node_modules/
│
└── README.md

---

# Requirements

Before running the project install:

- Node.js
- npm
- MongoDB Community Server
- VS Code
- Git & GitHub

---

# Installation Guide

## 1. Clone Repository

```bash
git clone https://github.com/yourusername/blog-platform.git
cd blog-platform
