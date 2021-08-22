# Socket-io


## What is the benefit of transforming data into packets?
>  Data packets. The main purpose of networking is to share data between computers. A file has to be broken up into small chunks of data known as data packets in order to be transmitted over a network. 

## UDP is often refereed to as a connectionless protocol. Why is this?

> UDP does not provide error correction and is therefore an unreliable protocol. In other words, delivery of packets is not guaranteed. UDP datagrams are transmitted without provision for an acknowledgment. Because there is no virtual connection between sender and receiver, UDP is also said to be connectionless.

## Can a socket server application have multiple socket connections?

> Yes. Multiple listening TCP sockets, all bound to the same port, can co-exist, provided they are all bound to different local IP addresses. Clients can connect to whichever one they need to.

## Can a socket connection application be connected to multiple socket servers?


> Yes, you can create a server socket that can handle multiple clients simultaneously.

## Can an application be both a socket server and a socket connection?

> Yes and no. It isn't very clear what you're trying, though. So the answer isn't very clear either.
However, if you want to use a client socket and a server socket within a single application, then yes! You can do that if you're willing to use two different ports

<hr>


- Observer Pattern : The Observer Pattern is an appropriate design pattern to apply in any situation where you have several objects which are dependent on another object and are required to perform an action when the state of that object changes, or an object needs to notify others without knowing who they are or how many there are

- Listener :
The event listener is a hook in the event method that's called on each event firing that calls the event handler

- Event Handler : 
You can define Event handlers, scripts that are automatically executed when an event occurs. Event handlers are embedded in documents as attributes of HTML tags to which you assign JavaScript code to execute

- Event Driven Programming: 
Event-driven programming is a programming paradigm in which the flow of program execution is determined by events 

- Event Loop :The event loop is the secret behind JavaScript's asynchronous programming. ... The event queue is responsible for sending new functions to the track for processing.

- Event Queue : An event queue is a repository where events from an application are held prior to being processed by a receiving program or system. Event queues are often used in the context of an enterprise messaging system

- Call Stack : 
A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions

- Emit/Raise/Trigger : event function

- Subscribe : 
In software architecture, publish–subscribe is a messaging pattern where senders of messages, called publishers

- database : A database is an organized collection of structured information, or data, typically stored electronically in a computer system. 

<hr>

### Which 3 things had you heard about previously and now have better clarity on?
1. Event Loop 
2. Subscribe 
3. Event Handler

### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
1. using  Emit/Raise/Trigger 
2. Event Driven Programming
3. Event Handler

### What are you most excited about trying to implement or see how it works?

- learning more about Event Driven Programming and how to use correctly 

<hr>

## WebSocket : 
> WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011, and the WebSocket API in Web IDL is being standardized by the W3C.

## Difference Between WebSocket and Socket.io

- WebSocket is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection

- Socket-IO is a library that enables real-time and full-duplex communication between the Client and the Web servers. It uses the WebSocket protocol to provide the interface. Generally, it is divided into two parts; both WebSocket vs Socket-io are event-driven libraries.

![](https://cdn.educba.com/academy/wp-content/uploads/2018/11/WebSocket-protocol-schema.png)

1. Client-Side: it is the library that runs inside the browser
2. Server Side: It is the library for Node.js

![](https://cdn.educba.com/academy/wp-content/uploads/2018/11/WebSockets-vs-Socket-1.jpg.webp)
