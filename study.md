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
Using 'this' within a method of an object can assure that you are referencing the correct object (i.e. the object containing the method). If you don't use 'this' but instead reference the object by name, you could potentially be referencing a global object of the same name.
--source:  javascriptissexy.com
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
'this' is a keyword built into the JavaScript language; the 'this' keyword, used within a method of an object, references that invoking object by default, but can also be bound to other objects, such as the global window object, etc.. 'this' is both a shorthand way to reference and interact with an object as well as a way to be more precise and targeted with how we reference objects (i.e. see my response to first question above)
--source:  mostly javascriptissexxy.com
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is a property of an object, which allows you to create a chain of method and property inheritance between objects. You could, for example, add an abstracted method to some object (let's call it highLevelObject), such as a print method that performs a console log of passed arguments, and instead of having to re-create that method on future objects, you could simply have your new object inherit that print functionality by assigning a constructor of highLevelObject to the prototype property of your new object.
--source:  primarily javascriptissexy.com
```
