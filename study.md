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
<!-- your answer here -->

Within an object, "this" is used to refer to the object it is inside. Much
like in the English language, after we have referred to a specific object, the
next time we refer to it, we can use the pronoun "this" instead.

For example:

"I have a really long assignment to complete. I don't know how I'm going to do this.""
"This" refers to "assignment".

The reason for doing this is for removing global ambiguity. If I had again said
"a really long assignment", it could be referring to any really long assignment,
not specifically THIS really long assignment. The same logic applies to JS objects.

Source: http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
<!-- your answer here -->

"this" is a javascript keyword that refers to the object it is used within.
It makes sure that we are referring to the specific method we are within, rather
than a possible conflicting global object elsewhere in the code.

Source: http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/

```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
<!-- your answer here -->

A prototype is used so that new objects will already have the functions within
the prototype when created. For example, if we have a car prototype object, we
might give it prototype functions like drive(), park(), honk() etc. We know that
ALL cars are able to perform these functions, so every new car object will
already have these functions defined. This is an example of inheritance.

http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language
```
