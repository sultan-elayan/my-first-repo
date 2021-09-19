# Context API - Behaviors

## When you have multiple contexts, what component type should you use (class/function) and why?

> 
In class components, the render method will be called, whenever the state of the components changes. On the other hand, the Functional components render the UI based on the props. Class Components should be preferred whenever we have the requirement with the state of the component

## What are some good use cases for using the Context API for global state?

> 
Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult. If you only want to avoid passing some props through many levels, component composition is often a simpler solution than context.

## How can you best test context?

> The best way to test Context is to make our tests unaware of its existence and avoiding mocks. We want to test our components in the same way that developers would use them (behavioral testing) and mimic the way they would run in our applications (integration testing)

<hr>

- context : React Context is a method to pass props from parent to child component(s), by storing the props in a store(similar in Redux) and using these props from the store by child component(s) without actually passing them manually at each level of the component tree.

- useContext() : 
“useContext” hook is used to create common data that can be accessed throughout the component hierarchy without passing the props down manually to each level. Context defined will be available to all the child components without involving “props”

- static context : 
A static method or, block belongs to the class and these will be loaded into the memory along with the class. You can invoke static methods without creating an object. ... But static contexts(methods and blocks) doesn't have any instance they belong to the class

<hr>

### context api

> Context provides a way to pass data through the component tree without having to pass props down manually at every level.

> The React Context API is a way for a React app to effectively produce global variables that can be passed around. ... Context API is a (kind of) new feature added in version 16.3 of React that allows one to share state across the entire app (or part of it) lightly and with ease.

![](https://miro.medium.com/max/1838/1*7gl-3SbI7MszLOCS1F953Q.jpeg)

