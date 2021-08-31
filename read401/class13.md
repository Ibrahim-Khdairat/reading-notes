# READ 13 : Message Queues

![img](https://www.cloudamqp.com/img/blog/thumb-mq.jpg)

# Review, Research, and Discussion

## 1- What does it mean that web sockets are bidirectional? Why is this useful?

   *  it means communication flows both ways between a server and client

   *  this is useful because a conversation can be kept going between a server and client

   *  It enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time. In the context of networked AV and control systems, this allows devices to send and receive continuous streams of data to and from any point on the network.

## 2- Does socket.io use HTTP? Why?

    a socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js ( to communication with clients.).

## 3- What happens when a client emits an event?
    The client emits an event and then the server handles the event using the on method.it would go the event handler

## 4- What happens when a server emits an event?

    Server emits the event and it is handled by the client side(The server emits an event and then the client that the event was emitted to handles the event.)

## 5- What happens if a client “misses” an event?
    Unhandled messages are just ignored. It's just like when an event occurs and there are no event listeners for that event. The socket receives the msg and doesn't find a handler for it so nothing happens with it (Nothing. The event will be ignored if it is missed.)

## 6- How can we mitigate this?
    We could assign unique IDs to events in order to track them, log events, and make sure the client recieved the event.(You could avoid missing messages by always having the handlers installed and then deciding in the handlers (based on other state) whether to do anything with the message or not.)

# Document the following Vocabulary Terms

## Socket : 

    A socket is one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to. An endpoint is a combination of an IP address and a port number.( serves as an endpoint for sending and receiving data across the network.)

## Web Socket :

    WebSocket is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection; WebSocket remains open all the time, so they allow real-time data transfer. When clients trigger the request to the server, it does not close the connection on receiving the response; it rather persists and waits for the Client or server to terminate the request. (A communication protocol for establishing a connection for servers and clients to transmit data)

## Socket.io : 

    a library that enables real-time and full-duplex communication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface. Generally, it is divided into two parts; both WebSocket vs Socket.io are event-driven libraries(A javascript library for realtime, bi-directional communication between servers and clients).

## Client: 

    it is the library that runs inside the browser(Accesses services or functionality from server)

## Server : 
It is the library for Node.js(Provides services and functionality for clients)

## OSI Model :

    (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system. The OSI model characterizes computing functions into a universal set of rules and requirements in order to support interoperability between different products and software.

 Physical Layer -> Data Link Layer -> Network Layer -> Transport Layer -> Session Layer -> Presentation Layer -> Application Layer


## TCP Model:

    specifications for translating the network addressing methods used in the Internet Protocol to link-layer addresses, such as media access control (MAC) addresses.

 Network Access Layer -> Internet Layer -> Transport Layer -> Application Layer

## TCP: 

    Transmission control protocol. TCP provides reliable, ordered, and error-checked delivery of a stream of octets (bytes) between applications running on hosts communicating via an IP network. (Transmission Control Protocol - a connection-based communication protocol used for the transmission of data within a network.)

## UDP :

    (User Datagram Protocol) is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet. It speeds up transmissions by enabling the transfer of data before an agreement is provided by the receiving party.(a connectionless communication protocol used for time-sensitive transmission of data.)

## Packets :

 a formatted unit of data carried by a packet-switched network. A packet consists of control information and user data; the latter is also known as the payload. Control information provides data for delivering the payload

# Preview

## Which 3 things had you heard about previously and now have better clarity on?

   TCP, OSI model, web sockets

## Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

   How to mitigate clients missing events, using socket.io with an api, broadcasting events

## What are you most excited about trying to implement or see how it works?

   A real-time chatroom or messaging queue