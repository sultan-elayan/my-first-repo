#  AWS: API, Dynamo and Lambda

- What are serverless functions? 

> A serverless function is a programmatic function written by a software developer for a single purpose. It's then hosted and maintained on infrastructure by cloud computing companies. These companies take care of code maintenance and execution so that developers can deploy new code faster and easier.

- If you were to create a system that emulated Lambda functions,  how would you do it?

1. Open the Functions page on the Lambda console.

2. Choose Create function.

3. Under Basic information, do the following:

- a : For Function name, enter my-function.

- b: For Runtime, confirm that Node.js 14.x is selected.
 Note that Lambda provides runtimes for .NET (PowerShell, C#), Go, Java, Node.js, Python, and Ruby.

4. Choose Create function.

- Describe how a CDN works

> The most common use case of a CDN is to cache content and deliver it to the end-user, reducing the page load time. This means that the content should be cached on the CDN edge as long as possible. ... For example, your CDN has stored, on its edge servers, a copy of the black Nike running shoe that we talked about earlier

<hr>

- Serverless Functions : 
A serverless function is a programmatic function written by a software developer for a single purpose. It's then hosted and maintained on infrastructure by cloud computing companies. These companies take care of code maintenance and execution so that developers can deploy new code faster and easier

- Cloud Storage : 
Cloud storage is a cloud computing model that stores data on the Internet through a cloud computing provider who manages and operates data storage as a service. It's delivered on demand with just-in-time capacity and costs, and eliminates buying and managing your own data storage infrastructure.

- CDN :  
A CDN (Content Delivery Network) is a highly-distributed platform of servers that helps minimize delays in loading web page content by reducing the physical distance between the server and the user. ... Without a CDN, content origin servers must respond to every single end user request.

<hr>

## Amazon API Gateway

> 
An API gateway is an API management tool that sits between a client and a collection of backend services. An API gateway acts as a reverse proxy to accept all application programming interface (API) calls, aggregate the various services required to fulfill them, and return the appropriate result.

![](https://d2908q01vomqb2.cloudfront.net/1b6453892473a467d07372d45eb05abc2031647a/2018/06/13/api-backends.png)


## What is DynamoDB?

> DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS)

> Amazon DynamoDB is a key-value and document database that delivers single-digit millisecond performance at any scale. It's a fully managed, multi-region, multi-active, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications. DynamoDB can handle more than 10 trillion requests per day and can support peaks of more than 20 million requests per second.

## Dynamoose

> Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familar.

- Type safety
- High level API
- Easy to use syntax
- Ability to transform data before saving or retrieving documents
- Strict data modeling (validation, required attributes, and more)
- Support for DynamoDB Transactions
- Powerful Conditional/Filtering Support
- Callback & Promise support