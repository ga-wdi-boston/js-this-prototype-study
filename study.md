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
This is handily used as an event handler as we did in the pre-work. By using it
in the context of a fuction, each time the function is called this refers to
the object that called it, i.e. the card clicked. In this way we can add our
function to multiple objects. I got some good practice with these concepts
as initally I had my code written in a manner that caused this to call a global
object. After some debugging and some console.log writes I realized this was the
case. I ultimatley figured out to put the this call within the scope of my function
and my code began to work as intended.
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
The Javascript is sexy article explains this in the context of pronouns. In
otherwords, this takes the place of an object and is dependent on it's use case.
Use case is dictated by a number of factors including use of strict or non-strict
code. Additionally, this can be configured to hold certain values inherintly
regardless of its scope of useage as is explains in the sections regarding the
bind function from the MDN article.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
The easiest way to explain prototypes is via inheritance. Each object is the child
of another parent object. Each time a new object is instantiated it gets all the
traits or more specifically methods and properties of its parent object, plus any
new ones that are written in. This continues for each new object instantiated. I
tend to think of these sorts of inhertiance in the context of the overhead
projector slides we used to have in clase. With the bottom layer representing
the parent object and each new object as a layer on top of that, building from the
bottom up. The MDN articles shows this as a series of parent objects and children.
An exmple would be a string object using the method split. This is predfined and
inherited from its parent. You need not write this code as it is inherited when
the object is created. 
```
