# Chat-JS: A Real-Time Chat Application 🌐💬

![Chat-JS](https://img.shields.io/badge/Chat--JS-v1.0.0-blue.svg)
[![Releases](https://img.shields.io/badge/Releases-v1.0.0-orange.svg)](https://github.com/abhinav579/Chat-JS/releases)

Welcome to **Chat-JS**, a real-time chat web application designed to provide seamless communication for users. Built with **Node.js**, **Express**, and **Socket.IO**, Chat-JS enables users to engage in live messaging, manage sessions, and enjoy a range of features that enhance their chatting experience. This project is perfect for local network deployment and is developed by **Bocaletto Luca**.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

Chat-JS comes packed with features that make it a powerful tool for real-time communication:

- **User Registration**: Users can create accounts to join the chat.
- **Persistent Sessions**: Sessions remain active, allowing users to reconnect without losing their chat history.
- **Live Messaging**: Send and receive messages in real-time.
- **JSON History**: Chat history is stored in JSON format for easy retrieval.
- **Notifications**: Users receive notifications for new messages.
- **Clear Chat Functionality**: Easily clear chat history when needed.

## Technologies Used

Chat-JS leverages several technologies to deliver its functionality:

- **Node.js**: A JavaScript runtime built on Chrome's V8 engine.
- **Express**: A web application framework for Node.js, providing a robust set of features.
- **Socket.IO**: Enables real-time, bidirectional communication between web clients and servers.
- **MongoDB**: A NoSQL database used for storing user data and chat history.
- **HTML/CSS/JavaScript**: The core technologies for building the web interface.

## Installation

To get started with Chat-JS, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/abhinav579/Chat-JS.git
   cd Chat-JS
   ```

2. **Install Dependencies**:
   Run the following command to install all necessary packages:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add your configuration. Here is an example:
   ```
   PORT=3000
   MONGODB_URI=mongodb://localhost:27017/chatjs
   ```

4. **Start the Application**:
   Use the following command to start the server:
   ```bash
   npm start
   ```

5. **Access the Application**:
   Open your web browser and go to `http://localhost:3000`.

## Usage

Once the application is running, users can:

1. **Register**: Fill in the registration form to create a new account.
2. **Log In**: Use your credentials to log into the chat.
3. **Chat**: Start sending messages to other users in real-time.
4. **Clear Chat**: Use the clear chat button to remove the chat history.

For more details, visit the [Releases](https://github.com/abhinav579/Chat-JS/releases) section.

## How It Works

Chat-JS operates on a client-server model:

- **Client Side**: The front-end is built with HTML, CSS, and JavaScript. Users interact with the interface to send and receive messages.
- **Server Side**: The back-end, powered by Node.js and Express, handles requests and manages real-time communication using Socket.IO. It also connects to MongoDB for data storage.

### Data Flow

1. **User Registration**: When a user registers, their information is sent to the server and stored in MongoDB.
2. **Real-Time Messaging**: When a user sends a message, it is emitted to the server via Socket.IO. The server then broadcasts this message to all connected clients.
3. **Chat History**: The server retrieves chat history from MongoDB and sends it to the client when they log in.

## Contributing

Contributions are welcome! If you would like to contribute to Chat-JS, please follow these steps:

1. **Fork the Repository**: Click the "Fork" button on the top right of this page.
2. **Create a Branch**: Create a new branch for your feature or bug fix.
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Changes**: Implement your changes.
4. **Commit Your Changes**: 
   ```bash
   git commit -m "Add your message here"
   ```
5. **Push to the Branch**: 
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Open a Pull Request**: Go to the original repository and create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

Special thanks to the following resources and communities:

- [Node.js](https://nodejs.org)
- [Express](https://expressjs.com)
- [Socket.IO](https://socket.io)
- [MongoDB](https://www.mongodb.com)

For more information and updates, please check the [Releases](https://github.com/abhinav579/Chat-JS/releases) section.