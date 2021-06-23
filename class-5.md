# Putting it all together

## Thinking in React
> React is, in our opinion, the premier way to build big, fast Web apps with JavaScript. It has scaled very well for us at Facebook and Instagram.

_One of the many great parts of React is how it makes you think about apps as you build them. In this document, we’ll walk you through the thought process of building a searchable product data table using React._




![](https://laurapinell.com/wp-content/uploads/2019/04/Screen-Shot-2019-04-04-at-3.29.05-PM.png)

### Step 1: Break The UI Into A Component Hierarchy
> The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names. If you’re working with a designer, they may have already done this, so go talk to them! Their Photoshop layer names may end up being the names of your React components!

### Step 2: Build A Static Version in React
> To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.

### Step 3: Identify The Minimal (but complete) Representation Of UI State
> To build your app correctly, you first need to think of the minimal set of mutable state that your app needs. The key here is DRY: Don’t Repeat Yourself. Figure out the absolute minimal representation of the state your application needs and compute everything else you need on-demand. For example, if you’re building a TODO list, keep an array of the TODO items around; don’t keep a separate state variable for the count. Instead, when you want to render the TODO count, take the length of the TODO items array.

#### Think of all the pieces of data in our example application. We have:

- The original list of products
- The search text the user has entered
- The value of the checkbox
- The filtered list of products


### Step 4: Identify Where Your State Should Live
> OK, so we’ve identified what the minimal set of app state is. Next, we need to identify which component mutates, or owns, this state.

### Step 5: Add Inverse Data Flow
> So far, we’ve built an app that renders correctly as a function of props and state flowing down the hierarchy. Now it’s time to support data flowing the other way: the form components deep in the hierarchy need to update the state in FilterableProductTable

![](https://www.logiqlabs.com/wp-content/uploads/2021/04/SRP.png)


<hr>

## Things I want to know more about

>  i want to know more about react app for mobile also , and be specified with this field

<hr>




