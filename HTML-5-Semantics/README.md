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