# In memory storage

![](https://felixgerschau.com/static/79486d91b22a7c1b4044fce88a4cae20/5a190/js-event-loop-explained.png
)

## What is a ‘call’?

> a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

## What does LIFO mean?

> LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns

## What causes a Stack Overflow?

> A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

 ### In summary

 > The key takeaways from the call stack are:
1. It is single-threaded. Meaning it can only do one thing at a time.
2. Code execution is synchronous.
3. A function invocation creates a stack frame that occupies a temporary memory.
4. It works as a LIFO — Last In, First Out data structure.


<hr>

## JavaScript error messages

> Most of your time as a developer is spent reading code followed by debugging that same code, most likely to be able to read it or solve an “unexpected feature” (which, joking aside, is more correctly known as a “bug”).


![](https://www.sfdcpoint.com/wp-content/uploads/2020/04/Lightning-Web-componentLWC-Toast-Messages.png)


 ### Types of error messages

 - Reference errors
 - Syntax errors
- Range errors
- Type errors

### Call stack
 
> The red part of our first example represents the call stack, which is the path that your program has taken to reach the point were you set a breaking point or were you have an error.

<hr>


## Things I want to know more about

_I want to know more about the easiest way to debug JS problem_


