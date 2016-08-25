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
One reason we use "this" when coding is to give our functions more flexibility. We may not always know what object is going to be invoking a method, and that object may or may not even have a name (apparently some functions are 'anonymous'?). By using 'this' instead of hard-coding an object name, we ensure that our function has the flexibility to work as intended in a variety of contexts.

The JSIS article "Understand JavaScript's "this" with Clarity, and Master It" was a very helpful source in writing this response.
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"this" is a JavaScript keyword referring to a property that all functions have when they are invoked. The value of 'this' is assigned when the function is invoked, and wherever it appears in that function, it will usually have the value of the object that invoked the function. There are a handful of case where changing context can make it tricky to determine what the value of this will be, and sometimes we have to use additional functions like bind() or apply() to make 'this' do what we want it to do.

The JSIS article "Understand JavaScript's "this" with Clarity, and Master It" was a very helpful source in writing this response. Some of the example code in the MDN documentation for 'this' was also useful, along with today's in-class code-along and lab work involving 'this'.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype in JavaScript is something that all functions have as a property, and all objects have as an attribute. Prototype is what drives inheritance in JavaScript. An object's prototype tells you what its parent object is. A function's prototype tells you what will be inherited any time that function is used. When we ask an object for the value of one of its attributes and it doesn't have its own version of that attribute, it goes up the 'prototype chain', parent by parent, until it finds one (or runs out of parents).
```
