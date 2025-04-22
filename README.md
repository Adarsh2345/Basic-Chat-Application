# 📱 Basic Chat App with Socket.IO

This is a simple real-time chat application built with **React Native (Expo)** on the frontend and **Node.js + Socket.IO** on the backend. It allows users to log in with a username and chat in real time with others connected to the app.

---

## 🚀 Features

- Real-time messaging with Socket.IO
- Simple login with username
- Message history for all users
- Mobile-friendly UI using React Native
- Expo-based development for easy testing on physical devices

---

## 🧱 Tech Stack

### Frontend:
- React Native (Expo)
- Socket.IO client

### Backend:
- Node.js
- Express.js
- Socket.IO

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/basic-chat-app.git
cd basic-chat-app

```
### 2. Start the backend server

```bash
cd server
npm install
node index.js

```

### 3. Set up the frontend

Change the  IP address in the frontend code to point to your local server : Use your system's local IP address which can be found by typing ipconfig in Command Prompt

```bash

// App.js
const socket = io('http://192.168.X.X:3001'); // Replace with your actual IP
```
Then install Expo CLI if you haven’t already:

```bash
npm install -g expo-cli
```
Start the frontend:

```bash

cd client
npm install
expo start
```
Use Expo Go on your phone to scan the QR code and launch the app.

## 📱 Testing on Mobile
Ensure your phone and computer are on the same Wi-Fi network.

Replace localhost with your local IP address in the frontend code.

Scan the QR code using Expo Go.

📂 Project Structure
```bash

.
├── frontend/           # React Native frontend (Expo)
│   └── App.js
├── backend/           # Node.js backend
│   └── server.js
└── README.md
