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
When used inside a function/object, it is used to clarify specifically which variable is being referred to.
It has no value until it is assigned (?) one by invoking the object it is referred to.

It works as a pronoun to refer to a variable/function previously declared within the object (or scope?).

```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Still a little confused on this. I think something along the lines of:

If used within a variable, it then refers to that object.
If it's NOT used within a variable, it then is a 'global' object (such as your browser window).

```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
All functions have inherently have prototypes, but by (explicitly?) adding a prototype to a function, if you later create a variable that holds that function, you can attach the properties of the initial function.

I think it basically allows you to create a revised/updated/additional 'new' version of a function, while keeping the properties of the initial function ('constructor'). Or, to assign an additional property to an existing object.

```
