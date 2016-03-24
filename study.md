# This and Prototype Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

-   [MDN: This](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)
(only up to and including the "As a Constructor" heading).
-   [JSIS: This](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)
-   [JSIS: Prototype](http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/)

## This in Context

In your own words, explain one reason why we use "this". In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
It can actually be less ambiguous to use 'this' rather than specific variable/property names,
as there could always be another variable/property elsewhere int he code that you are unaware of.  Using 'this' ensures that you are only referencing the object that invokes the variable/property that
contains 'this'.  I consulted the beginning of the [JSIS: This] article above.
```

## This is what

In your own words give explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"This" refers to the object in which it is invoked. If 'this' is not contained within an object, then it refers to the global 'window' object in JS, or is simply undefined using 'strict' JS. I consulted the [JSIS: This] article above.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is an attribute of an object, such that subsequent methods and objects constructed/created or based upon that initial object will inherit that prototype.  I consulted the [JSIS: Prototype] article above.
```
