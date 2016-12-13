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
"This" can be used to avoid redudancy.

(via javascriptissexy)
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"This" changes depending on the context in which it is called. If it is called
outside of a function, it refers to the global object (or undefined if javascript is in strict mode). If it is a part of a method,it refers to the object the method is called on (even if it was originally part of a prototype and inherited).
```

(via MDN: This)

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Prototypes are bundles of methods and properties that objects inherit. Objects
can inherit multiple prototypes in a chain (if a prototype they have inherited
has inherited prototypes of something else). All objects inherit the object prototype.

via javascriptissexy and Google
```
