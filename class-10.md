# Debugging
## Error Handling & Debugging
> JavaScript can be hard to learn and everyone makes
mistakes when writing it. This chapter will help you learn
how to find the errors in your code. It will also teach you how
to write scripts that deal with potential errors gracefully.


![](https://developer-chrome-com.imgix.net/image/admin/fgJB1mwfZsJ7Pv21hzSt.png?auto=format)


## ORDER OF EXECUTION
> To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run:

1. The greeting variable gets its value from the
greetUser() function.
2. greetUser() creates the message by combining
the string 'He 11 o ' with the result of getName ().
3. getName () returns the name to greetUser() .


![](https://miro.medium.com/max/2800/0*bQzxDDHWy9g5YyqF.png)

<hr>

## UNDERSTANDING SCOPE
> In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.

## UNDERSTANDING ERRORS
> If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.

## ERROR OBJECTS

- Syntax Error : SYNTAX IS NOT CORRECT
- Ref erenceError : VARIABLE DOES NOT EXIST
- EvalError : INCORRECT USE OF eval() FUNCTION
- URI Error : INCORRECT USE OF URI FUNCTIONS

## HOW TO DEAL WITH ERRORS ??
_Now that you know what an error is and how the browser treats them,
there are two things you can do with the errors._

1. DEBUG THE SCRIPT TO FIX ERRORS
2. HANDLE ERRORS GRACEFULLY

## A DEBUGGING WORKFLOW
> Debugging is about deduction: eliminating potential causes of an error.
Here is a workflow for techniques you will meet over the next 20 pages.
Try to narrow down where the problem might be, then look for clues.

![](https://vscode-docs.readthedocs.io/en/stable/extensionAPI/images/api-debugging/debug-arch.png)


## BROWSER DEV TOOLS & JAVASCRIPT CONSOLE
> The JavaScript console will tell you when there is a problem with a script,
where to look for the problem, and what kind of issue it seems to be.

## WRITING FROM THE SCRIPT TO THE CONSOLE
> Browsers that have a console have a console object, which has several
methods that your script can use to display data in the console.
The object is documented in the Console API.