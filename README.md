# MERN Stack Real-Time Chat Application (with AI Smart Replies)

A full-stack chat application built using the **MERN stack (MongoDB, Express, React, Node.js)** with **real-time messaging powered by Socket.IO**.  
Includes **AI-generated smart replies using OpenAI API**, secure authentication, encrypted messages, group chat, and media sharing.

## 🚀 Features

### 🔐 Security & Authentication
- Secure login & signup with **JWT authentication**
- **Password hashing** using bcrypt
- **Email verification** on signup
- **Encrypted messages** using Crypto module

### 💬 Chat Functionalities
- One-to-One Private Chats
- Group Chats with Admin privileges (add/remove users)
- Typing indicator (real-time using Socket.IO)
- Message Forward / Reply / Delete
- Send photos & media (Cloudinary integration)
- Custom chat wallpaper
- Muting chats & notification management

### 🤖 AI Integration
- **Smart Reply System using OpenAI API**
- Automatically generates reply suggestions for text messages

### 👤 User & Profile
- User search to start new conversation
- Profile picture update
- Status update (auto-expiry after 24 hours)

### ⚙️ Other Features
- Tic-Tac-Toe game inside chat using command `\play`
- Scheduled clean-up jobs using **node-cron**

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| MongoDB | Database |
| Express.js | Backend API |
| React.js | Frontend UI |
| Node.js | Server runtime |
| Socket.IO | Real-time messaging |
| OpenAI API | AI reply generation |
| Cloudinary | Image uploads |
| JWT, bcrypt | Security |
| Tailwind / Chakra UI | UI styling |

---

## 📦 Installation

Clone the repository:

```sh
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
