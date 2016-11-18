# heightFix

jQuery plugin to fix height of child divs based on the shortest/tallest div.

$('.parent').heightFix();

##### options

$('.parent').heightFix({
  type: 'min', // string; possible values = 'min' or 'max'; if u want to make all child divs get the height of the shortest, 'min'. tallest, 'max'.
  child: '.child' // name of the class for child elements inside the parent div
});

requires jquery.


