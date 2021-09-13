# Component Lifecycle / useEffect()

## Why do we not need more .html pages in a multi-page React app?

> It takes advantage of HTML's popularity and strength as the most popular programming language, by letting you use a very similar syntax to HTML to build interfaces and add dynamic features to it using JavaScript.

## If we wanted a component to show up on every page, where would we put it and why?

> Inside the (BrowserRouter /), outside a (Route)

## What does routing do with the components that were rendered when a new route is requested

> One way to do would be to pass the component prop an inline function. When you use component, the router uses React. createElement to create a new React element from the given component. That means if you provide an inline function to the component prop, you would create a new component every render. 

## What does props.children contain?
>  display whatever you include between the opening and closing tags when invoking a component. This component contains an (img) that is receiving some props and then

## How do useState() and this.setState() differ?

> setState() does not immediately mutate this. state but creates a pending state transition. Accessing this. state after calling this method can potentially return the existing value.

<hr>

- State Hook : 
A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We'll learn other Hooks later.

- Mounting and Un-Mounting : Mounting a file system attaches that file system to a directory (mount point) and makes it available to the system. ... The root ( / ) file system is always mounted. Any other file system can be connected or disconnected from the root ( / ) file system.

<hr>

## effects hook 

[Using the Effect Hook](https://reactjs.org/docs/hooks-effect.html)