# WebSocket Chat Application

This project is a simple WebSocket-based chat application built with Spring Boot and JavaScript. It allows users to connect, send messages, and receive messages from other users in real-time.

## Features

- Real-time chat functionality using WebSockets.
- User authentication and session management.
- Message broadcasting to all connected users.
- Handling user join and leave events.

## Setup

1. **Clone the repository** to your local machine.
2. **Build the project** using Maven or Gradle.
3. **Run the application** using `java -jar target/chat-application.jar` (adjust the command based on your build tool and project structure).
4. **Access the application** in your browser at `http://localhost:8080`.

## Usage

1. **Enter a username** on the initial page to join the chat.
2. **Send messages** using the input field on the chat page.
3. **View messages** in real-time as they are sent by other users.

## Technologies

- **Backend**: Spring Boot, WebSocket, STOMP, SockJS.
- **Frontend**: HTML, CSS, JavaScript, SockJS, STOMP.js.

## Contributing

Contributions are welcome Please feel free to submit a pull request or open an issue to report a bug or suggest improvements.

## License

This project is licensed under the MIT License.
