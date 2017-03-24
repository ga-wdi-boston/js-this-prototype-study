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
-   [MDN: Prototype](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object_prototypes)
-   [JSIS: Prototype](http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/)

## This in Context

In your own words, explain one reason why we use "this". In your answer, be
sure to cite any relevant sources you consulted in your search.

When creating a function we can use this to refer back to a property in a function that may have been used in several other functions recently. Rather than potentially referring to the instance of that property that appears in another place it allows us to refer to the specific instance of that property within the function we are defining.

I used the required reading as well as the website http://www.quirksmode.org/js/this.html

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

This is a way to relieve the developer from having to keep track of common properties from function to function. Rather than having to identify each similar property separately it allows us to reference only to it's most recent use.

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

It seems to me like a prototype is a way of building upon the power of this by referring to the values contained within it and attaching them to a new object. In the case of functions creator functions it allows properties defined in the creating function to be passed down to the items created by it.
