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
One important application of 'this' is in the context of a function in an object.
In that situation, 'this' would automatically refer to the object it's in and makes
it so you can call values within the object in the function without having to type
out the entire object name, thus making it valuable shorthand.

Sources:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
The most apt description of 'this' is from the JSIS: This link {included below}.
The article compares 'this' to a pronoun used to refer to the most immediate object
it is linked to instead of reiterating object names. Even after it is invoked in
the context of a function, 'this' still does not have an assigned value outside of the
object. Thus, 'this' also serves as an intermediary of sorts where its actual value
doesn't matter but it can help produce a variable that requires calling the onject inside
of the method in said object. 'This' can still be used to refer to an object
without a method and will basically apply to whatever object is most relevant.
It is versatile but requires you to be precise in its usage to avoid pointing to the
wrong object.

Sources:
http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this
https://www.sitepoint.com/what-is-this-in-javascript/
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype in JavasScript is an object assigned to a parent object, which can be inherited whenever there is an instance of the parent object is called. The prototype contains a set of values {properties}, which can be adjusted and reassigned and refers back to the parent object. Subsequent objects after the parent object can inherit methods and properties assigned to the prototype. For example, if we have the following:

let parent = {
  key : 'value'
};

let new = {};

If we assign 'parent' as the protoype of 'new', 'new' now contains the properties of
'parent', so if you call 'new.key', 'value' is returned even though 'key : value' was
never explicitly assigned to 'new'. Thus, if a later object is equal to 'new', it will
also inherit the properties of the prototype, or the object 'parent'.

Sources:
http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/
http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/

```
