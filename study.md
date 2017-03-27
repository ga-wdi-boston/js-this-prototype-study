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
this is used to refer to the object that called it. I am not entirely sure why, but I think one of the reasons may be that if one function calls to another function you can always refer back to the original object that "this" refers to. Also instead of hard coding object in code you can use "this" to create functions that cant determine an object vs writing it in.

The use of this in the global scope
http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"this" is a contextual method, that isn't assigned a value, but rather searches the object that invoked it. it then replaced itself with object name. in the example in my reference. I see that every instance of this is reffering to the user object.

Fix this inside closure
http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/

```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is an "anonymous" object that makes reference to itself via the "this" method. Because it uses "this" rather than hard coding. It can be used to construct other object with the same key value pairs. It also acts as a default so that if a new object is made with a prototype, but the user does not specify values for a key, the protoype can fill it in with the default. It falls in line ewith DRY practices because you will not be writing the syntax over and over for simillar objects.

fun fun function
https://www.youtube.com/watch?v=riDVvXZ_Kb4
```
