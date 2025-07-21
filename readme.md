# ✅ To-Do App (MERN Stack)

A full-stack **To-Do Application** built using the **MERN stack (MongoDB, Express, React, Node.js)**. This app allows users to register, log in, and manage daily tasks with an intuitive UI and secure backend authentication.

---


## ✨ Features

- 📝 Add, update, and delete to-do tasks
- 👥 User registration and login system
- 🔒 JWT-based secure authentication
- 📧 Email verification using Gmail SMTP
- 📱 Responsive design for all devices
- ⚙️ Environment-based configuration support

---

## 🛠️ Tech Stack

| Technology     | Purpose                        |
|----------------|--------------------------------|
| **React.js**   | Frontend user interface        |
| **Node.js**    | Backend runtime                |
| **Express.js** | API and server framework       |
| **MongoDB**    | NoSQL database                 |
| **Mongoose**   | MongoDB object modeling        |
| **JWT**        | User authentication            |
| **Nodemailer** | Sending verification emails    |

---

## 🚀 Getting Started

Follow the steps below to set up and run the project locally.

### 📦 Installation

Go to `frontend` and `backend` directories to install the dependencies.

```bash
cd frontend
npm install
```
```bash
cd backend
npm install
```

### ⚙️ Configuration
Create a .env file inside the backend directory and add the following:
```bash
MONGO_URI=your_mongodb_connection_string
GMAIL_USERNAME=your_email_address
GMAIL_PASSWORD=your_app_password   # Use Gmail App Password (not your Gmail password)
PORT=8000
JWT_SECRET=thisisasecretkey
```

💡 Note: For Gmail password, generate an App Password via your Google account > Security > App Passwords.

## 🏃‍♂️ Run the App
Start both frontend and backend servers:

# Start Backend :
```bash
cd backend
nodemon server
```

# Start Frontend
```bash
cd frontend
npm start
```
