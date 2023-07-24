**README: Simple Java Client-Server Chat Application**

This repository contains a simple Java client-server chat application that allows two users to exchange messages over a network. The chat application consists of two Java programs, one for the server and the other for the client.

## Server Application

The `Server.java` file represents the server-side of the chat application. It creates a server socket that listens on port 2100 for incoming client connections. When a client connects, the server establishes a connection and starts a chat session with the client. The server and client can exchange messages in a chat-like manner until the client terminates the chat.

To run the server application:
1. Compile the Java file using `javac`:
   ```bash
   javac Server.java
   ```
2. Start the server application:
   ```bash
   java Server
   ```

## Client Application

The `Client.java` file represents the client-side of the chat application. It establishes a connection to the server running on localhost at port 2100. Once the connection is established, the client and server can exchange messages. The chat session continues until the client types "end" to terminate the chat.

To run the client application:
1. Compile the Java file using `javac`:
   ```bash
   javac Client.java
   ```
2. Start the client application:
   ```bash
   java Client
   ```

Please note that for successful communication between the client and server, the server application must be running before starting the client application.

**Usage Instructions**
- When the server and client are connected, they can exchange messages by typing text and pressing "Enter."
- The server and client will take turns sending and receiving messages until the chat is terminated.
- To end the chat, the client should type "end" (without quotes) and press "Enter." This will close the connection with the server and end the chat session.

**Important Note**
This chat application is a simple example for educational purposes. It lacks error handling and security features and should not be used in a production environment.

Feel free to explore and modify the code to enhance the chat application's features or use it as a starting point for more sophisticated client-server applications. Enjoy chatting!
