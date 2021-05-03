# CSS Layout 
## Building Blocks
> CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.

## Containing Elements
> If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.

![](https://developers.google.com/web/updates/images/2017/01/css-grid/examplelayout.png)

## Controll ing the Position of El ements
> CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.

### Normal flow
_Every block-level element
appears on a new line, causing
each item to appear lower down
the page than the previous one.
Even if you specify the width
of the boxes and there is space
for two elements to sit side-byside,
they will not appear next
to each other. This is the default
behavior (unless you tell the
browser to do something else)._


### Relative Positioning
_This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed. This
does not affect the position of
surrounding elements; they stay
in the position they would be in
in normal flow._

### Ab solute positioning
_This positions the element
in relation to its containing
element. It is taken out of
normal flow, meaning that it
does not affect the position
of any surrounding elements
(as they simply ignore the
space it would have taken up).
Absolutely positioned elements
move as users scroll up and
down the page._

<hr>

## Normal Flow
- ### position:static
> In normal flow, each block-level
element sits on top of the next
one. Since this is the default
way in which browsers treat
HTML elements, you do not
need a CSS property to indicate
that elements should appear
in normal flow.

- ### position:relative
> Relative positioning moves an
element in relation to where it
would have been in normal flow.

- ### position:absolute
> When the position property
is given a value of absolute,
the box is taken out of normal
flow and no longer affects the
position of other elements on
the page.

<hr>

## Screen Sizes
> Different visitors to your site will have different sized screens that show
different amounts of information, so your design needs to be able to
work on a range of different sized screens.

![](https://sender11.typepad.com/photos/img3/screensizesgrsmall.png)
