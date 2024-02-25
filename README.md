# Socket Programming in C/C++

In C++, socket programming is a method that combines two or more nodes with each other over a network so that the nodes can share the data without any loss of the data. In this connection, one node listens to one port which is connected to a particular IP address. When the client reaches the server, the server creates the socket listener.

## What is a Socket?

 The socket is a type of mechanism that is used to exchange data between different processes. Here these processes are either present in different devices or the same device which are connected over a network. Once the connection for the socket is created, then the data can be sent in both directions and continues until one of the endpoints closes the connection.

### ![Capture d'écran 2024-02-25 154432](https://github.com/zaid1729/Socket_Connection/assets/107809533/c0dac561-c8f5-4a39-8e37-f589b1f37924)


## Procedure in Client-Server Communication

There are some procedures that we have to follow to establish client-server communication. These are as follows.

* Socket: With the help of a socket, we can create a new communication.
* Bind: With the help of this we can, we can attach the local address with the socket.
* Listen: With this help; we can accept the connection.
* Accept: With this help; we can block the incoming connection until the request arrives.
* Connect: With this help; we can attempt to establish the connection.
* Send: With the help of this; we can send the data over the network.
* Receive: With this help; we can receive the data over the network.
* Close: With the help of this, we can release the connection from the network.




