# 💬 ChatApp

A real-time chat application built to demonstrate modern web communication using WebSockets.  
This project enables users to join chat rooms and exchange messages instantly with other users.

Real-time chat systems are commonly used in messaging platforms and collaboration tools to allow instant communication between users. :contentReference[oaicite:1]{index=1}

---

# 🚀 Features

- 💬 Real-time messaging
- 👥 Multiple users chatting simultaneously
- ⚡ Instant message delivery using WebSockets
- 🧑 Username-based chat participation
- 📡 Live communication between frontend and backend
- 📱 Simple and responsive UI

---

# 🛠️ Tech Stack

**Frontend**
- ReactJs

**Backend**
- Java
- Spring Boot
- WebSocket

**Build Tool**
- Maven

---

# 🏗️ Project Architecture

```

Client (Browser)
|
WebSocket Connection
|
Spring Boot Server
|
Message Broadcasting to Connected Clients

````

The application uses **WebSockets** to maintain a persistent connection between the client and server, enabling real-time communication without repeated HTTP requests.

---

# ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/harshitkkush/ChatApp.git
````

### 2️⃣ Navigate to project directory

```bash
cd ChatApp
```

### 3️⃣ Run the Spring Boot application

If using Maven:

```bash
mvn spring-boot:run
```

or run the main application class from your IDE.

---

# ▶️ How to Use

1. Start the Spring Boot server
2. Open the application in your browser
3. Enter your username
4. Join the chat room
5. Send and receive messages instantly

---

# 📂 Project Structure

```

ChatApp-Backend
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── websocket configuration
│   │   │   └── controller
│   │   ├── resources
│   │   │   └── static
│   │   │   └── templates
│
└── pom.xml

```

---

# 📸 Demo

*(Add screenshots or GIFs here)*

Example:

```
![ChatApp Screenshot](screenshots/chat.png)
```

---

# 🔮 Future Improvements

* User authentication
* Private messaging
* Chat rooms
* Message persistence using database
* Typing indicators
* Message history

---

# 👨‍💻 Author

**Harshit Kushwaha**

* GitHub: [https://github.com/harshitkkush](https://github.com/harshitkkush)
* Email: [harshitkkush@gmail.com](mailto:harshitkkush@gmail.com)

---

# ⭐ Support

If you like this project, please give it a ⭐ on GitHub!

```


