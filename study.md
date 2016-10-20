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
"this" can be used to help resolve ambiguity within our code as it refers to the
specific object that called the function that used "this".  As an example,
in our television object code along from this morning we used `television.<key>`
when defining our functions, but we could have used `this.<key>` to make sure
that it was that specific television object that was being referred to.

source: http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"this" is a keyword that refers to the object that called the function that
uses "this" within it.  It's only assigned a value once the object has called
the function. You need to be careful about how the function is being called
because the context of "this" can be altered. There are methods within
javascript that can be used to force a certain context for "this" as well.

source: http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Prototypes make inheritance possible in javascript.  Different properties and methods
can be be added to the prototype of an object and then inherited by any of its
child objects. In this way, you could build your own set of constructors with
their own prototype properties and methods and have them apply to anything created
with those custom constructors. All objects also inherit a set of "default"
properties/methods that belong to the Object.prototype. Finally, there are
prototype attributes that are used by javascript to establish a prototype chain.
Javascript can then run up the chain to see if a property/method is inherited by
any parent object (if not it returns undefined).

source: http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language
```
