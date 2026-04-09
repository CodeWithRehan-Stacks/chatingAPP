# 💬 Chatting App (Laravel + React)

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-Backend-red?style=for-the-badge&logo=laravel">
  <img src="https://img.shields.io/badge/React-Frontend-blue?style=for-the-badge&logo=react">
  <img src="https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge&logo=mysql">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/CodeWithRehan-Stacks/chatingAPP?style=for-the-badge">
</p>

<p align="center">
  ⚡ Real-time Chat App with Modern UI ⚡  
</p>

---

## 🚀 Live Demo

👉 **Frontend:** https://your-live-demo-link.com
👉 **Backend API:** https://your-api-link.com

---

## 🎥 Demo Preview (GIF)

<p align="center">
  <img src="https://via.placeholder.com/800x400.gif?text=Chat+App+Demo+GIF" alt="Chat Demo">
</p>

> 🔥 Replace this GIF with your real app recording (use ScreenToGif or OBS)

---

## 📸 Screenshots

| Login Page                               | Chat Dashboard                           |
| ---------------------------------------- | ---------------------------------------- |
| ![](https://via.placeholder.com/400x250) | ![](https://via.placeholder.com/400x250) |

---

## ✨ Features

* 🔐 Authentication (Register / Login)
* 💬 Real-time Messaging
* 🟢 Online / Offline Status
* 📩 Private Chats
* ⚡ Fast UI with React
* 📡 API-driven architecture
* 🔔 Notifications *(coming soon)*

---

## 🛠️ Tech Stack

### 🔙 Backend

* Laravel
* Laravel Sanctum / JWT
* MySQL
* Laravel WebSockets / Pusher

### 🎨 Frontend

* React.js
* Axios
* Tailwind CSS

---

## 📂 Folder Structure

```
ChatApp/
├── backend/
├── frontend/
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone Repo

```bash
git clone https://github.com/CodeWithRehan-Stacks/chatingAPP.git
cd chatingAPP
```

---

### 2️⃣ Setup Backend (Laravel)

```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
```

Update `.env`:

```
DB_DATABASE=chatapp
DB_USERNAME=root
DB_PASSWORD=
```

```bash
php artisan migrate
php artisan serve
```

---

### 3️⃣ Setup Frontend (React)

```bash
cd frontend
npm install
npm run dev
```

---

## 🔌 API Endpoints

| Method | Endpoint      | Description    |
| ------ | ------------- | -------------- |
| POST   | /api/register | Register user  |
| POST   | /api/login    | Login user     |
| GET    | /api/users    | Get users      |
| POST   | /api/message  | Send message   |
| GET    | /api/messages | Fetch messages |

---

## 🧠 Future Plans

* 👥 Group Chat
* 📞 Voice & Video Calls
* 😊 Emojis & Reactions
* 🌙 Dark Mode
* 📎 File Uploads

---

## 🤝 Contributing

1. Fork the project
2. Create your feature branch
3. Commit your changes
4. Push to branch
5. Open Pull Request

---

## 📜 License

MIT License

---

## 👨‍💻 Author

**Muhammad Rehan**
🔗 https://github.com/CodeWithRehan-Stacks

---

## ⭐ Show Some Love

If you like this project, please ⭐ the repo and share it!

<p align="center">
  🚀 Built with ❤️ using Laravel & React
</p>

