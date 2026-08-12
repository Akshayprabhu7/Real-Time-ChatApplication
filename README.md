# 💬 Real-Time Chat Application

A modern and responsive real-time chat application built using **Java, Spring Boot WebSocket, STOMP, SockJS, HTML, CSS, and JavaScript**.

The application allows multiple users to connect and exchange messages instantly through WebSocket communication.

## 🚀 Live Demo

👉 https://real-time-chatapplication-rodq.onrender.com

## 📂 GitHub Repository

👉 https://github.com/Akshayprabhu7/Real-Time-ChatApplication

---

## ✨ Features

- 💬 Real-time messaging
- ⚡ WebSocket communication
- 🔄 STOMP messaging protocol
- 🌐 SockJS support
- 👥 Multiple users can chat simultaneously
- 🟢 Online/Offline connection status
- 🔁 Automatic WebSocket reconnection
- 😊 Emoji picker
- 👤 Username support
- 💾 Username saved using Local Storage
- ⏱️ Message timestamps
- 🔢 Message character counter
- 📱 Fully responsive mobile design
- 💻 Desktop-friendly UI
- 🎨 Modern interactive user interface
- 🐳 Dockerized application
- ☁️ Deployed on Render

---

## 🛠️ Technologies Used

### Backend

- Java 21
- Spring Boot
- Spring WebSocket
- STOMP
- SockJS
- Maven

### Frontend

- HTML5
- CSS3
- JavaScript

### Deployment

- Docker
- GitHub
- Render

---

## 🏗️ Project Structure

```text
Real-Time-ChatApplication/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── chat/
│       │           └── app/
│       │               ├── AppApplication.java
│       │               ├── ChatController.java
│       │               ├── ChatMessage.java
│       │               └── WebSocketConfig.java
│       │
│       └── resources/
│           ├── static/
│           │   └── index.html
│           │
│           └── application.properties
│
├── .mvn/
├── Dockerfile
├── mvnw
├── mvnw.cmd
├── pom.xml
└── README.md
