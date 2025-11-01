# ShowOff - Social Media Platform

ShowOff is a modern minimalistic social media platform built using the MERN stack where users can create posts, share images, interact, follow others, like posts and comment in real-time. The goal is to provide a fast, clean and elegant space for people to showcase their ideas, achievements and creativity.

## 🚀 Features

- User Authentication (JWT + HTTPOnly Cookies)
- Create / Delete Posts
- Like & Comment support
- Follow / Unfollow system
- User Profile Page
- Image Upload using Cloudinary
- Responsive UI (Mobile + Desktop)
- Recoil State Management for global store

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| Frontend | React, Vite, Chakra UI, Recoil |
| Backend | Node.js, Express.js, MongoDB |
| Storage | Cloudinary |
| Deployment | Vercel (Frontend + Backend) |

## 📂 Project Structure

```
ShowOff/
├── frontend/        # React (Vite)
└── backend/         # Node + Express
```

## ⚙️ Setup Instructions

### Clone Repository

```bash
git clone <YOUR_REPO_URL>
cd ShowOff
```

### Backend Setup

```bash
cd backend
npm install
npm start
```

Create `.env` inside backend:

```
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
CLOUDINARY_CLOUD_NAME=
```

### Frontend Setup

```bash
cd ../frontend
npm install
npm run dev
```

## 🌍 Deployment Links

| Service | URL |
|---------|------|
| Frontend | https://show-off-frontend.vercel.app |
| Backend | https://show-off-backend.vercel.app |

## 📘 Learnings

- Managing secure token flow using HTTPOnly cookies
- Deployment lifecycle on Vercel for MERN apps
- Recoil based global store optimization

## 🤝 Contributing

Contributions are welcome! Fork this repository and open a PR.

## 📜 License

MIT License


username - utkars1
pass - 12345678
email - utkarsh@gmail.com

username - tanishka
pass - 12345678
email - tanishka@gmail.com
