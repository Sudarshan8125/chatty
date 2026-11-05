# Chatty 💬

A full-stack realtime chat application built with the MERN stack and Socket.io.

## Features

- 🔐 JWT Authentication & Authorization
- 💬 Real-time messaging with Socket.io
- 🟢 Online user status tracking
- 🖼️ Image sharing via Cloudinary
- 🎨 30+ themes with TailwindCSS + DaisyUI
- 📦 State management with Zustand

## Tech Stack

| Layer | Tools |
|-------|-------|
| Frontend | React, Vite, TailwindCSS, DaisyUI, Zustand |
| Backend | Node.js, Express, MongoDB, Socket.io |
| Auth | JWT, bcrypt |
| Media | Cloudinary |

## Getting Started

### 1. Clone

```bash
git clone https://github.com/Sudarshan8125/chatty.git
cd chatty
```

### 2. Environment Variables

Create a `.env` file in the `backend` directory:

```env
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### 3. Install & Run

```bash
npm run build   # installs deps for backend + frontend, builds frontend
npm start        # starts the server
```

App runs at `http://localhost:5001`.
