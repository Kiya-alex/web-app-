# Full-Stack Web Application

A modern, production-ready full-stack web application built with React, Node.js, Express, and MongoDB. This project demonstrates best practices in web development including responsive design, RESTful API architecture, authentication, and database management.

## 🚀 Features

- **User Authentication** - Secure login/signup with JWT tokens
- **Responsive Design** - Mobile-first UI with Tailwind CSS
- **RESTful API** - Clean, documented API endpoints
- **Database Integration** - MongoDB with Mongoose ORM
- **Error Handling** - Comprehensive error handling
- **Environment Configuration** - Secure env variable management
- **Input Validation** - Server-side and client-side validation

## 📋 Table of Contents

- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## 🛠 Tech Stack

### Frontend
- React 18
- Tailwind CSS
- Axios
- React Router
- Redux Toolkit

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB

### Backend Setup

git clone https://github.com/yourusername/web-app.git
cd web-app/backend
npm install
cp .env.example .env
npm start

### Frontend Setup

cd ../frontend
npm install
npm start

## 🎯 Usage

1. Start the backend server
2. Start the frontend development server
3. Open http://localhost:3000
4. Register or login with your credentials
5. Start using the application

## 🔌 API Documentation

### Authentication

**Register:**
POST /api/auth/register
{
  "email": "user@example.com",
  "password": "password",
  "fullName": "John Doe"
}

**Login:**
POST /api/auth/login
{
  "email": "user@example.com",
  "password": "password"
}

### Items

**Get All Items:**
GET /api/items
Headers: Authorization: Bearer {token}

**Create Item:**
POST /api/items
Headers: Authorization: Bearer {token}
{
  "title": "Item Title",
  "description": "Description"
}

**Update Item:**
PUT /api/items/:id
Headers: Authorization: Bearer {token}
{
  "title": "Updated Title",
  "description": "Updated Description"
}

**Delete Item:**
DELETE /api/items/:id
Headers: Authorization: Bearer {token}

## 📁 Project Structure

web-app/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── controllers/
│   ├── server.js
│   └── package.json
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── package.json
├── .gitignore
├── LICENSE
└── README.md

## 📝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

**Kiya-alex**
- GitHub: [@Kiya-alex](https://github.com/Kiya-alex)

---

Last Updated: 2026-05-17
