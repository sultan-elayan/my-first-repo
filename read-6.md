# Bearer Authorization

## Write the following steps in the correct order:

1. Ask the client if they want to sign in via a third party
2. Register your application to get a client_id and client_secret
3. Redirect to a third party authentication endpoint
4. Make a request to a third-party API endpoint
5. Make a request to the access token endpoint
6. Receive authorization code
7. Receive access token


## What can you do with an authorization code?

> Authorization codes are used for any transaction or entry that has restrictions on which users are entitled to access.

## What can you do with an authorization code?

> Access tokens must be kept confidential in transit and in storage. The only parties that should ever see the access token are the application itself

## What’s a benefit of using OAuth instead of your own basic authentication?

> OAuth doesn't share password data but instead uses authorization tokens to prove an identity between consumers and service providers. OAuth is an authentication protocol that allows you to approve one application interacting with another on your behalf without giving away your password.

![](https://d33wubrfki0l68.cloudfront.net/ffe0e3332e89626da57e5a6f74194cffb2535183/23da3/assets-jekyll/browser_spa_implicit_flow-9116158c9299208718b42a75921acd10a60e4c829edee55a8f14a9ce8de40028.png)

<hr>

- Client ID :
The Client ID (cid) is a unique identifier for a browser–device pair that helps Google Analytics link user actions on a site. By default

- Client Secret : The client ID and secret is unique to the client application on that authorization server.

- Authentication Endpoint : 
Endpoint authentication is a security mechanism designed to ensure that only authorized devices can connect to a given network, site or service.

- Access Token Endpoint :
The token endpoint is where apps make a request to get an access token for a user. This section describes how to verify token requests and how to return the appropriate response and errors.

- API Endpoint : An API Endpoint is the URL for a server or a service. These APIs operate through responses and requests — that is you make a request and the API Endpoint makes a response

- Authorization Code : The authorization code is a temporary code that the client will exchange for an access token.

- Access Token : 
Access tokens are used in token-based authentication to allow an application to access an API. 

<hr>

## Which 3 things had you heard about previously and now have better clarity on?

1. access token 
2. deferent between authorization and authentications
3. Client Secret

## Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

- learn more about access token 
- how to secure accounts
- if there any authorization cloud service 

## What are you most excited about trying to implement or see how it works?

- the access token 