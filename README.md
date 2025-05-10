# 💬 Multi-Room Chat App (Node.js + WebSockets)

I built this real-time chat app to explore how JavaScript, despite being single-threaded, can still feel like it's multitasking—especially with the help of WebSockets and asynchronous behavior. This was originally a multithreaded Java-based project, which I later recreated using **Node.js**, **Express**, **Socket.IO**, and **WebSocket** to dive deeper into JS internals.

---

## 🚀 Features

* Choose your own username and join any chatroom
* Displays join time and participants in the room
* Broadcasts messages **only within** the current chatroom
* Real-time user presence updates (join/leave)
* Built to mimic multithreaded behavior using JS's event-driven model

---

## 📁 Tech Stack

* Node.js
* Express.js
* WebSocket
* Socket.IO
* Ngrok (for testing public connections)

---

## 🛠️ How to Run

1. **Clone the repo**

   ```bash
   git clone <your-repo-url>
   cd <project-folder>
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the server**

   ```bash
   npm start
   ```

   This runs the app on **localhost:3500**.

4. **(Optional) Use Ngrok for public access**

   ```bash
   ngrok http 3500
   ```

   This gives you a public-facing URL to share or test with others.

---

## 🧠 Why I Built This

I wanted to see how JS's non-blocking architecture could support a real-time application that feels multitasked—even though it’s single-threaded under the hood. Socket.IO handles concurrent socket events efficiently, and this project helped me solidify that understanding.

---

## 📦 Project Structure (optional if you'd like to include)

```bash
.
├── public
│   ├── index.html
│   └── ...
├── server.js
├── package.json
└── README.md
```

---

## ⚙️ Future Plans

* Add authentication
* Deploy on a hosting platform
* Persistent chat history with MongoDB
* Better UI and mobile responsiveness

---
