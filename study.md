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
"this" could be used to refer to the object that a function is being called from,
such as:
  function foo(){
    return this.a;
  }

  let my_object = {a: 'Hey me!', foo: foo};

  my_object.foo();

Sources:
https://john-dugan.com/this-in-javascript/
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"this" is a feature(? dunno the proper "thing" that "this" is) in javascript
that refers to the object that is executing the current block of code.
tl;dr this is a reference to the object that currently holds context.
E.g. "this" refers to the object that a function is bound to, such as
obj.foo(), where foo's "this" is equal to obj. foo's 'context' is obj.

Sources:
https://john-dugan.com/this-in-javascript/
http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
prototype is the parent object that an object inherits from (all objects have
a parent object). E.g. const myChild = new theParent(); theParent is the prototype of myChild. 

Sources:
http://www.w3schools.com/js/js_object_prototypes.asp
http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/prototype
```
