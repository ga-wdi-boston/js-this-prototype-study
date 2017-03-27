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
The main use of the 'this' seems to be to be able to give a value to and also call a specific object from a function without having to rewrite a bunch of code to access that object. The use of 'this' depends a lot on the context of the code. The value of this can have any value but the value depends on how the function is called.
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Outside of functions, 'this' refers to the global object, which is determined by whether or not you are in strict mode. When not in strict mode, this will refer to the global object itself, i.e a window, a document, etc. But in strict mode, the value depends on how the object within a function is used by using 'this' and if there is no value, then it will be undefined. The 'this' fuction can be used to make code more precise and less confusing when refering objects to functions they are bound to. The assigned value is based on the object that the this function is refering to from previous lines of code. The ways 'this' values can be defined is through .call(), .bind() and .apply().

These are the pages I looked at
https://toddmotto.com/understanding-the-this-keyword-in-javascript/
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Prototypes have attributes or characteristics that help define an object. The prototype attributes are the inherent features and basic properties that functions must follow to work depending on the coding language you are using. New properties that are defined are assigned to the object the prototype refers to but not added to the basic properties that protype follows initially. These new properties are added along to make a prototype/object chain, where the initial function prototype is the first link on the chain. Using protoype chains, we can add properties to objects which can then be called upon later in the code. Prototypes allows an object to have a base property that will stay the same as other properties are attached to the object.

These are the pages I looked at
http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/
http://yehudakatz.com/2011/08/12/understanding-prototypes-in-javascript/
```
