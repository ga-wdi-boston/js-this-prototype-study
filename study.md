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
According to JavaScript.isSexy, this is a convenient shorthand, especially for calling methods on the object that this refers to. However, there are some
situations where the referent of this can switch unexpectedly; being aware of
any potential pitfalls is important.
```

## This is what

```md
Again citing JavaScript.isSexy, this is a property that refers to the object
that this is assigned to. For example, when assigning:

let obj = {
  a: 1,
  b: 2,
  c: 3
}

along with the properties a, b and c, JavaScript also assigns a property this
as a variable that refers to obj.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
While prototype is a property of any object in JavaScript that begins as
undefined, on a conceptual level it is an attribute or attributes of any object inherited from their parent objects. For example, all objects created in
JavaScript inherit properties and methods, such as constructor and HasOwnProperty(), from the Object.prototype naturally. JavaScript.isSexy proved
the most useful resource for this information yet again.
```
