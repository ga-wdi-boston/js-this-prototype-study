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

```
as in our Computer object in yesterday's class, we use this in the case of 'this.objectMethodsName' when calling a method upon our object.   This is more elegant code than having to write 'objectname.objectMethodsName'.  It basically, lets us call a method defined in an object upon itself with a simple 'this'.  Additionally, if an object is declared in another function, using 'this.methodCall' prevents us from potentially calling another global-scope object with the same name as the local scope object.   It prevents confusion for the person reading the code.
cite http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it
first 3 paragraphs
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```
When writing an object and it's properties, this is a shorthand way of referring to an object's OWN properties.  THis is especially helpful when writing methods inside an object.  IN a method definition (it's defining code) this allows us to refer to a a key and it's key value pair by "this.key".
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```
A prototype allows us to declare a function ONCE, for an class instead of having to declare it many times in each object.
Citation: codeacademy.com : Prototype to the rescue
```
