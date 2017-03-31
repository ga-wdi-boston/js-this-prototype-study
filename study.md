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
the this keyword can be used to point to a specific object when used within a function without running the risk of going out into the global scope where a different object could have been created with the same name that when the code is initialized will change the value of the first object breaking the code.  This behavior happens because when used within a function the this keyword is not run or (initilized) until the function is called.
wtached a informative video on youtube that showed the vunerabilities of not using the  (this) keyword. https://youtu.be/URVdQG96MUw
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
The (this) keyword is the owner of a function when used correctly so within the function it is common knowledge that (this) is the function name.

```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Every function has a protype property, when you want to implement attributes stored within the original to a newly created object you use __proto__ to do this, so all attributes and properties flow down to the new object.  This allows you to reuse your work over and over again.  The new object can have its own attributes also so this allows for the creation of more complex objects with less work. I used the required reading and a conversation with a seasoned dev. for a little extra clarity.
```
