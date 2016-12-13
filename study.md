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
Utilizing "this" is beneficial insofar as it allows a developer to save time.
For instance, imagine having the following object:

let myCar2 = {
  maxSpeed : 70;
  driver : "Net Ninja";
  drive: function (speed, time) {
    console.log(speed * time);
  },
  test : function () {
    console.log(this)
  }
};

And suppose you had several copies of the object:
let myCar3 =
  maxSpeed : 70;
  driver : "Net Ninja";
  drive: function (speed, time) {
    console.log(speed * time);
  },
  test : function () {
    console.log(this)
  }
}

In every instance where "this" appears, you would have had to otherwise write
console.log(myCar2)
console.log(myCar3)

https://www.youtube.com/watch?v=yVdU2coJ1VQ
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
The "this" keyword refers to whatever object currently owns the space (context)
that utilizes "this". And simply going by the MDN article on "this" it seems
like the keyword operates in several different contexts (e.g. global and function).
Not only does the contextual environment affect "this" but also how it is invoked
can return different evaluations, which then becomes important to implement
different methods (e.g. apply, bind and call).

```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
This is a fundamental concept of the Javascript language itself in respect to objects.
Because Javascript is a prototype-based language, every object has a prototype.
You can add properties and methods to the object's prototype property, and those
properties and methods will be inherited in all the instances of that particular
object.
http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/
```
