# 💬 Chatting App (Laravel + React)

A real-time chatting application built using **Laravel (Backend)** and **React (Frontend)**.
This app allows users to send and receive messages instantly with a modern UI.

---

## 🚀 Features

* 🔐 User Authentication (Login/Register)
* 💬 Real-time Messaging
* 🟢 Online / Offline Status
* 📩 Private Chats
* 📁 File & Image Sharing *(optional if you add)*
* 🔔 Notifications *(optional)*
* ⚡ Fast & Responsive UI (React)

---

## 🛠️ Tech Stack

### Backend:

* PHP / Laravel
* Laravel Sanctum / JWT (for authentication)
* MySQL Database
* Laravel WebSockets *(optional for real-time)*

### Frontend:

* React.js
* Axios
* Tailwind CSS / Bootstrap *(depending on your setup)*

---

## 📂 Project Structure

```
ChatApp/
│
├── backend/ (Laravel)
│   ├── app/
│   ├── routes/
│   ├── database/
│
├── frontend/ (React)
│   ├── src/
│   ├── components/
│   ├── pages/
│
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/CodeWithRehan-Stacks/chatingAPP.git
cd chatingAPP
```

---

### 2️⃣ Backend Setup (Laravel)

```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
```

👉 Configure your `.env`:

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

### 3️⃣ Frontend Setup (React)

```bash
cd frontend
npm install
npm run dev
```

---

## 🔌 API Endpoints (Example)

| Method | Endpoint      | Description    |
| ------ | ------------- | -------------- |
| POST   | /api/register | Register user  |
| POST   | /api/login    | Login user     |
| GET    | /api/users    | Get users      |
| POST   | /api/message  | Send message   |
| GET    | /api/messages | Fetch messages |

---

## 📸 Screenshots

*Add your app screenshots here*

---

## 🧠 Future Improvements

* Group Chat
* Voice Messages
* Video Calling
* Message Reactions
* Dark Mode

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Muhammad Rehan**
GitHub: https://github.com/CodeWithRehan-Stacks

---

## ⭐ Support

If you like this project, please ⭐ the repository!
