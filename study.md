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
We will likely have to introduce 'this' into our code if we assign
methods to an object that are borrowed from another object.
In that case, any uses of 'this' in the method will refer to the object from
which the method was borrowed, even when the method is called from the new object.
In order to make our method behave as if the method hadn't been borrowed,
we need to bind the function to the 'this' context of our new object using
'functionName.bind(this)'.
See('https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this')
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
'This' is an object that refers to the context within which the function is called.
Where the function is called as a method on an object, 'this' refers
to the object on which the method is defined.
I find the 'Understand JavaScript’s “this” With Clarity, and Master It'
analogy to natural language pronouns useful for understanding the relationship
between 'this' and the object it refers to.
See('https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this')
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
In prototypical inheritence, a prototype is the object from which a newly
created object inherits properties and determines the new objects prototype
attribute.  Importantly and, as opposed to the classical inheritence model, all
protoypes are simply objects themselves and, therefore, can be modified at any
point, and those modifications will be inherited by any object that inherits
its properties from the modified object.
Another important concept is the 'prototype chain.'  Every object inherits its
properties not just from its own protoype but from its prototype's prototype.
This chain links all objects back to the base 'Object' protoype.
See('https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain')
See('http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/')
```
