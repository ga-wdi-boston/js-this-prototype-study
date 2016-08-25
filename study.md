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
The main reason why we use "this" is as a shortcut; it references an object (usually within a function or method) that has already been defined in the code that we are rendering, allowing us to invoke it without redundancy and with more clarity and precision. The object that "this" refers to can change depending on the context or method that it is used in.
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
In its simplest form, "this" is a variable of an object that has previously been defined in a function where "this" is used. However, a value is not assigned to "this" until an object invokes the function where you defined "this".
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Above all, we us the prototype attribute to execute two imporant things: First, it allows us to establish properties and methods that we want to implement through inheritance. Unlike most scripting languages, JavaScript does not have classical inheritance; thus we implement inheritance in JS through the prototype property. A prototype allows us to create a function and add attributes and methods to the function, and said function will inherit all of the established attributes and methods in all future instances. Second, the prototype attribute is crucial for accessing properties and methods of objects. If you want to invoke the property of an object, JS runtime will search for it directly on the object. If it cannot find it there, JS will look for the object it inherited it's properties from - I.E. the object's prototype. If the object is still not found, JS will then move to the prototype of the object's prototype - and so on and so on - continuing until there are no more prototypes to follow.
```
