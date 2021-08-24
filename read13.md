#  Event Driven Architecture

## What’s the difference between a FIFO and a standard queue?

> Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it; duplicates are not introduced into the queue

## How can the server be assured a message was properly received?

> by giving back to message queue that he received the message

## What classic design pattern is best represented by event driven programming?

> One of the most popular design patterns used by software developers is a factory method. It is a creational pattern that helps create an object without the user getting exposed to creational logic. The only problem with a factory method is it relies on the concrete component 

## How do you test an event driven system?

> by adding test file and testing it with jest library 


<hr>


- Term : 
Code or source code is a term used to describe a written set of instructions, written using the protocols of a particular language 

- FIFO Queue : A FIFO queue is a queue that operates on a first-in, first-out (FIFO) principle. This means that the request (like a customer in a store or a print job sent to a printer) is processed in the order in which it arrives.

- Pub/Sub : Publish/subscribe messaging, or pub/sub messaging, is a form of asynchronous service-to-service communication used in serverless and microservices architectures. In a pub/sub model, any message published to a topic is immediately received by all of the subscribers to the topic

<hr>

- Which 3 things had you heard about previously and now have better clarity on?

1. FIFO Queue
2. microservices architectures
3. Publish/subscribe messaging,

- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

1. FIFO Queue
2. microservices architectures
3. Publish/subscribe messaging


- What are you most excited about trying to implement or see how it works?

- microservices architectures

<hr>

## SNS and SQS

### SNS is a distributed publish-subscribe service.

> Amazon SNS is a fast, flexible, fully managed push notification service that lets you send individual messages or to bulk messages to large numbers of recipients. Amazon SNS makes it simple and cost effective to send push notifications to mobile device users, email recipients or even send messages to other distributed services.

![](https://miro.medium.com/max/452/1*mdUPKzrfJFuXa4d43KhKUQ.png)


### SQS is distributed queuing service.

> SQS is distributed queuing system. Messages are not pushed to receivers. Receivers have to poll SQS to receive messages. Messages can’t be received by multiple receivers at the same time. Any one receiver can receive a message, process and delete it. Other receivers do not receive the same message later.
Polling inherently introduces some latency in message delivery in SQS unlike SNS where messages are immediately pushed to subscribers.

![](https://miro.medium.com/max/630/1*7eL3udb6Cto4I9Ly1sN8oA.jpeg)
