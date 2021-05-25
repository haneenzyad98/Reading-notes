# Message Queues

A message queue is a queue of messages sent between applications. It includes a sequence of work objects that are waiting to be processed. A message is the data transported between the sender and the receiver application; it's essentially a byte array with some headers at the top.

## Review, Research, and Discussion

- What does it mean that web sockets are bidirectional? Why is this useful?


 An important consequence is that you may efficiently push data from the server to the client. ... It must be handled both client-side and server-side

 - Does socket.io use HTTP? Why?


Even when websockets can be used, the initial connection setup it done over HTTP.

- What happens when a client emits an event?

emit() to send a message to all the connected clients. 

- Socket

 one endpoint of a two-way communication link between two programs running on the network.

 - Web Socket


 makes it possible to open a two-way interactive communication session between the user's browser and a server. 
 

 - Socket.io

Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server.

- Client

a person who receives services

- Server

 computer hardware or software (computer program) that provides functionality for other programs or devices, called "clients". This architecture is called the client–server model. Servers can provide various functionalities, often called "services", such as sharing data or resources among multiple clients, or performing computation for a client.


 - OSI Model


The physical layer.

The data link layer.

The network layer. 

The transport layer. 

The session layer. 

The presentation layer. 

The application layer. This is the only layer that directly interacts with data from the user.

- TCP Model


it stands for Transmission Control Protocol/Internet Protocol. The TCP/IP model is a concise version of the OSI model. It contains four layers


![img](https://www.guru99.com/images/1/093019_0615_TCPIPModelW2.png) 


- TCP

Transmission Control Protocol (TCP) is one of the main protocols of the Internet protocol suite.

TCP is connection-oriented, and a connection between client and server is established before data can be sent. 

- UDP


UDP (User Datagram Protocol) is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet. It speeds up transmissions by enabling the transfer of data before an agreement is provided by the receiving party.

![img](https://www.educative.io/api/edpresso/shot/5669375870763008/image/5080565785034752) 



- Packets


packet is a small segment of a larger message. Data sent over computer networks*, such as the Internet, is divided into packets. These packets are then recombined by the computer or device that receives them


