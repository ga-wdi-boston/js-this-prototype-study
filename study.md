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
We can use "this" to help with both concision and precision. "This" refers specifically to the containing object of the function in which "this" is being used, which lets us avoid repeating the name of the object (and potentially confusing that name with another object/variable). 

Source: "JSIS: This"
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"This" is a reference to the object that contains the function where "this" is used. It lets us more easily access that object's value/properties. ("This" can be tricky, as its value changes depending on the context in which the function that uses it is called.)

Source: "JSIS: This"
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is a property (to which a set of properties and methods can be attached) of all JavaScript functions. All instances of a function inherit that function's prototype properties and methods. Prototypes let us define a standard set of attributes/behaviors for a particular kind of things, then create instances of that kind of thing that can have unique attributes/behaviors while sharing the same basic template. All objects in JS have the same ultimate parent, the Object prototype object (which lets us access methods like Object.keys(obj), among other things). Prototypes facilitate inheritance, given that JavaScript doesn't have classes.

Sources: "JSIS: Prototype", [A Plain English Guide to Prototypes](http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/), [MDN: Object.prototype](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/prototype) 
```
