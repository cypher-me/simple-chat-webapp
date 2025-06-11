# ChatApplication

A real-time chat application built with Spring Boot WebSocket backend and ReactJS frontend, enabling instant messaging between multiple users.

## 🚀 Features

- Real-time messaging using WebSocket technology
- Modern React frontend with responsive design
- Spring Boot backend with WebSocket support
- Multi-user chat functionality
- Clean and intuitive user interface

## 🛠️ Technology Stack

### Backend (Server)
- **Spring Boot** - Java framework for building the WebSocket server
- **WebSocket** - Real-time bidirectional communication protocol

### Frontend (Client)
- **ReactJS** - Modern JavaScript library for building user interfaces
- **WebSocket Client** - For real-time communication with the server

## 📸 Screenshots

### Chat Interface
![Chat screen](img/chat_screen.jpg "Chat screen")

## 🏗️ Project Structure

```
ChatApplication/
├── spring-ws-server/     # Spring Boot WebSocket server
├── react-client/         # ReactJS frontend application
└── img/                  # Screenshots and images
```

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed on your system:

- **Node.js** (v14 or higher)
- **npm** or **yarn**
- **Java** (JDK 8 or higher)
- **Maven** (for building the Spring Boot application)

### Installation & Setup

#### 1. Clone the Repository

```bash
git clone https://github.com/cypher-me/simple-chat-webapp.git
cd simple-chat-webapp
```

#### 2. Start the Server (Backend)

Navigate to the Spring Boot server directory and run:

```bash
cd spring-ws-server
mvn spring-boot:run
```

The server will start on the default port (usually `http://localhost:8080`).

#### 3. Start the Client (Frontend)

Open a new terminal window, navigate to the React client directory, and run:

```bash
cd react-client
npm install
npm start
```

The React application will start on `http://localhost:3000` and automatically open in your browser.

## 📝 Usage

1. **Start the Server**: Ensure the Spring Boot server is running first
2. **Launch the Client**: Start the React application
3. **Open Multiple Tabs**: Open the chat application in multiple browser tabs or windows to simulate multiple users
4. **Start Chatting**: Begin sending messages and see them appear in real-time across all connected clients

## 🔧 Development

### Server Development

The Spring Boot server handles:
- WebSocket connection management
- Message broadcasting to connected clients
- Session management

### Client Development

The React client provides:
- User interface for sending and receiving messages
- WebSocket connection handling
- Real-time message display

## 📚 API Documentation

### WebSocket Endpoints

- **Connection Endpoint**: `/ws` (or as configured in the Spring Boot application)
- **Message Format**: JSON objects containing user and message data

## 🐛 Troubleshooting

### Common Issues

- **Port conflicts**: Make sure ports 8080 (server) and 3000 (client) are available
- **WebSocket connection issues**: Ensure the server is running before starting the client
- **Build errors**: Check that all dependencies are properly installed

### Support

If you encounter any issues, please create an issue in the repository or contact the development team.

## 🔮 Future Enhancements

- User authentication and authorization
- Private messaging functionality
- Message history persistence
- File sharing capabilities
- Mobile application support

---

**Happy Chatting! 💬**