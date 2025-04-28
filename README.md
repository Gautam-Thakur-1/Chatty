# 💬Chatter: Real-Time Chat App

A modern real-time chat application built with a **MERN stack** (MongoDB, Express, React, Node.js) and **Socket.IO**. It supports user authentication, real-time messaging, and cloud image upload using **Cloudinary**.

---

## 🧱 Project Structure

```
chat-app/
├── backend/      # Express.js server (API, Socket.IO, MongoDB)
└── frontend/     # React client (Vite, Zustand, TailwindCSS)
```

---

## 🚀 Features

- 🔐 User authentication (JWT + bcrypt)
- 💬 Real-time messaging (Socket.IO)
- ☁️ Image upload via Cloudinary
- 📦 State management with Zustand
- 🎨 Styled with Tailwind CSS + DaisyUI
- 🧭 Routing with React Router
- 🔥 Toast notifications (react-hot-toast)

---

## 📦 Tech Stack I used

| Category     | Technology                                 |
| ------------ | ------------------------------------------ |
| Frontend     | React, Vite, Zustand, TailwindCSS, DaisyUI |
| Backend      | Express.js, MongoDB, Mongoose              |
| Real-Time    | Socket.IO                                  |
| Auth         | JWT, bcryptjs                              |
| Image Upload | Cloudinary                                 |

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Gautam-thakur-1/chatter.git
cd chat-app
```

---

### 2. Setup the Backend

```bash
cd backend
npm install
```

#### Create a `.env` file

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

#### Start the backend server

```bash
npm run dev
```

---

### 3. Setup the Frontend

```bash
cd ../frontend
npm install
npm run dev
```

---

## 🛠 Scripts

### Backend

- `npm run dev` – Run backend with nodemon
- `npm start` – Run backend normally

### Frontend

- `npm run dev` – Start Vite development server
- `npm run build` – Build for production

---

## 📁 License

This project is licensed under the [ISC License](https://opensource.org/licenses/ISC).

---

## 🙌 Contributions

Contributions are very welcome, Please open an issue or submit a PR.
