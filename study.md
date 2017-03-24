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
 In your own words, explain one reason why we use "this". In your answer, be sure to cite any relevant sources you consulted in your search.

```md
Having programmed in Java, I thought of 'this' as refering to the current
object that is in scope. Allowing distinct access to work with my objects properties.
A case that I've used in the past is when 'let someVariable' is defined both globaly(object)and within a function in the same object, you would use this.someVariable to explicitly use the one inside side the function. Typically this is when a
variable passed in is the same as one already in the object.

functions in java will have access to the this pointer of the object that calls it.
If the object is a button that is calling the function, it will have access to
the this of button. Interesting using 'strict' some of the this rules change.

As I read more on how 'this' works with javascript...scope plays a large role in
determining what 'this' and how the object was created. If new is not used in
the creation, then you go up the chain. Readings tell you that you can even
manipulate the 'this' with apply() and call() allowing us to
pass in an object to use the objects 'this'.

http://www.digital-web.com/articles/scope_in_javascript/
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this
```

## This is what

 In your own words explain "this". In your answer, be sure to cite any relevant sources you consulted in your search.

```md
The this pointer implicitly assinged when creating a new object. If new is not
used when creating say a function, the this pointer is the global object.

functions in java will have access to the this pointer of the object that calls it.
If the object is a button that is calling the function, it will have access to
the 'this' of button. Interesting using 'strict' some of the this rules change.

As I read more on how 'this' works with javascript...scope plays a large role in
determining what 'this' and how the object was created. If new is not used in
the creation, then you go up the chain. Readings tell you that you can even
manipulate the 'this' with apply() and call() allowing us to
pass in an object to use the objects 'this'.

When we use ‘new’, JavaScript injects an implicit reference to the new object being created in the form of the ‘this’ keyword.

It also returns 'this' reference implicitly at the end of the function.

http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
http://stackoverflow.com/questions/710542/jquery-javascript-this-pointer-confusion
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
_proto_ ES6
Prototype is a property that allows inheritance, meaning that properties and methods of
objects in the chain of objects associated with this object can be used
as if they are part of the object you are currently working with. Often these
 are referred to as the 'Parent' properties.

http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/
http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/
https://github.com/stevekwan/best-practices/blob/master/javascript/gotchas.md
```
