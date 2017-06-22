# learning
Lots of learning happening here.

JS button manlipulation

To create an event based on button click;
- remove item on click

$(‘.btn’).click(function() {
	$(‘.selected’).remove();
});
 
- prependTo list item on click
 
$(‘.btn’).click(function() {
	$(‘<li>’).text(‘New Item’).prependTo(‘.items’);
});
 
This is adding a new list item to a list by clicking a button. prependTo is different to append because prepend puts the item at the top of the list not at the bottom of the list like ‘appendTo’.
