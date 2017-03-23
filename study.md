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
One use would be to have the ability to change the context of a function. This
is used to refer to something different than the scope its in. I would say
the major reason to use it is if you need your variable to be dynamic.

Resources: http://stackoverflow.com/questions/3127429/how-does-the-this-keyword-work
http://www.digital-web.com/articles/scope_in_javascript/
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
This is used refer to objects and functions that we are currently working
with. It seems to be mostly about scope control. I've read that local variables
will take precedence over those higher in the scope chain, so this allows us
to control the variables at a local level.
Same resources as above.```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Just like "this", an object's prototype is dynamic. Simply put, it acts as
a template for objects to inherit certain traits. It appears that the
parameters we list within functions act as prototypes. Defining the template
can let you can use this
to assign attributes to newly created objects as well.
resources: http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/```
