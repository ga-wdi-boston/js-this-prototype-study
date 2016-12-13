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
To reference the object it is contained in and to specify that 'this.whatever' is _only_ referring to the object it's contained in, instead of potentially referencing another global variable with the same name (source: javascriptissexy.com).
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
features of 'this':
-A way to be sure you're referencing the the thing the 'this' is inside. it contains the value of the object.
-It is not set until the function it's in is invoked.
-if it isn't in an object, it'll be assigned to the global scope (unless you're in 'use strict')
(source: javascriptissexy)
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is a parent object, all the objects you create will have features from the prototype. You can also assign new features to the prototype for objects to inherit. (javascriptissexy)
```
