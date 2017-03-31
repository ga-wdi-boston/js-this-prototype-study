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
<!-- when used correctly, it helps keep our code from breaking.  The main
example that comes to mind is if there are multiple global variables with the
same name.  Using 'this' prevents those other global variables from being
called if you call them by their name.  source: javascriptissexy.com-->
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
<!-- 'this' is very contextual and weird.  contextual because it refers back to
the value of the object we are calling out within a function (which allows us to
easily and simply reference those values in our calculations/functions),
and weird because even though we believe that is contains the value of that
object, it's not assigned until the function is executed, which can make things
tricky.  source: javascriptissexy -->
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
<!-- the way i read it, a prototype is a property that you imprint on an object
or a function that you'd like to pass along to another object of function,
depending on the situation.  the new object inherits the property without
needing to create a new function.  another feature is the prototype allows you
to call back on an object's lineage, find the parent, grandparent, etc.  -->
```
