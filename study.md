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
`this` can be used in a lot of ways. I think the way that is most familiar
for me is that if you are defining an Object method, `this` refers to the
object you are in, or the instance of the object if you are in a prototype,
so you can use `this.value` to access another attribute or method of the
Object you are in. It is important because when we define the function, we
may not know the name of the Object that will ultimately be calling it.

Another reason we use `this` is that it refers unambiguously to the present
context. It will not reference a global variable outside of this context
that happens to have the same name.

I mostly just knew this from reading online, but the first and
second links above helped, especially with the second reason I wrote.
```

## This is what

In your own words give explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
`this` is a JavaScript keyword that refers to the context you are in. It is
like the actual scope. So if you are in a window where the global context
is the window then `this` refers to the window. If you are in an Object it
refers to the Object. It is the scope that your scoped variables are accessible
within at that time, so it changes as your program executes and the scope
changes.

I used the first link above.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
A prototype is like a class in some other languages, but it is defined
for functions, which are Objects, rather than specifically on new things called
classes. A prototype is is an Object definition that will likely be used,
or instantiated, many times. For example, in a war simulation,
you might have a prototype soldier, with various attributes
and methods. Then you can instantiate that soldier many times to build up armies
of entities who all have those attributes and methods, and are yet distinct.

I read the third link above, but first I wrote that paragraph from just my
feeling about what this probably was/what I talked about with Brian earlier.
```
