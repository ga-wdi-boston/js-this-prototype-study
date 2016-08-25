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
One reason we would use "this" is to increase the precision of our keyword usage.
For example, if we were repeatingly using the variable name inside the function, it
would first of all be repetitive and could get a little redundant to read, but could
also open up the potential call upon another property that has the same variable
name somewhere within our code globally. Using "this" will make the code less
ambiguous and easier for someone else or future you to read, since "this" acts
as a referrant to the object.

```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"This" is a keyword that acts as a referrant to the object and holds the value of that
object. "This" is used to access properties or methods from the object that is
invoking the function. "This" is most commonly used inside a function or
method of an object.

'use strict';
let obj = {
greeting: 'Hey,',
name: 'Jim',
getGreeting:function () {
console.log(this.greeting + ' ' + this.name);
}
}

obj.getGreeting(); // This would return Hey, Jim

I consulted the 'Understand JavaScript’s “this” With Clarity, and Master It'
reading for both of these questions, because their explanation really helped me
grasp the purpose and context for 'this'.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is sort of like a blue print for an object. The
object's prototype is inherited by either an object literal (let obj = {}) or by
the constructor function (which is when you assign a parent prototype using the 'new'
keyword to a newly declarded object). The prototype houses properties and methods
of a particular object, and another object can inherit a the 'parent' object's
prototype, in addition to it's own.
 
```
