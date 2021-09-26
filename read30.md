# Redux - Combined Reducers

## Why choose Redux instead of the Context API for global state?

> Context API is easy to is use as it has a short learning curve. It requires less code, and because there's no need of extra libraries, bundle sizes are reduced. Redux on the other hand requires adding more libraries to the application bundle. The syntax is complex and extensive creating unnecessary work and complexity

## What is the purpose of a reducer?

> In Redux, a reducer is a pure function that takes an action and the previous state of the application and returns the new state. The action describes what happened and it is the reducer's job to return the new state based on that action 

## What does an action contain?

> It carries a payload of information from your application to store


## Why do we need to copy the state in a reducer?

> the reducer must create new object, and making a copy is a way to describe the unchanged part.

<hr>


- immutable state : 
Using immutable states allows us to write code that can quickly tell if the state has changed, without needing to do a recursive comparison on the data, which is usually much, much faster

- time travel in redux : 
Time travel is the ability to move back and forth among the previous states of an application and view the results in real time

- action creator : 
An action creator is merely a function that returns an action object. Redux includes a utility function called bindActionCreators for binding one or more action creators to the store's dispatch() function.

- reducer : 
In Redux, a reducer is a pure function that takes an action and the previous state of the application and returns the new state.

- dispatch : 
dispatch is a function of the Redux store. You call store. dispatch to dispatch an action. This is the only way to trigger a state change. With React Redux, your components never access the store directly - connect does it for you


<hr>


## Using combineReducers

> combineReducers is simply a utility function to simplify the most common use case when writing Redux reducers

> 
It turns out that Redux lets us combine multiple reducers into one that can be passed into createStore by using a helper function named combineReducers . The way we combine reducers is simple, we create one file per reducer in the reducers directory. We also create a file called index. js inside the reducers directory.

![](https://imgs.developpaper.com/imgs/881160120-5cbd6895d4819_articlex.png)
 



