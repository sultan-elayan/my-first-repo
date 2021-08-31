# Events

### Describe the similarities between AWS 
API Gateway + Lambda functions and an ExpressJS Server

- Key Authentication	✅	✅

- HTTPS	✅	✅

- CORS	✅	✅

- oAuth2	✅	⚠️**2

- Finegrain Access Control	✅	✅

- Rate Limiting✅	✅

### List the AWS Database offerings and talk about the pros and cons of each

[click to see the answer ](https://sarasanalytics.com/blog/amazon-rds-pros-and-cons)

### What’s the difference between a FIFO and a standard queue?


[click to see the answer ](https://medium.com/awesome-cloud/aws-difference-between-sqs-standard-and-fifo-first-in-first-out-queues-28d1ea5e153#:~:text=Standard%20queues%20guarantee%20that%20a,not%20introduced%20into%20the%20queue.)



### How can the server be assured a message was properly received?

> by using RESTful API

<hr>

- Serverless API : Serverless is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers. A serverless application runs in stateless compute containers that are event-triggered, ephemeral (may last for one invocation), and fully managed by the cloud provide

- Triggers : Triggers are functions registered against a database operation. They are executed in response to the operation being performed, hence 'triggering' the function. They are triggered whenever a data element is updated, added or deleted allowing the 

- Dynamo vs Mongo : 
1. MongoDB is vendor agnostic, Open Source, and can be deployed anywhere. DynamoDB is only available on AWS.
2. DynamoDB is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas.
3. DynamoDB as an integrated AWS service makes it easier to develop end to end solutions.
4. DynamoDB uses tables, items and attributes, MongoDB uses JSON-like documents.
5. DynamoDB supports limited data types and smaller item sizes; MongoDB supports more data types and has fewer size restrictions.


- Dynamoose vs Mongoose :

1. Dynamoose to use dynnodb 
2. Mongoose to use mongodbb

<hr>


## SNS and SQS

### SNS is a distributed publish-subscribe service.

> Amazon SNS is a fast, flexible, fully managed push notification service that lets you send individual messages or to bulk messages to large numbers of recipients. Amazon SNS makes it simple and cost effective to send push notifications to mobile device users, email recipients or even send messages to other distributed services.

![](https://miro.medium.com/max/452/1*mdUPKzrfJFuXa4d43KhKUQ.png)


### SQS is distributed queuing service.

> SQS is distributed queuing system. Messages are not pushed to receivers. Receivers have to poll SQS to receive messages. Messages can’t be received by multiple receivers at the same time. Any one receiver can receive a message, process and delete it. Other receivers do not receive the same message later.
Polling inherently introduces some latency in message delivery in SQS unlike SNS where messages are immediately pushed to subscribers.

![](https://miro.medium.com/max/630/1*7eL3udb6Cto4I9Ly1sN8oA.jpeg)

