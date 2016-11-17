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
From the JSIS linked above:

"this" can be used as a reference to the object that invoked a function.
For example say you have an object with various properties and functions defined.
The functions internally can refer to other keys and such within the object by
"this". So instead of writing objectName.key1 = x, one could write
this.key1 = x. This is both shorthand and more precise (since objectName could
potentially be used elsewhere).

```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
From the JSIS linked above:

I think basically it is just a reference to an invoking object.


```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
From the JSIS linked above:

A prototype is the parent object of an object. You can have an object A with
a set of properties and methods. Then if you create a new object B based off
of A it will inherit all those properties and methods. They are chained together,
like C<--B<--A, so that B inherits from A, and C inherits from both A and B.

```
