# This and Prototype Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

-   [MDN: This](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)
(only up to and including the "As a Constructor" heading).
-   [JSIS: This](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)
-   [JSIS: Prototype](http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/)

## This in Context

In your own words, explain one reason why we use "this". In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Clarity and, this is a guess, to help avoid namespace collisions? This also
seems to help with our ability to create object constructors, since we can make
a constructor, then assign a new instance of it to a variable, and then the
constructor's properties become associated with the variable name, e.g., a.foo()
is a new object a that inherits the this.foo() method from the object constructor.

[JSIS](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)
[Naming Collision](https://en.wikipedia.org/wiki/Naming_collision)

```

## This is what

In your own words give explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
The "this" keyword acts like a pronoun and is replaced by whatever object
"owns" it. From the readings, determining what exactly "this" acts as a pronoun
of can be tricky.

[JSIS](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)
[stackoverflow](http://stackoverflow.com/questions/3127429/how-does-the-this-keyword-work)

```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is a property and an attribute of an object; it allows us to set up
inheritance in JavaScript, i.e., children/descendents of an object inherit the
parent object's properties, the parent's parent object properties, etc.
Prototypes of an object point to an object's parent (so we can go up the
inheritance chain looking for a property).

[JSIS](http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/)
[stackoverflow](http://stackoverflow.com/questions/18298435/prototype-and-constructor-in-javascript-plain-english)
```
