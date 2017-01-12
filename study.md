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
Much like we use pronouns in the way we talk (i.e. Rick hires actors because he writes the scripts.)  The 'he' in the example refers back to Rick.  In JS, 'this' refers back to the previous object. We use this to keep our code cleaner and to avoid conflicts with global variables.

SOURCE: 'Understand JavaScript’s “this” With Clarity, and Master It' from Javascript.isSexy
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
'This' is used to refer to the object that a function is bound to.  A good example would be the following.
var show = {
name: 'Bryar Lane',
numberActors: '4',

showInfo:function() {
console.log(this.name+" has "+this.numberActors+" actors");
}
}

SOURCE: 'Understand JavaScript’s “this” With Clarity, and Master It' from Javascript.isSexy
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
From what I've read, prototypes are used to extend properties and values from one variable to other variables.
One example which stood out referred to the 'color' property of a cat.  All animals have color so we would use prototype to extend the 'color' property to all animals. 
```
