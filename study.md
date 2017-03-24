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
The "this" keyword makes it easier for developers to reference a thing that
was just "worked" so to speak. It also is easier to type than a full name of
something. Developers like to be... efficient. ;) I like to be soooo efficient.

ref: articles listed above and ref: https://www.youtube.com/watch?v=JduQUNn7L4w
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"this" is a way for developers to refer to thing that is in context. So when nothing
has been invoked yet, "this" would refer to the window of the webpage. Then if
an object method has been invoked, then the "this" in the method refers to the invoked object.
If a function has been invoked, then the "this" in the function refers to the function.
Visualize your scope as circles. The Window is a big circle around everything.
In the case of "this", methods and functions are littler circles within the
Window circle. A function circle or a method circle can contain each other.
"this" would refer to the circle in which it exists.

So if a method invokes a function that is using "this", visually I am picturing
a function bubble inside of an object bubble and the word "this" is applicable
to only the function bubble. There are ways to explicitly set the scope for
"this". The developer can use the call or apply method.

ref: articles listed above and ref: https://www.youtube.com/watch?v=JduQUNn7L4w
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is Javascript's way of doing inheritance. I understand what
inheritance is, but I still don't grasp how and when I can use the different
ways to use prototype to create inheritable javascript objects.
```
