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
This makes code less ambiguous. It prevents confusion between a global variable and an object within a function to hone in on the code.

source use:

```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
I realize what 'this' did today in class when I saw it in the midst of a function and even then I struggled to be able to define its
function. The readings helped a bit but I think I still may struggle to identify its purpose. 'this' calls back to the variable in the function it
function it is in. What doing this does is eliminate confusion for the function so it doesn't get mixed up with a potential global variable. I also had to look up a global variable which is a variable outside of a function. 'this' refers back to the object that is used within a function and is most often used in a function.

The easiest way for me to envision it in my mind is through an example:
function carStats(){
  this.Year: 2008
  this.Make: Jeep
  this.Transmission: Standard
}

In this example, this relates specifically to carStats which makes it non-redundant and prevents conflict with global elements.

sources used:
http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
prototype allows you to use methods/properties later on. The prototype inherits its funcionality from uses earlier on in the code. If there isnt a use of a prototype then the object or array uses a sort of built in prototype that is standard with JS and is created based directly off of what the  programmer has named the object or array.

Prototype allows for inhertiance which is not built into JS. Much like a person examines their inheritance by looking at the person previously in their lineage to see how they got a trait, JS will use protypes to look backwards to see the way in which an object should be identifies.



sources used:
http://www.w3schools.com/js/js_object_prototypes.asp
http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/
```
