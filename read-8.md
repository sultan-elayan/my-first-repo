#  Authorization/Authentication


## What header(s) are used in authentication and authorization

> In basic HTTP authentication, a request contains a header field in the form of Authorization: Basic <credentials> , where credentials is the Base64 encoding of ID and password joined by a single colon 

## What is safe to put into a JWT

> 
A JWT needs to be stored in a safe place inside the user's browser. ... To keep them secure, you should always store JWTs inside an httpOnly cookie. This is a special kind of cookie that's only sent in HTTP requests to the server. It's never accessible (both for reading or writing) from JavaScript running in the browser

## How are JWTs validated

> 
When you receive a JWT from the client, you can verify that JWT with this that secret key stored on the server. Any modification to the JWT will result in verification (JWT validation) failure. A JWT is simply a string but it contains three distinct parts separated with dots (.)

<hr>
<hr>

- RBAC : Role-based access control

![](https://sites.google.com/site/cacsolin/_/rsrc/1261008425131/role-based-access-control/Role%20Based%20Access%20Control.png)

- User Roles : 
A permission is the right to access one or more system objects. A role is a group of permissions.

![](https://help.falcon.io/hc/article_attachments/4402733790737/Manage-v5.jpg)

- JWT Token: JSON Web Token (JWT) access tokens conform to the JWT standard and contain information about an entity in the form of claims. 

![](https://miro.medium.com/max/2000/1*RvUzEHQi5JEifWCBY4Rkng.png)

<hr>
<hr>

- ## Which 3 things had you heard about previously and now have better clarity on?
1.how is Role-based access control working
2. deferent between Role-based access control and Special gate in some websites
3. cookies 

- ## Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
1. what cookies contain also
2. how to build more RBAC web app
3. JWT Token

- ## What are you most excited about trying to implement or see how it works?

- how can get benefit from the cookies