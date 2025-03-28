# Expandable_Lists_js

Expandable List

Description:

Create an expandable list where clicking on a list item expands or collapses a sub-list. 
Use event delegation to handle the click events on the parent list element, 
and bubbling to toggle the sub-list visibility.

Instructions

Create an HTML file with an unordered list element containing several list items.
Each list item should have a title and a sub-list containinga some content. The sub-list should be initially hidden with CSS (display: none;).
Use JavaScript to add an event listener to the parent list element, and use event delegation to handle click events on the list items.

When a list item is clicked, toggle the visibility of its sub-list using the classList property to add or remove the hidden class 
(which should have the CSS display: none; rule).Use bubbling to handle the click events on the child elements of the list item.
Clicking on the sub-list should not trigger the expand/collapse behavior.
