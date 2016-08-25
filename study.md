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
To avoid ambiguity. If there was another global variable with the same name
as the object that we are referring to, this could lead to errors because the
the property of the global might be accessed rather than the intended object's
property.

http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
http://www.quirksmode.org/js/this.html
http://stackoverflow.com/questions/3127429/how-does-the-this-keyword-work
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
'This' is a referrent. It is like how the pronoun 'he' can be used to refer to
the subject of a sentence, for instance, John. In JS, 'this' refers to the
object of executing code. It is used not only for asthetic purposes, but it is
also used for precision and to make you code less ambiguous (see above).
'This' also assumes the value of the object to which it is referring.
Therefore, it can be used to access the properties and methods of the object
invoking the function. This is also helpful because we don't always know the
name of the invoking object when we might want to refer to it. 'This' does not
get assigned a value of an object until that object invokes a function.

Source:
http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
http://www.quirksmode.org/js/this.html
http://stackoverflow.com/questions/3127429/how-does-the-this-keyword-work
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Prototype is a property in every JS function that is empty by default. It is
used to implement inheritance by attaching properties and functions onto a
prototype. The prototype attribute (a.k.a. prototype object) tells us the
"parent" of an object. The prototype attribute of all objects created with
'new Object()' or {} is Object.prototype. Objects created from constructor
functions (new Something()) inherit from that constructor. Therefore, the
prototype attribute would be Something.prototype. JS uses the lineage
prototype chain to look for properties and methods of an object.

Sources:
http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/prototype
```
