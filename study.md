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

```md
It likely saves keystrokes when referring to an object.  You can use this.cat instead of animal.cat. It can also help avoid a bug if your object is found globally; this will only apply to the object which is in context (the subject) http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/

it could also save keystrokes when dealing with event handlers
http://www.quirksmode.org/js/this.html


```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
‘this’ refers to the global object if:
1. It is outside a function
2. code is not in strict mode AND ‘this’ is not set by a call
‘This’ refers to whatever it was set to when entering the execution in a function

You can pass the value of ‘this’ throughout a function but not outside of a function.

In my view, it's shorthand to refer to the object at hand.

http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/

```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
It allows you to reuse properties for all instances of an object.  For instance, you could apply the same shoe.prototype.female property to all instances of an object created to represent women's shoes.
http://www.webdeveasy.com/javascript-prototype/
```
