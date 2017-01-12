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
We use 'this' inside of a function if the variable we would have used is already in use somewhere else in the code globally.  The function would get confused as to which variable to use (the local one or the global one), so we can use 'this' to represent the object variable locally.

The following source was very helpful to my understanding: http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
'this' is used in place of an object variable inside of a function.  It is used to replace a local variable if there exists a global variable of the same name as the local one.  It also makes the code more aesthetically pleasing.  If 'this' is used outside of a function (in the global scope) it refers to the 'window' object, as in the window that is used to view a web page or application.  However, 'this' only refers to the global 'window' object if strict mode is not in use.

The following source was very helpful to my understanding: http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A 'prototype' is a command that is added to an object.  It is used to establish a set of properties of an object.  If an object is set with a 'prototype' property and a new variable is created that uses that same object, the properties established by the 'prototype' will be applied to the new variable without the need to retype these properties.  The new variable is said to 'inherit' the properties of the object with 'prototype'.

I found this source to be very helpful: http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/
```
