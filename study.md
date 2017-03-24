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
We use 'this' as a shortcut to reference a property. For example, when using
dot notation for the object below instead of house.district we could use
this.district.

let house = {
  address: '123 Main St',
  county: 'King',
  district: 'Western Washington'
}

I referenced the JSIS: This article as it provided a clear explanation using the
"John is running fast because John is trying to catch the train" vs. "John is
running fast because he is tring to catch the train". I felt this more clearly
described this than the MDN: This article
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
The 'this' keyword is used to refer to an object within the context of the
object. For example, within the object below 'this' refers to the cat object.

let cat = {
  name: 'Garfield',
  color: 'Orange',
  age: 15,
  test: function(){
    console.log(this)
  }
}

When we add another object with similar properties the 'this' within each object
refers to that object. Below the output of test() will refer to the cat object
whereas the output of test2() will refer to the dog object.

let cat = {
  name: 'Garfield',
  color: 'Orange',
  age: 15,
  test: function(){
    console.log(this)
  }
}
let dog = {
  name: 'Snoopy',
  color: 'White',
  age: 27,
  test2: function(){
    console.log(this)
  }
}

I used the MSIS: This article as well as a video on YouTube -
https://www.youtube.com/watch?v=yVdU2coJ1VQ that provied a high level
explanation.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is a property in JavaScript that relates to inheritance and how
objects can inherit properties and methods from 'parent' objects. The prototype
property allows for reuse and removes the need for each object to define its
own properties and methods, instead it can borrow/inherit from a 'parent'.

I referenced both articles listed above about prototype as well as the
article shared in Slack - http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/
```
