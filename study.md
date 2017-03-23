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
According to the Javascriptissexy article, the keyword this refers to the local version of a variable within a function or object.  If you were to use person.name with the person object instead of this.person, it can create confucsion if you have multiple person objects.
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
In Javascript is sexy, 'this' is a referrent.  It points to the object closest to it.  For example, if you are inside an object called foo with a variable bar, and you also have a function in that object that adds 1 to bar, calling this.bar specifically refers to the bar variable in the foo object.  This always refers to the object that it is called from.  It is not assigned a value until an object invokes the function where this is defined, according to Javascriptissexy.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is a method assigned to an object that other objects can inherit from.  For example, if you have an object room, you can use prototype to give it a prototyped method called goToMyRoom().  So if you create a new object called myRoom = new room(), myRoom, would be able to use the method goToMyRoom.
```
