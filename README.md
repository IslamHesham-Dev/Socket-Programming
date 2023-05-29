# Socket-Programming
The World Wide Web and Internet has changed the way we live and communicate with each 
other and the way we conduct science, engineering, and commerce. The modern life is 
completely being driven around or being centered around the Internet. Businesses are 
continuously seeking new ways to produce and communicate with various services in a new 
fashion introducing innovation.
Socket programming is a way of connecting two nodes on a network to communicate with 
each other. Through socket (door) listens on a particular port at an IP, while other socket 
reaches out to the other to form a connection (TCP) or connection-less oriented (UDP). Server 
forms the listener socket while client reaches out to the server.

Java Socket programming is used for communication between the applications running on different JRE.

Java Socket programming can be connection-oriented or connection-less.

Socket and ServerSocket classes are used for connection-oriented socket programming and DatagramSocket and DatagramPacket classes are used for connection-less socket programming.

The client in socket programming must know two information:

IP Address of Server, and
Port number.
Here, we are going to make one-way client and server communication. In this application, client sends a message to the server, server reads the message and prints it. Here, two classes are being used: Socket and ServerSocket. The Socket class is used to communicate client and server. Through this class, we can read and write message. The ServerSocket class is used at server-side. The accept() method of ServerSocket class blocks the console until the client is connected. After the successful connection of client, it returns the instance of Socket at server-side.
