# Event Driven Applications

## Why is access control important?

> The main purpose of access control is to provide security by allowing or restricting access to these resources by any party or individua

## Describe an application that would need access control.

> our college website , there is role for student to track his course and TA role to grade him and instructor to edit course data , so we need permission for every one of us 

## What is a role used for?
 
 > A role is a collection of privileges that can be granted to one or more users or other roles. Roles help you grant and manage sets of privileges for various categories of users,

## Why is role based access control more scalable than discretionary or mandatory access control?

> 
For most business applications, RBAC is superior to ACL in terms of security and administrative overhead. ACL is better suited for implementing security at the individual user level and for low-level data, while RBAC better serves a company-wide security system with an overseeing administrator.

<hr>


- Term :
A term is a word or expression with a specific meaning, especially one which is used in relation to a particular subject. 

- Authorization :
Authorization is the process of giving someone permission to do or have something. ... Thus, authorization is sometimes seen as both the preliminary setting up of permissions by a system administrator and the actual checking of the permission values that have been set up when a user is getting access.

- Role Based Access Control : 
Image result for Role Based Access Control
Role-based access control (RBAC) is a method of restricting network access based on the roles of individual users within an enterprise

- Capabilities : A capability (known in some systems as a key) is a communicable, unforgeable token of authority. It refers to a value that references an object along with an associated set of access rights. 

<hr>

## Which 3 things had you heard about previously and now have better clarity on?

1. deferent between ACL and RBAC
2. why we use ACL 
3. why we use RABC

## Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

1. using RABC in our class
2. learn more about setting the role
3. how to make ACL easier to the user 

## What are you most excited about trying to implement or see how it works?
- sending the token automatically with every request 

<hr>

## Event-Driven Programming in Node.js

> A style of coding where a program's overall flow of execution is dictated
by events.
• The program loads, then waits for user input events.
• As each event occurs, the program runs particular code to respond.
• The overall flow of what code is executed is determined by the series
of events that occur
• Contrast with application- or algorithm-driven control where
program expects input data in a pre-determined order and timing
– Typical of large non-GUI applications like web crawling, payroll,
batch simulation

> ### • event: An object that represents a user's interaction with a GUI
component; can be "handled" to create interactive components.
> ### • listener: An object that waits for events and responds to them.
> – To handle an event, attach a listener to a component.

> – The listener will be notified when the event occurs (e.g. button
click).

![](https://i.ytimg.com/vi/SnO9dTbF6hM/maxresdefault.jpg)

