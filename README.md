
# SocialS – Real-Time Social Messaging Platform

SocialS is a full-stack social messaging platform designed to support dynamic user interaction, responsive theming, and secure communication. Built using modern web technologies, this app is scalable, performant, and ready for real-time functionality.

## 🚀 Features

- 🔒 Secure login & registration with JWT and bcrypt
- 💬 Socket.IO-ready backend for real-time messaging
- 🎨 Theme switching with DaisyUI + Tailwind
- ⚡ Fast builds and hot reloads with Vite
- 🗂️ Clean, modular architecture with Express and Mongoose

## 🛠 Tech Stack

### Frontend
- React
- Tailwind CSS
- DaisyUI
- Zustand (state management)
- Vite

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- bcrypt for password hashing

## 🧪 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/socials-platform.git
cd socials-platform
```

### 2. Install dependencies

Install both frontend and backend dependencies:

```bash
cd frontend
npm install

cd ../backend
npm install
```

### 3. Configure environment variables

Create a `.env` file in the `backend` directory with the following:

```
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
NODE_ENV=development
```

### 4. Run the development servers

```bash
# Start backend
cd backend
npm run dev

# In a separate terminal, start frontend
cd ../frontend
npm run dev
```



## 📁 Project Structure

```
SocialS Platform/
├── backend/
│   ├── src/
│   └── .env
├── frontend/
│   └── src/
└── README.md
```

## 📜 License

MIT License © 2024
