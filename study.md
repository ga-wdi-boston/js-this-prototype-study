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
One reason to use 'this' is to be more precise. If you use a variable inside the object and you want
the varible to refer the object itself for it's value, there is a possiblity that the variable could have
already been defined globally, outside of the object and our variable would pick up the value
of that global variable instead of what we want it to be within our object.
Source: ttp://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/

Another reason to use this is so that you could share a method between multiple objects.
You could create a function example that returns "this.property". Then you can call that method for different
objects, when it is called, the this will reference the object you said should be called.
Source: Javascript For Kids by Nick Morgan
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
This is a keyword which can be used inside of a method to refer to the object on which
the method is currently be called on.
Source: Javascript for Kids by Nick Morgan
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
There are two aspects to a protoype:
  1. Prototype Property
    1.1 If you add a method to a constructor's prototype proerty, that method will be
         available to as a method to all objects created by that constructor. Sharing!
  2. Protoype Attribute
    2.1 Any objects created with the new keyworkd will inherit that object's attributes.

    Source: http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language
```
