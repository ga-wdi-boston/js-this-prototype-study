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
We can use this from within an object's method to reference a different property within the same object.
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
this is a javascript keyword that can be used to reference local variables.  For example, it can be used within methods to reference other properties within the method.  Within the DOM,
it can get confusing because it trys to use the object being acted upon rather than the method in which is was originally located.  You can use binds() or other functions to make
sure that this is referencing the correct variables.  It also varies (in relation
to global variables) based on if you are using 'use strict' or not.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is similar to the classes system in other object oriented programing languages.
Basically it means that obects inherit methods that they can use from the other methods that
they come from.  You can create an object using a different objects as a constructor and then
the new object will be able to use all the methods from the construtor prototype.
All objects originally descend from the Object prototype, and therefore can use Object
prototype methods.  You can also explicitly define methods to be accesible to different 
protoypes using prototype itself as a constructor.  ```
