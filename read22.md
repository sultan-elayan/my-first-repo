# Advanced State with Reducers



## How can we ensure that an effect hook runs only once?

>  If we pass an empty array [] , it just renders the component only once like componentDidMount 

## Can useState() update more than one state variable at the same time?

>  You can have multiple states inside of a single component: call multiple times useState()

## Is useState() synchronous?

> no , useState() doesn't update value of the variable if called just after setting value.

<hr>


- State Hook : A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We'll learn other Hooks later.

- Component Lifecycle : Every React Component has a lifecycle of its own, lifecycle of a component can be defined as the series of methods that are invoked in different stages of the component's existence. ... A React Component can go through four stages of its life as follows

![](https://media.geeksforgeeks.org/wp-content/uploads/lifecycle_reactjs.jpg)



<hr>

## useReducer hook

> useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

![](https://i.stack.imgur.com/q6NQJ.png)

## Ultimate Guide to useReducer

## How does useReducer work?

- useReducer is used to store and update states, just like the useState Hook. It accepts a reducer function as its first parameter and the initial state as the second.

- useReducer returns an array that holds the current state value and a dispatch function, to which you can pass an action and later invoke. This is similar to the pattern Redux uses but with a few differences.

![](https://camo.githubusercontent.com/39edc655449f6262a9a7be81b38da2a83896b55c8c1b146a8922ae1804ccbe91/68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f64676576653764616f2f696d6167652f75706c6f61642f76313538303636353932322f5573655f526564756365725f536964655f4566666563745f44656d6f2e706e67)
