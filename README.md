# WebSocket

This project demonstrates a simple WebSocket application built using Spring Boot. It includes a frontend HTML page for real-time communication with the server. You can send messages from the HTML client or Postman, and they are echoed back and displayed in both interfaces.

## Features
- **WebSocket Communication**: Enables real-time communication between a client and server.
- **HTML Client**: Allows users to send and receive messages via a simple form.
- **Postman Integration**: Supports message exchange through Postman for testing purposes.

---

## Prerequisites
- **Java 17** (or compatible version)
- **Maven** (for dependency management)
- A modern web browser

---

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/somnath271/webSocket-project.git
```

### 2. Build and Run the Application
``` bash
mvn spring-boot:run
```
### 3. Open the WebSocket Client

- Navigate to http://localhost:8080/index.html in your web browser.
- Enter a message in the form and click "Send." The message will be echoed back by the server.

### 4. Test with Postman
- Send a WebSocket message using Postman to ws://localhost:8080/ws.
- Observe real-time communication between the client and the server.


## Project Workflow
- When the HTML form submits, a WebSocket message is sent to the server.
- The server echoes the message back to all connected clients.
- Messages can also be sent directly via Postman to test the WebSocket connection.

## Contributing
- Contributions are welcome! Fork this repository, create a new branch, and submit a pull request for review.
