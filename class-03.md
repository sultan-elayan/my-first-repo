# HTML Lists, Control Flow with JS, and the CSS Box Model
## Lists in HTML
> There are lots of occasions when we
need to use lists. HTML provides us with
three different types:

- **Ordered lists** are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.

![](https://www.programming9.com/images/orderedlist_programming9.png)

_The ordered list is created with
the (ol) element._

<hr>

-  **Unordered lists** are lists that begin with a bullet point (rather than characters that indicate order).

![](https://www.programming9.com/images/ul_programming9.png)

_The unordered list is created
with the (ul) element._

<hr>


- **Definition lists** are made up of a set of terms along with the
definitions for each of those terms.

![](https://www.programming9.com/images/orderedlist_programming9.png)

_The definition list is created with
the (dl) element and usually
consists of a series of terms and
their definitions._

<hr>
Every list in html contain (li) 

> The HTML (li) element is used to represent an item in a list. It must be contained in a parent element

![](https://i.stack.imgur.com/e96No.png)

_example_

<hr>

## Box in CSS
> In CSS, the term "box model" is used when talking about design and layout.
The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.

- **Box Dimensions**

**width, height**
> The height and width properties are used to set the height and width of an element.
The height and width properties do not include padding, borders, or margins. It sets the height/width of the area inside the padding, border, and margin of the element.


- **Limiting Width**

**min-width, max-width**
> The max-width property defines the maximum width of an element.
If the content is larger than the maximum width, it will automatically change the height of the element.
If the content is smaller than the maximum width, the max-width property has no effect.

- **Limiting Height**

**min-height, max-height**
> The max-height property defines the maximum height of an element.
If the content is larger than the maximum height, it will overflow. How the container will handle the overflowing content is defined by the overflow property.
If the content is smaller than the maximum height, the max-height property has no effect.

- **Overflowing Content**

**overflow**
> The overflow property tells the
browser what to do if the content
contained within a box is larger
than the box itself. It can have
one of two values:
1. hidden
This property simply hides any
extra content that does not fit in
the box.
2. scroll
This property adds a scrollbar to
the box so that users can scroll
to see the missing content.

### Border, Margin & Padding
> Every box has three available properties that
can be adjusted to control its appearance:

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/35092531323/original/jCCU5Zuh4nvioMmOGW0UEilxM-svalVSNg.png?1597594199)

<hr>

## Control Flow In JS
### What is an Array?
> An array is a special variable, which can hold more than one value at a time.
If you have a list of items (a list of car names, for example), storing the cars in single variables

![](https://cdn.educba.com/academy/wp-content/uploads/2019/09/Arrays-in-JavaScript.png)

<hr>

## Decisions and Loops
### JavaScript if else and else if
- Use the if statement to specify a block of JavaScript code to be executed if a condition is true.
- Use the else statement to specify a block of code to be executed if the condition is false.
- Use the else if statement to specify a new condition if the first condition is false.

![](https://cdn.programiz.com/sites/tutorial2program/files/js-if-else-statement.png)

### JavaScript switch
**Use the switch statement to select one of many code blocks to be executed.**

#### This is how it works:

- The switch expression is evaluated once.
- The value of the expression is compared with the values of each case.
- If there is a match, the associated block of code is executed.
- If there is no match, the default code block is executed.

![](https://cdn.programiz.com/sites/tutorial2program/files/javascript-switch-statement.png)

<hr>

## Javascript Loops
> The JavaScript loops are used to iterate the piece of code using for, while, do while or for-in loops. It makes the code compact. It is mostly used in array.

![](https://www.tutsmake.com/wp-content/uploads/2020/05/Loops-In-JavaScript.jpeg)

## Loop Counter
> The JavaScript for loop statement allows you to create a loop with three optional expressions. The following illustrates the syntax of the for loop statement

![](https://cdn.educba.com/academy/wp-content/uploads/2020/03/nested-loop-in-javascript.jpg)

<hr>

For more INFO you can visit [github profile](https://github.com/sultan-elayan)