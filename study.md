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

Using "this" is a cleaner, less amibguous way of referencing the object associated with
a given method. If the purpose of the message is to relect on the object it is contained
within and gather/return information, "this" can be used to reference the object rather
than typing out the name of the object (e.g. exampleObject). If there happened to be a
global variable by the same name exampleObject, the code becomes ambiguous. Using "this"
ensures we are precise that we avoid a possible hard-to-address bug if the global object
is referenced. There may also be cases where the object name is unknown for a method we
are creating (this use case isn't totally clear to me now becuase I
haven't seen much code, but I could see how this may be possible in some scenarios).

Resources:
http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
http://www.digital-web.com/articles/scope_in_javascript/

```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"This" is a mechanism for referencing an object without calling on the object by its name.
"This" takes into account scope and context when determing what the value of "this" will be
when it is invoked via a function.

I was able to follow the simple examples in the below resources that discussed local/global scope and how "this" changes value if the same method is used on a global object using the apply() method.

I had a harder time following some of the more advance jQuery examples and nested functions because we haven't seen that yet.

Resources:
http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
http://www.digital-web.com/articles/scope_in_javascript/
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is like a pointer from one object to another. The prototype is the object from which
a given object inherits properties and methods. Essentially, the prototype of an object is the parent
from which it is created.
Prototypes allow us to create a new object that has the same keys and methods as another.

Resources
http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/
http://yehudakatz.com/2011/08/12/understanding-prototypes-in-javascript/
```
