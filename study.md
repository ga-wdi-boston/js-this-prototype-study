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
'This' is a way to refer to an object using a shorthand. This is useful because we can refer back to whatever the object "this" has been assigned to not only that but it will also refer to an object's value.
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
This is shorthand for refering to the object or function calling 'this'. so for example if I wanted to create a person object like:
let person = {
  firstName: 'Dara';
  lastName: 'Hoy';
  showFullName () {
  console.log(this.firstName' ' + this.lastName);//would give Dara Hoy
  }
}
you can see that by invoking 'this' it refers to the data (first and last name) of the object where it was called.

"...this similar to the way we use pronouns in natural languages like English and French. We write, “John is running fast because he is trying to catch the train.”" http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Prototype refers to the attributes of an object that was inherited from its parent object. This can be used to create instances of objects that draws from the properties of its aprent object.

```
