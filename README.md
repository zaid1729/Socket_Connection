# Socket Programming in C/C++

In C++, socket programming is a method that combines two or more nodes with each other over a network so that the nodes can share the data without any loss of the data. In this connection, one node listens to one port which is connected to a particular IP address. When the client reaches the server, the server creates the socket listener.

## What is a Socket?

 The socket is a type of mechanism that is used to exchange data between different processes. Here these processes are either present in different devices or the same device which are connected over a network. Once the connection for the socket is created, then the data can be sent in both directions and continues until one of the endpoints closes the connection.

### ![Capture d'écran 2024-02-25 154432](https://github.com/zaid1729/Socket_Connection/assets/107809533/c0dac561-c8f5-4a39-8e37-f589b1f37924)


## Procedure in Client-Server Communication

There are some procedures that we have to follow to establish client-server communication. These are as follows.

1. Socket: With the help of a socket, we can create a new communication.
2. Bind: With the help of this we can, we can attach the local address with the socket.
3. Listen: With this help; we can accept the connection.
4. Accept: With this help; we can block the incoming connection until the request arrives.
5. Connect: With this help; we can attempt to establish the connection.
6. Send: With the help of this; we can send the data over the network.
7. Receive: With this help; we can receive the data over the network.
8. Close: With the help of this, we can release the connection from the network.

## Stages for Server Socket Creation

There are some stages by which we can create the socket for the server. These are as follows : 

1. int socketcr: Socket(domain, type, protocol).
2. Socketcr: It is an integer type, and it is like a file handler.
3. Domain: It is a communication domain and it is an integer type.
4. Type:It is a communication type.
5. SOCK_DGRAM: It is a type of UDP which is unreliable and connectionless.
6. Protocol: It is used to assign the protocol value for the IP address, which is 0. The protocol value is similar to the value appearing in the protocol field of the IP header of the pocket.


## Compiling:

   ` gcc client.c -o client `
    
   ` gcc server.c -o server `

## Output:

    Client : Hello message sent 
    Hello from server 
    Server : Hello from client
    Hello message sent 




