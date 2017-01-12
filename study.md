# This and Prototype Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

-   [MDN: This](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)
(only up to and including the "As a Constructor" section).
-   [JSIS: This](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)
-   [JSIS: Prototype](http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/)

## This in Context

In your own words, explain one reason why we use "this". In your answer, be
sure to cite any relevant sources you consulted in your search.

'this' is used in JavaScript as a shortcut to refer to the object whose method is called within a function of the object. It is also used to make our code look neater as well as avoiding any mixups with any potential global variables that could have the same name as the object we are calling. Used http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/ for this answer.

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

This is a way to refer a method of the object we are calling the method in. It allows for more specificity when calling the function and avoids any potential mishaps when calling methods within the function in case there are global variables that share the same name as the object whose method we are calling. The 'this' method only becomes an object when the function is called - before it is nothing. Used http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/ for this answer.

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

A prototype attribute is used for inheretance of methods of the parent object which the new object is derived. An object as it is used in object oriented programming has methods that can be customized. If we were to create a new object but want it to inherit the methods of another object - the parent object - then we would make what is called a constructor the same as the parent object therefore allowing it to inherit the methods of the parent object. The each parent object has the 'Object' constructor by default although child objects can have unique constructors with unique methods to pass on.
