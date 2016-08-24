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
  `this` helps makes code easier to read, as well as clarifying which instance of the Object
  we are referring to (the surrounding Object).
  `this` is used to refer to the object that contains the surrounding function.
  However, `this` is 'undefined' until we invoke that object's `this` function.

  I'm basing this definition off the description from the JSIS 'this' link above.
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
  We use `this` much the same way we use pronouns in English, to refer to the object that invokes
  the function containing `this.`

  I'm also basing this definition from the JSIS 'this' link above.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
  A prototype is used mainly for inheriting methods and properties.

  When we create new Objects, they come with the prototype property, which we can
  then use to add methods and properties. Any other new instance of that object will
  inherit those methods and properties from the parent object constructor.

  Prototypes can also be used to track the 'family tree' of an object.
  So we can see what an object's 'parent' is (and what it inherits from)
  by using the prototype attribute.

  I based this definition from the JSIS 'Prototype in Plain Language' link listed above.
```
