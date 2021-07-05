#  CRUD

## Which HTTP Status Code to Use for Every CRUD App

> The HTTP specification defines many status codes we can use when responding to our clients. Some APIs only use the most basic codes and define their own error signaling mechanisms on top of it; others want to make full use of HTTPs collection of codes to tell their clients what’s going on. If you belong to the latter, this article is for you. This guide walks through the various CRUD operations and which status codes you should be using for clean API design.



## CRUD (Create, Read, Update, Delete)Permalink

> The CRUD model defines the most basic API actions for persistent storage. Create, read, update, and delete. They make up the lions-share of API endpoints. Let’s see which status codes meet their requirements.



## CREATE

Status Codes

- 200 OK - It’s the basic status code to tell the client everything went good. Since we don’t create endpoint accessible resource when creating an access token, we can use 200 as a status for that action.
- 201 Created - The most fitting for Create operations. This code should signal backend-side resource creation and come along with a Location header that defines the most specific URL for that newly created resource. It’s also a good idea to include appropriate representation of the resource or at least one or more URLs to that resource in the response body.
- 202 Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.
- 303 See Other - Like the 202 code but using a Location header field in response to informing the client about the location of the created resource or an endpoint that lets the client check for the status of the creation process. Some clients follow the status codes of the Redirect-class automatically. This code is usually only used for POST requests.

## API ChangesPermalink
> If our API lives long enough, sooner or later it will change its structure. It’s best practice to avoid breaking changes and the redirection class of status codes can help with this because some clients follow their Location header automatically.

## Wrong URLPermalink

> When a client sends a URL, we don’t know. This can have multiple different reasons, so we have to check which of them applies here.

![](https://1.bp.blogspot.com/-NES44rDk7aY/XpsSeVDaRdI/AAAAAAAAHqc/BQ4NIgGXBtEVmilZbvazluMNAd06L5o6wCLcBGAsYHQ/s1600/api-list.PNG)

<hr>

### To know more about Build A REST API With Node.js, Express, & MongoDB -Quick [CLICK HERE](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)


<hr>

## Things I want to know more about

_I want to know more about using CRUD in real APP_