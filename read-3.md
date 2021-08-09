# Express REST API 

## Name 3 real world use cases where you’d want to change the request with custom middleware

## 1. Translator
> There are many data-interchange formats, such as JSON, XML and Protobuf. Even though we mostly use JSON nowadays, each of them have their own use cases.

![](https://www.freecodecamp.org/news/content/images/2020/08/0.png)

## 2. Accumulating-Duplicating Data
> Microservice architecture is a popular architectural pattern that is commonly applied in modern applications.

![](https://www.freecodecamp.org/news/content/images/2020/08/3-6.png)

## 3. API Security
> For any front end client-side code, we can view the outgoing requests, either in the browser's console or via a proxy.

<hr>
<hr>

## True or false: The route handler is middleware?

## Answer Is TRUE 

![](https://static.packt-cdn.com/products/9781849696548/graphics/6548_03_04.jpg)

<hr>

## In what ways can a middleware function end the process and send data to the browser?

> Middleware functions are functions that have access to the request object (req), the response object (res), and the next function in the application’s request-response cycle. The next function is a function in the Express router which, when invoked, executes the middleware succeeding the current middleware.

<hr>

## At what point in the request lifecycle can you “inject” middleware?

> in Session Provider before the request

<hr>

## What can cause express to error with “Request headers sent twice, cannot start a second response”

>In your case, you called res.redirect(), which caused the response to become Finished. Then your code threw an error (res.req is null). and since the error happened within your actual function(req, res, next) (not within a callback)

<hr>
<hr>


| Syntax      | Description |
| ----------- | ----------- |
| Middleware  | Middleware is software that enables one or more kinds of communication or connectivity between two or more applications or application components in a distributed network.     |
| Request Object  | The request object allows you to submit a POST or GET request to an URL. Essentially it provides a way to make REST API requests to another URL.    |
| Response Object |  It is the object which communicates between the server and the output which is sent to the client |
| Application Middleware  |  Enterprise application integration is an integration framework composed of a collection of technologies and services which form a middleware or “middleware framework” to enable integration of systems and applications across an enterprise.      |
| Routing Middleware  | Routing defines the way in which the client requests are handled by the application endpoints. And when you make some routers in separate file, you can use them by using middleware.     |
| Test Driven Development  | s a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases.      |
| Behavioral Testing  | Behavioral Testing is a testing of the external behavior of the program, also known as black box testing. It is usually a functional testing.     |

<hr>
<hr>


## Question section

1. Which 3 things had you heard about previously and now have better clarity on?

> - copying command in terminal 
> - exporting models directly 
> - REST methods

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
> - using the RESTFUL architecture
> - using the middleware as authenticated 
> - mocking codes

3. What are you most excited about trying to implement or see how it works?

> - how to use middleware functions to make authenticated request


