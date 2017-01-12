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
We can use `this` to be sure that the object we're referring to is the one that we think it is.
```
"Consider that there could be another global variable (that we might or might not be aware of) with the name “person.” Then, references to person.firstName could attempt to access the firstName property from the person global variable, and this could lead to difficult-to-debug errors." [-JSIS: This](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)


## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
`this` refers to an object with the context of the function calling it.
```
"In JavaScript this always refers to the “owner” of the function we're executing, or rather, to the object that a function is a method of." [-Quirksmode](http://www.quirksmode.org/js/this.html)

"The this reference ALWAYS refers to (and holds the value of) an object—a singular object—and it is usually used inside a function or a method" [-JSIS: This](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Prototypes are a way for objects to inherit properties or methods from parent objects. They provide fallback functionality when an instance of an object doesn't have a property or function defined. 
```

Youtube: FunFunFunction [Protoype Basics](https://www.youtube.com/watch?v=YkoelSTUy7A);
