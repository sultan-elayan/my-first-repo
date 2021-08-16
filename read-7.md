#  Access Control (ACL) 


## When is Basic Authorization used vs. Bearer Authorization?

> The Basic and Digest authentication schemes are dedicated to the authentication using a username and a secret (see RFC7616 and RFC7617).

The Bearer authentication scheme is dedicated to the authentication using a token and is described by the RFC6750.

![](https://www.okta.com/sites/default/files/styles/1640w_scaled/public/media/image/2020-10/Authentication_vs_Authorization.png?itok=uBFRCfww) 

## What does the JSON Web Token package do?

>  defines a compact and self-contained way for securely transmitting information between parties as a JSON object. 


![](https://miro.medium.com/max/630/0*d3B1kfFX_8arebDR.)

## What considerations should we make when creating and storing a SECRET?


- Never store unencrypted secrets in .git repositories
- Don’t share your secrets unencrypted in messaging systems like slack
- Restrict API access and permissions


<hr>

- encryption :Encryption is the process of taking plain text, like a text message or email, and scrambling it into an unreadable format

- token: In general, a token is an object that represents something else, such as another object (either physical or virtual), or an abstract concept

- bearer : Bearer authentication (also called token authentication) is an HTTP authentication scheme that involves security tokens called bearer tokens

- secret : 
Secret key is used for Private key cryptography. A private key, also known as a secret key, is a variable in cryptography that is used with an algorithm to encrypt and decrypt code

- JSON Web Token : which defines a compact and self-contained method to encapsulate and share assertions (claims) about an entity (subject) between peers in a secure manner by using JSON objects

<hr>

## Which 3 things had you heard about previously and now have better clarity on?

1. secret key and how to use it 
2. the idea of bearer
3. web access token

## Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

1. jwt types 
2. how to hack wen access token 
3. encrypting data methods

## What are you most excited about trying to implement or see how it works?

- the pattern thumb key access 


<hr>

## Role Based Access Control

> user -> role -> rights

### RBAC

![](https://lh4.ggpht.com/_0hUssIlWt_o/Syl2TpMYHRI/AAAAAAAAAAU/X872p5_OlsY/s1600/Role%20Based%20Access%20Control%20In%20Action.png)

>  is nothing more than the idea of assigning system access to users based on their role within an organization. The system needs of a given workforce are analyzed, with users grouped into roles based on common job responsibilities and system access needs. Access is then assigned to each person based strictly on their role assignment. With tight adherence to access requirements established for each role, access management becomes much easier.

- Access control lists (ACL) — An ACL is a means of defining access rights by a given user or user group

- Attribute-based access control (ABAC) — ABAC, sometimes known as policy-based access control


## 5 steps to RBAC

1. Inventory your systems
2. Analyze your workforce and create roles
3. Assign people to roles
4. Never make one-off changes
5. Audit


