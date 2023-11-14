# Simple Java Chat Application

This is a basic implementation of a client-server chat application in Java. The application allows multiple clients to connect to a server and exchange messages in a chat-like interface.

## Files

- `Client.java`: Contains the implementation of the chat client.
- `Server.java`: Contains the implementation of the chat server.

## How to Run

### Server

1. Open a terminal and navigate to the directory containing `Server.java`.
2. Compile the server code using the following command:
   
    javac Server.java

3. Run the server using the following command:
   
    java Server

The server will start, and it will listen for incoming connections on port 9999.

Client

1. Open a new terminal window and navigate to the directory containing Client.java.
2. Compile the client code using the following command:

     javac Client.java
   
4. Run the client using the following command:

     java Client

 The client will connect to the server at 127.0.0.1:9999. You can run multiple instances of the client to simulate multiple users in the chat.

Usage

  -Once the client is running, it will prompt you to enter a nickname.
  -You can send messages to the chat by typing them in the terminal and pressing Enter.
  -To change your nickname, type /nick newnickname and press Enter.
  -To quit the chat, type /q and press Enter.

Important Notes

   -Ensure that you have Java installed on your system.
   -The server and client must be run on the same machine.
   -Adjust firewall settings if necessary to allow connections on port 9999.
