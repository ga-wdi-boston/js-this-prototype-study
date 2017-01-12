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

```md

We use the this property in when a function utilizes this as a keyword in its body. This will have the value binded to
a certain object in the call. The method used here will have all functions inheriting from Function.prototype through the call or apply process.

```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
The this property can be used in multiple ways.

This is utilized when the function executes and it is considered to
invoke the function as a variable with the value of the object.

It is used outside of function when referencing global
scope and used inside a function or a method. In
global and anonymous functions that aren't tied to any
object, this' value would undefined in strict mode.

There isn't an assignment with this until an object invokes
the function where this is defined.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype property is empty by default and every JavaScript function has one. If you want to implement inheritance, you would attach properties and methods on this prototype property.


In JavaScript, objects have a pointer to another object and that is the object's prototype (also known as the prototype object). JS will look through the prototype to find the key on an object if it isn't found through the object. Until a null value pops up, it will follow the prototype chain. So the return will remain undefined.
```
