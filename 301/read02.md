#  jQuery, Events, and The DOM
----------------------
## Chapter 7 (From the Duckett JS book)

jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation.

Basic syntax is: $(selector).action()
- A $ sign to define/access jQuery
- A (selector) to "query (or find)" HTML elements
- A jQuery action() to be performed on the element(s)

A type of jQuery selection:
- single element
- multiple element

 jQuery ready() Method
 The ready event occurs when the DOM (document object model) has been loaded
 
$( document ).ready(function() {
  // Handler for .ready() called.
});

Methods that update the content of all elements in a jQuery selection:

- . html() 
- . text() 
- .replaceWith()
- . remove()

Inserting new elements involves two steps:

1: Create the new elements in a jQuery object

2: Use a method to insert the content into the page (.before(),.after(),.prepend(),.append() )

create attributes( .attr() ,. removeAttr(),. addCl ass(),.removeClass() )

The . css () method lets you retrieve and set the values of CSS properties. 

jQuery allows you to recreate the functionality of a loop on a selection of elements, using the  each () or $(this) method. 



--------------------------------
## Reasons for Pair Programming

- Greater efficiency
- Engaged collaboration
- Learning from fellow students
- Social skills
- Job interview readiness
- Work environment readiness

