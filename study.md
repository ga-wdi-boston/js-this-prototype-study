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
One reason to use "this" is to avoid possible collisions if there was a global variable with the same name as the object that is calling the function.  Using "this" means we can safely assume that we are working with the object we want to work with.

This information came from http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
I think of "this" as the current context where it is being used.
So if you were calling a function from the "person" object, this = person.
If you were calling a function from a "dog" object, then this = dog.

http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is a way of passing methods or functions to any objects that are built from a parent object.  For example: getting the length of a string is really helpful so it is added to the String prototype.  Any strings that you create will have the "length" property because they inherit it from the parent "String".

http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/
```
