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
'this' can be used to make code more human-readable since it acts like a pronoun and can shorten our code.  It makes our code more intuitive and makes us more aware of the context within which we are working because we have to pay attention to its antecedent.  Similarly, as with another aspect of pronouns, it can be useful when we want to talk about something that we don't know everything about (do the thing to whatever 'this' is).
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
'this' is a placeholder for an object whose identity we don't yet know.  It allows us the flexibility to write generalized functions that don't care specifically which objects call them.  However, the tradeoff for this flexibility is that 'this' is highly context-specific, and what it refers to can change unexpectedly if we're not familiar with how it works.  It can be used globally and locally, and if used in multiple scopes, it can cause conflicts.  Thankfully these conflicts can be resolved by using functions like 'apply' and 'bind' in order to manually specify the context of 'this'.  (Source: JSIS - understand javascripts this with clarity and master it)
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is the model that defines the structure and behavior of all instances of itself.  We can add to the prototype even after it has been created so that any instances declared afterwards will inherit any new functions or properties from the updated prototype. The prototype concept in Javascrpt is what gives the language the capability of inheritance, which is fundamental to object-oriented programming and is utterly essential for DRY programming because it allows us to share properties and functons between different classes of objects, avoiding the need to rewrite the same properties and functions in new contexts (Source: JSIS - javascript prototype in plain detailed language.)
```
