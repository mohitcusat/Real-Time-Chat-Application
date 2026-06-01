# 💬 Full Stack Realtime Chat App

A modern real-time chat application built using the MERN stack with Socket.io for instant messaging. Users can create accounts, update profiles, upload profile pictures, and chat in real time with online users.

## 🚀 Features

- 🔐 User Authentication & Authorization using JWT
- 💬 Real-time messaging with Socket.io
- 🟢 Online/Offline user status
- 👤 User profile management
- 🖼️ Profile image upload with Cloudinary
- ⚡ Fast frontend with React + Vite
- 🎨 Responsive UI using Tailwind CSS & DaisyUI
- 🗄️ MongoDB Atlas database integration
- 📱 Mobile-friendly design
- 🔄 Global state management with Zustand
- 🛡️ Secure password handling
- ❌ Error handling on both client and server

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- DaisyUI
- Zustand
- Axios
- Socket.io Client

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT Authentication
- Socket.io
- Cloudinary

---

## 📂 Project Structure

```bash
fullstack-chat-app/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── lib/
│   │   └── index.js
│   └── .env
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── vite.config.js
│
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the backend folder.

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

---

## 📥 Installation

### Clone Repository

```bash
git clone <https://github.com/mohitcusat/Real-Time-Chat-Application.git>
cd fullstack-chat-app
```

### Install Backend Dependencies

```bash
cd backend
npm install
```

### Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

---

## ▶️ Run Project

### Start Backend

```bash
cd backend
npm start
```

### Start Frontend

```bash
cd frontend
npm run dev
```

Frontend will run at:

```text
http://localhost:5173
```

Backend will run at:

```text
http://localhost:5001
```

---

## 🗄️ Database

This project uses MongoDB Atlas for cloud database storage.

- User Information
- Chat Messages
- Profile Data

---

## ☁️ Deployment

Frontend can be deployed on:

- Vercel
- Netlify

Backend can be deployed on:

- Render
- Railway
- Cyclic

Database:

- MongoDB Atlas

---

## 📸 Screenshots

Add application screenshots here.

---

## 👨‍💻 Author

**Mohit Chauhan**

GitHub: https://github.com/mohitcusat
---