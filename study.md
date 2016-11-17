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
We use "this" inside object methods to reference the object instance calling the method. This allows attributes of the object instance to be called/modify/accessed contextually.
Source: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this#As_an_object_method 
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"this" is a reference to an object with a value that is assigned based on context. For example, "this" used in the context of a method references the calling object. "this" can have a value that is explicitly set by using different ways of invoking the function that uses "this" Ultimately, this is supposed to be a convient and clear way of referencing an object. 
Source: all three articles
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype allows inheritance in Javascript. If I want to make an object that has certain methods and attributes and then want to build off that object with access to those properties, I need to add them to the prototype property. The property attribute of an object indicates the "parent" object or the object that that object is built off of.
Source: http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/
```
