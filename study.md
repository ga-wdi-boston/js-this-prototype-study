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
It's possible to have more than one variable with the same name (even if you're not aware of it). When this happens, it's useful to use "this" because it directs to the nearest variable with that name, rather than the global one.

(from http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"this" tells your javascript code to apply a method to the nearest Object environment. It saves you the trouble of renaming a variable or object repeatedly within the same object.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is a type of Object which gives its attributes and methods to a child class.
So for example if you have an Object called Video_Game which has a method nextLevel(), an object built from that called RPG will also have nextLevel() as a method automatically.
```
