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
We use 'this' to prevent code from bugs: if we have to change all our code because we didn't use 'this' then we could miss an edit and the whole code goes boohoo.

Source:
I don't learn well from reading therefore I watch videos:
https://www.youtube.com/watch?v=URVdQG96MUw&t=308s
https://www.youtube.com/watch?v=yVdU2coJ1VQ
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
For the purpose of your current knowledge in web dev and the fact that we currently always use 'use strict', most simply put, 'this' is a shortcut. It allows you to refer to a value of an object when calling a function.
Source: http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is an object of a function. All functions will have an object whether defined or not which will be the prototype. If a function has multiple objects, then all these objects will share the same prototype and it's properties. To access a prototype's property directly from the function it would be '.prototype' but from one of the other objects in the function it would be '.__proto__'. It is super useful as it works at run time which is why it is like a better tool than class.
sources:
https://www.youtube.com/watch?v=z19gt-wslCo&index=12&list=PLqq-6Pq4lTTaflXUL0v3TSm86nodn0c_u
https://www.youtube.com/watch?v=F4GL4M3wmuw&list=PLqq-6Pq4lTTaflXUL0v3TSm86nodn0c_u&index=13
https://www.youtube.com/watch?v=qUBcYdWlkz0&list=PLqq-6Pq4lTTaflXUL0v3TSm86nodn0c_u&index=14
```
