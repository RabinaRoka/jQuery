1. Inside your script element, add this code: $(document).ready(function() { to your script. Then close it on the following line (still inside your script element) with: });

We'll learn more about functions later. The important thing to know is that code you put inside this function will run as soon as your browser has loaded your page.

##All jQuery functions start with a $, usually referred to as a dollar sign operator, or as bling.

#animations : $("button").addClass("animated bounce");
    $(".well").addClass("animated shake");
    $("#target3").addClass("animated fadeOut");


    #jQuery has a function called .prop() that allows you to adjust the properties of elements.

    #jQuery has a function called .html() that lets you add HTML tags and text within an element. Any content previously within the element will be completely replaced with the content you provide using this function.

    #Now let's remove an HTML element from your page using jQuery.

jQuery has a function called .remove() that will remove an HTML element entirely.

#jQuery has a function called appendTo() that allows you to select HTML elements and append them to another element.

#In addition to moving elements, you can also copy them from one place to another.

#jQuery has a function called clone() that makes a copy of an element.

#jQuery has a function called parent() that allows you to access the parent of whichever element you've selected.

#jQuery has a function called children() that allows you to access the children of whichever element you've selected.

#jQuery uses CSS Selectors to target elements. The target:nth-child(n) CSS selector allows you to select all the nth elements with the target class or element type.