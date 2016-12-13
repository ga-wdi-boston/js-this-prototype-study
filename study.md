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
One reason we use "this" is to be able to refer to a variable from within the
variable's code. For instance, how in Javascript Is Sexy's first example, "this.firstName"
"this" refers to "person" which is the variable the function is within.
This allows us to not have to use "person" which could be a variable name elsewhere, and
is more clear that it is referring to the variable the code is within.
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"this" is a keyword which refers to the subject of the code. What it references
depends on context. It is helpful as a shortcut and when used within a variable,
to clarify that we are referring to the variable the code is within.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Prototype is a property which allows inheritance. Methods and properties added to
the prototype property of a function can be accessed when that function is used elsewhere.
As Mozilla Developer Network's documentation notes, this allows us to create "sub-classes"
of functions which can access the same property.
```
