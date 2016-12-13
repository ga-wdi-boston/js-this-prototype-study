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
We use "this" in javascript to avoid ambiguity in our code by ensuring that a
method (function as a property of an object) intended for use with a particular
object calls other properties from that same object. It is used in a similar way
to pronouns in English, words that refer back to the intended subject of a
sentence.

I consulted primarily the JSIS article on "this."
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"this" is a referent in javascript that allows us to refer to properties of a
specific object within that object's method (or methods/function invoked by
a particular object.) For example if we have a method within a TV object that
changes the volume property of the TV, we would use this.volume rather
than tv.volume.

I consulted MDN & JSIS to research "this."
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is a mechanism by which we can allow new objects to inherit
properties from previously constructed objects. This allows us to have elements
in our code that behave similarly and have access to the same methods without
having to constantly repeat them.

I consulted MDN & JSIS in my search.
```
