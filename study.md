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
The "this" keyword can be used to avoid accidently referencing the wrong
variable. As an example, we are working with a local scoped object called car.
The car has a function to return a string with the make and model. However,
instead of using the target object there was an additional global scope variable
named car that picks up instead - and we get an unexpected result or error.
Source: http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
This is a reserved word in JavaScript that can replace an explicit reference
to an object. Instead of car.make or car.printMakeModel() the
object "car" can be replaced with "this". Within a function, the "this" refers
to the corresponding object. In the example below, the "this" keyword refers to
the object in which the function is nested.

let car = {
  make: "Nissan",
  model: "Altima"
  printMakeModel: function() {
    console.log(this.make + " " this.model);
  }
}

Source: http://www.w3schools.com/js/js_object_definition.asp
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is a way to create a blueprint for objects - similiar to classes
in languages such as Java. This allows you to use "Protoype-based inheritance"
which means you can define the functions and properties once rather than
with each new object. For example, you can create a generic "car" prototype
object with make/model properties and printMakeModel function. If you then use
this car as a prototype when creating myCar - you'll be able to use them. The
other key point with prototypes is that you can access the parent (the object
it inherited the property from).

Source: http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/

```
