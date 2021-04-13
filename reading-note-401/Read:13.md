## Read 13

# Message Queues

### What does it mean that web sockets are bidirectional? Why is this useful?
Whereas HTTP relies on a client request to receive a response from the server for every exchange, WebSockets allow for 
full-duplex bidirectional communication.

### Does socket.io use HTTP? Why?
Even when websockets can be used, the initial connection setup it done over HTTP. Also, a socket.io server will attach to an 
HTTP server so it can serve its own client code through /socket.io/socket.io.js .

### What happens when a server emits an event?
The event gets passed to the server through websockets. Its a tcp connection from the browser to the server.

### What happens if a client “misses” an event?
it will be ignored

## Term

### Socket
is a way of connecting two nodes on a network to communicate with each other.

### Web Socket
WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

### Socket.io
Socket.IO is a library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers. 

### Client
a client is a piece of computer hardware or software that accesses a service made available by a server as part of the client–server 
model of computer networks.

### Server
a server is a piece of computer hardware or software that provides functionality for other programs or devices, called "clients". 

### OSI Model
The Open Systems Interconnection model is a conceptual model that characterises and standardises the communication functions of a 
telecommunication or computing system without regard to its underlying internal structure and technology

### TCP Model:
The Internet protocol suite is the conceptual model and set of communications protocols used in the Internet and similar computer networks.

### TCP
The Transmission Control Protocol is one of the main protocols of the Internet protocol suite. It originated in the initial network 
implementation in which it complemented the Internet Protocol.

### UDP
 User Datagram Protocol is one of the core members of the Internet protocol suite.
 
 ### Packets
 In telecommunications and computer networking, a network packet is a formatted unit of data carried by a packet-switched network.
 
 ## Preparation Materials
 
 ### Socket.io Chat 
 Writing a chat application with popular web applications stacks like LAMP (PHP) has normally been very hard. It involves polling the 
 server for changes, keeping track of timestamps, and it’s a lot slower than it should be.
 
 ### Rooms and Namespaces
 A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients

 
