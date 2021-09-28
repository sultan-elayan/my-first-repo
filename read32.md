# Redux - Additional Topics

## What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

> to fire off the asynchronous action in the lifecycle method (probably componentWillMount ) of a Higher Order Component that wraps your app.


## When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

> The most common use case for Redux Thunk is for communicating asynchronously with an external API to retrieve or save data. Redux Thunk makes it easy to dispatch actions that follow the lifecycle of a request to an external API

<hr>

- middleware : iddleware is software which lies between an operating system and the applications running on it. Common middleware examples include database middleware, application server middleware, message-oriented middleware, web middleware and transaction-processing monitors. 

- thunk : Redux Thunk is middleware that allows you to return functions, rather than just actions, within Redux. This allows for delayed actions, including working with promises. One of the main use cases for this middleware is for handling actions that might not be synchronous, for example, using axios to send a GET request

<hr>

## Redux Toolkit

> Redux Toolkit is our official, opinionated, batteries-included toolset for efficient Redux development. It is intended to be the standard way to write Redux logic, and we strongly recommend that you use it.

## What is Hookstate?

>  Hookstate is a small and yet fast and flexible state management tool based on React and Hooks. Hookstate is simple and easy to learn with a pragmatic and flexible API. Even though Hookstate is small, it comes with some good developer-friendly features. ... It also supports plugins that enhance the developer experience.

![](https://miro.medium.com/max/679/1*XpC18cRhDokp1D8CKVrS4A.png)
