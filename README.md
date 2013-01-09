jquery-stick
============

Easy jQuery plugin to stick elements when you scroll. Simply adds a default class called "stick" to the named element when the top of the window hits the element, then removes "stick" and replaces it with "stick-end" when the bottom of the named element hits the bottom of its container (default: ".container").



Usage
============

$('.block').stick();

Calls for the "stick" plugin on ".block" using default values.



Advanced Usage
============

Default values of options:

$('.block').stick({
  offset: 0,
  bottompadding: 0,
  container: '.container',
  stickyclass: 'stick',
  endclass: 'stick-end'
});


Description of options:

"offset" - number of pixels above element to call the stickyclass to be added to the element.

"bottompadding" - number of pixels below element (within the container) to remove the stickyclass and replace it with the endclass.

"container" - the container that holds your element that you want it to be referenced against (make sure to have the leading period).

"stickyclass" - the class to be added when sticky (be sure not to have the leading period).

"endclass" - the class to be added once the element has reached the end of the container (be sure not to have the leading period).



License
============

Dual licensed under MIT and GPL. Feel free to clone, modify, and use at will, as you see fit. If used in commercial projects, just let me know with a note, tweet, or email. Thanks!



Contact
============

Kyle Conrad - kyle@kyleconrad.com - http://www.kyleconrad.com - @kyle_conrad 
