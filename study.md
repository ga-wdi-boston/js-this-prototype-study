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
'this' helps make the code less ambiguous. It makes clear which object is being referenced in a function.

souce: http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
'```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
'this' is a keyword that refers to the subject of the executing code. If we were to define an object called 'food', it could look like the following:

const food = {
  init: function(type) {
    food.type = type
  }
  eat: function() {
    console.log('you ate the ' + this.type)
  }
}

food.type (line 40) is effectively achieving the same result as this.type (line 43). However, this.type can only be referencing the object to which it belongs (food). This adds more clarity to the code.

Source: https://www.youtube.com/watch?v=riDVvXZ_Kb4
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Prototypes are template objects. The methods and properties in these objects can be applied to other objects.

Let's say we define an object called Food. Then, we define an object called Waffle that is created from the prototype Food. Waffle is going to inherit all of the properties/methods from Food. If Waffle does not have a certain property/method, it will fall back to Food and see if that object has the property/method. If Food does have the property/method, Waffle will use that one.

Sources: 
https://www.youtube.com/watch?v=riDVvXZ_Kb4

http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/
```
