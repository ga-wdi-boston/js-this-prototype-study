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
-   [MDN: Prototype](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object_prototypes)
-   [JSIS: Prototype](http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/)

## This in Context

In your own words, explain one reason why we use "this". In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
One reason to use 'this' is to avoid ambiguity when calling a function from an object.  In some cases, the object calling the function might change so it is helpful to have a word to refer to the parent object instead of explicitly calling it by name.  I used the JSIS article that explains 'this' to help understand this use for 'this'.
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
'this' is a way to refer to the object that calls a function.  If a new function is called inside the original function, the value of 'this' changes inside the new function to refer to the object that called the new function.

If we have two objects, we might need to call a function called printValue that prints the value of the objects.  In order to avoid writing two functions, we can write one function using 'this' that can work on both objects.

Since functions can be nested in functions, the object that 'this' refers to can become confusing so there are ways to force 'this' to refer to a specific object to avoid this issue.

Both the JSIS article and MDN article were really helpful in understanding 'this'.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Prototype is the primary way that inheritance is done in Javascript.  It allows the developer to avoid writing the same lines of code over and over when creating objects that are similar to each other.  If we are writing a program that contains many different kinds of Fish objects, instead of defining Tuna, Cod, and Haddock as all having their own individual 'name' property, we can create a prototype called Fish from which each of these different kinds of fish inherits the property 'name'.

Just like we write functions to avoid having to write the same lines of code over and over, prototypes help us achieve a similar result while creating objects.  It allows the dependant objects to have more easily understandable properties that are specific to the different objects.
```
