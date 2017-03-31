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
We use t-his to refer to object we are currently inside of for same reason we use pronouns in the english language.
We would say "John called me today, he said he missed me" and not :"John called me today, john said he missed me."
Both are essentially correct but the second is never used, sounds clunky and technically the second time we say john
we could be reffering to a different a john.

let obj = {
  name: Arlo,
  printName: function(){  <---- less eloquent
    console.log(name)
  }
}

let obj = {
  name: Arlo,
  printName: function(){  <--- more eloquent
    console.log(this.name)
  }
}

t-his also lets use the printName method on another object in the future.
I referenced http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
t-his is a variable with the value of the object that calls the function it is inside of.
It doesnt get assigned until the function is invoked. the t-his variable is only available inside of its function.
I referenced http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
 protoype is a property that every function/object in javascript has. You attach properties and methods onto this prototype property
when you want its children to inherit those attached properties and methods.

Also,

prototype is an attribute that every object has that points to its parent, the object that it in inherits its properties from. The properties and methods that get inherited are
ones that are attached to the parents prototype property. The inherited properties and methods do not get copied they are searched for within a 'protoype chain' if they get invoked.


```
