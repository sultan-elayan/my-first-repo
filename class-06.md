# Problem Domain, Objects, and the DOM
## Problem Domain
_Understanding The Problem Domain Is The Hardest Part Of Programming_

### **Why problem domains are hard??**
_because you can’t really see what you are trying to build very clearly._

### **What can you do about it?**
- #### Make the problem domain easier
- #### Get better at understanding the problem domain

### A familiar problem
> By creating a familiar problem domain, I found that both the tasks of me teaching a new technology and the viewer learning that technology were much easier, because it is very difficult to learn more than one thing at once.

![](https://i.ytimg.com/vi/NTPfKmuHNlU/maxresdefault.jpg)

<hr>

## Object Literals
### WHAT IS AN OBJECT?
> Objects group together a set of variables and functions to create a modelof a something you would recognize from the real world. In an object,variables and functions take on new names.


- IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES
- IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS

![](https://miro.medium.com/max/2404/1*pz5Hpau0mjI5-qZHX78mJw.png)


<hr>

## DOM 
### What is the DOM ?
> The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window.

![](https://simplesnippets.tech/wp-content/uploads/2018/10/what-is-document-object-model-in-JS-featured-image.jpg)

_The DOM is neither part of HTML, not part of JavaScript; it is a separate set of rules.
It is implemented by all major browser makers, and covers two primary areas:_

1. MAKING A MODEL OF THE HTML PAGE
2. ACCESSING AND CHANGING THE HTML PAGE

### DOM TREE

![](https://www.researchgate.net/profile/Jian-Chang-8/publication/254002847/figure/fig1/AS:298235726974978@1448116346303/Example-of-DOM-Node-Tree.png)

_DOM tree have two sectio_
- ATTRIBUTE NODES : The opening tags of HTML elements can carry
attributes and these are represented by attribute
nodes in the DOM tree.

- TEXT NODES : Once you have accessed an element node, you
can then reach the text within that element. This is
stored in its own text node.

### WORKING WITH THE DOM TREE
**Accessing and updating the DOM tree involves two steps:**
-  Locate the node that represents the element you want to work with.
-  Use its text content, child elements, and attributes.

- ### STEP 1: ACCESS THE ELEMENTS
- ### STEP 2: WORK WITH THOSE ELEMENTS

### ACCESSING ELEMENTS
> DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes.

### Accessing a DOM element By TagName:

1. getElementByTagName
2. getElementByTagName.html
3. getElementByClassName

![](https://www.toolsqa.com/wp-content/uploads/2020/04/DOM-IN-JAVASCRIPT.jpeg
)


