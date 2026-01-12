# Java-Socket-Chat-Room
# JavaSocketGroupChat

A Java-based command-line group chat application built using socket programming and a client–server architecture.  
The server supports multiple concurrent clients and enables real-time message broadcasting similar to a group chat system.

JavaSocketGroupChat allows multiple clients to connect to a central server and communicate with each other in real time.  
Messages sent by one client are broadcast to all connected clients. The server uses multi-threading to handle multiple users simultaneously without interruption.

Clients can leave the chat gracefully by typing stop, while the server continues running for remaining users.


 -Multi-client support using Java Sockets  
 -Real-time group messaging  
- Client–server architecture  
- Multi-threaded server for concurrent connections  
- Graceful client exit using stop command  
- Command-line based interface  


* Technologies Used

- Java  
- Socket Programming (TCP/IP)  
- Multi-threading  
- Input/Output Streams  


* How It Works

1. The server starts and listens on a specified port.
2. Clients connect to the server using the server IP and port number.
3. Each client runs on a separate thread.
4. Messages from any client are broadcast to all connected clients.
5. Typing stop disconnects a client safely from the chat.


 1. Compile the Server and Client
javac MyServer.java
javac MyClient1.java
