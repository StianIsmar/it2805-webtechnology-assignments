# Questions for assignment 3

### Question 1
position:absolute is very powerful and can be used to place an element anywhere you would like, in relation to the parent element. If there is no parent elememt, the element you are placing using absolute will be positioned in relation the the html-element itself (the outer one).

postition:fixed places elements relative to the viewport or the browser window itself. The viewport does not change when the user scrolls the page. So this positioning is much less versatile then the absolute positioning.


### Question 1

One way of selecting the third element (kind of hardcoded way) is to give that element an id and use # to select it in the css.

A prittier way is to use :nth-child(3) to select it. If the parent element is a div, the css selector would look like this: div:nth-child(3).

