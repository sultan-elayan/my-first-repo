# Project Kickoff

## How the Web works
### HTML Basics: Elements, Tags, and Document Structure
> HTML stands for HyperText Markup Language and is the basic structural element that is used to create webpages. HTML is a markup language, which means that it is used to “mark up” the content within a document, in this case a webpage, with structural and semantic information that tells a browser how to display a page.

![](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works/simple-client-server.png)

![](https://www.tutorialrepublic.com/lib/images/html-illustration.png)

<hr>

# State and Props

## What are component lifecycle events?
> React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

![](https://miro.medium.com/max/700/0*_UWbSFyhbBMVeCkj.jpeg)

- Mounting
> When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase.


- Updating
> Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.


- Unmounting
> The final phase of the lifecycle if called when a component is being removed from the DOM


- Mounting
> When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase.

<hr>

# Passing Functions as Props

## What does .map() 
> The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.

![](https://www.codeproject.com/KB/combobox/1255451/render-a-list-r-700.png)



##  display each value in JSX
> .map() in JavaScript iterates through an array and calls a specified function for each of the items. Components in JSX are JS functions. For each object in the array, a block of JSX elements is returned.

Also, data from the object is passed to each block using the JSX handlebars-like curly brackets.

In the App() component of src/index.js iterate over the imported data using .map()

<hr>

# React and Forms

## React Docs - Forms
> HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state.

![](https://cdn2.hubspot.net/hubfs/2174253/components-react-bos.png)

### Controlled Components
> We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.
### The textarea Tag
> In HTML, a (textarea) element defines its text by its children.

### The select Tag
> In HTML, (select) creates a drop-down list. For example, this HTML creates a drop-down list of flavors

## Alternatives to Controlled Components
> It can sometimes be tedious to use controlled components, because you need to write an event handler for every way your data can change and pipe all of the input state through a React component. This can become particularly annoying when you are converting a preexisting codebase to React, or integrating a React application with a non-React library. In these situations, you might want to check out uncontrolled components, an alternative technique for implementing input forms.

<hr>

# NODE.JS

## What Is Node.js?
> Node.js® is a JavaScript runtime built on Chrome’s V8 JavaScript engine.

![](https://www.isavgo.com/images/magazine/Node.JS-Use-Cases-Cover-Image.png)

## Node Is Built on Google Chrome’s V8 JavaScript Engine
> The V8 engine is the open-source JavaScript engine that runs in Google Chrome and other Chromium-based web browsers, including Brave, Opera, and Vivaldi. It was designed with performance in mind and is responsible for compiling JavaScript directly to native machine code that your computer can execute.

## How Do I Install Node.js?
> In this next section, we’ll install Node and write a couple of simple programs. We’ll also look at npm, a package manager that comes bundled with Node.

### Node Binaries vs Version Manager
> Many websites will recommend that you head to the official Node download page and grab the Node binaries for your system. While that works, I would suggest that you use a version manager instead. This is a program that allows you to install multiple versions of Node and switch between them at will. There are various advantages to using a version manager. For example, it negates potential permission issues when using Node with npm and lets you set a Node version on a per-project basis.


## What Is Node.js Used For?
> Now that we know what Node and npm are and how to install them, we can turn our attention to the first of their common uses: installing (via npm) and running (via Node) various build tools — designed to automate the process of developing a modern JavaScript application.

![](https://uploads.sitepoint.com/wp-content/uploads/2012/10/1516152673node_event_loop.png)

### What Are the Advantages of Node.js?
> Aside from speed and scalability, an often-touted advantage of using JavaScript on a web server — as well as in the browser — is that your brain no longer needs to switch modes. You can do everything in the same language, which, as a developer, makes you more productive (and hopefully, happier). For example, you can easily share code between the server and the client.

<hr>

# Authentication

## What is OAuth?

> OAuth allows websites and services to share assets among users. It is widely accepted, but be aware of its vulnerabilities.

![](https://1tskcg39n5iu1jl9xp2ze2ma-wpengine.netdna-ssl.com/wp-content/uploads/2020/02/oauth-2-flow-diagram.png)


## OAuth definition

> OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.

## How OAuth works

> Let’s assume a user has already signed into one website or service (OAuth only works using HTTPS). The user then initiates a feature/transaction that needs to access another unrelated site or service.

![](https://help.bizagi.com/bpm-suite/en/security_8.png)

