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
We use "this" to make our code more precise. When you use the variable's name (e.g. person.name instead of this.name), there could be another global with the same name. The use of 'this' makes our code less ambiguous.
I consulted javascriptissexy.com for this answer - they made a very useful analogy - comparing "this" to using pronouns.
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"this" is used to refer to an object, and is used as a shortcut to make code more elegant and precise. What "this" is depends heavily on the context.

I used mainly javascriptissexy.com for my answer. Found this source much easier to understand.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
In Javascript, every object and function has a prototype, and this prototype is used for inheritance (for the most part). For example, if you create a function creature() - every time you make a new instance of creature (let aCreature = new Creature()), this new instance, which also has a prototype, inherits the prototype from the first one.

Again, I used mainly javascriptissexy.com for my answer.
```
