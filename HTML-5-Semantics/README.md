### Position
There are 5 different values for the position property:
* static: The element is positioned according to the normal flow of the document.
* relative: The element is positioned relative to its normal position in the document flow.
* absolute: The element is positioned absolutely relative to the nearest positioned ancestor element.
* fixed: The element is positioned fixed relative to the viewport.
* sticky: The element is positioned sticky relative to the viewport.

viewport: The viewport is the area of the screen that is visible to the user. The position property can be used to position elements relative to the viewport.<br>
#### static:
default value to begin with. can't move this anywhere on page<br>
#### relative
can move a value from its original place
, but it's still part of the regular layout and will affect other elements' positions as well if
they overlap or stack behind each other. It moves itself based off where it would have been had there
not been any `position` attribute at all (i.e., default behavior).<br> For example,
you might use `relative` when creating dropdown menus that appear below an anchor link instead of overlapping them
you might use `relative` when creating dropdown menus that appear below an item after clicking/hovering
over it.<br>
### absolute
Absolute positioning is a CSS property that allows you to position an element relative to the nearest positioned ancestor, or to the viewport if there is no positioned ancestor. This means that you can place an element anywhere on the page, regardless of its position in the document flow.<br>

To use absolute positioning, you need to set the position property of the element to absolute. <br>You can then use the top, right, bottom, and left properties to specify the element's position relative to its parent element.<br>

For example, the following code will position an element 100 pixels from the top and left of its parent element:<br>

div {<br>
  position: absolute;<br>
  top: 100px;<br>
  left: 100px;<br>
}<br>

Absolute positioning can be useful for creating floating elements, positioning elements over other elements, and creating custom layouts.<br>
### fixed

Fixed positioning is a CSS property that allows you to position an element relative to the viewport, or the browser window.<br> This means that the element will stay in the same place on the screen, even if the user scrolls the page.<br>

To use fixed positioning, you need to set the position property of the element to fixed.<br> You can then use the top, right, bottom, and left properties to specify the element's position relative to the viewport.<br>

For example, the following code will position an element 100 pixels from the top and left of the viewport:<br>

div {<br>
  position: fixed;<br>
  top: 100px;<br>
  left: 100px;<br>
}<br>
​<br>
Fixed positioning can be useful for creating headers, footers, and other elements that should always be visible on the screen
<br>
### sticky
Sticky positioning is a CSS property that allows you to position an element relative to the viewport, but only when the element is scrolled past a certain point. <br>This means that the element will behave like a fixed element until it is scrolled past, and then it will behave like a normal element.<br>

To use sticky positioning, you need to set the position property of the element to sticky. You can then use the top, right, bottom, and left properties to specify the element's position relative to the viewport.<br>

For example, the following code will position an element 100 pixels from the top of the viewport when it is scrolled past:<br>


​<br>
div {<br>
  position: sticky;<br>
  top: 100px;<br>
}<br>
Sticky positioning can be useful for creating headers, footers, and other elements that should always be visible at the top or bottom of the screen, even when the user scrolls the page<br>

## Pseudo Classes & Elements
add : and class name like `hover`,`focus`
hover: is used when you hover mouse on some tag or element. It can be applied to any HTML elements, including links, buttons etc., but not all of them support it.<|im_sep|>
```css
input[type="text"]:focus {
  border-color: red;
  }
focus: is used when you click on some tag
.class_name::focus{ /* this will add content after the element */ 
border:4px solid green";
display:block;}
valide: is used when a condition is true and you want to show that condition is true

.class_name::after{ /* this will add content after the element */ 
content:"hello";
display:block;}
/* ::before adds a pseudoelement before an element, while ::after does it after.*/
a:visited{} //this applies to visited links only
p::-moz-selection {}//This selects all p elements with Mozilla Firefox selection styles applied (e
```
Pseudo classes are added using `:`, for example `.classname`:active`. This means that if
the user clicks or taps inside of any HTML element with the classname "classname", then its active
state should be triggered by adding the ":active" suffix at the end of the selector.<|im
sep|>
### psuedo elements
Add double colon (::) in front of them
```css
h2::first-letter {/*selects first letter*/
font-size:3em; color:#f90; font-weight:bold;}
ul li::marker {/*adds marker symbol as bullet point*/
list-style-image:url('bullet.png'); margin-left:-5%; width:.
8rem;}
