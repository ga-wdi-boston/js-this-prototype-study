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
We use "this" to both avoid potential bugs depending on variable names and to
have more flexible code in certain functions. With "this", bugs related to typos
and spelling are reduced for certain functions, as the names of objects do not
need to be repeated. Bugs related to other objects having access to methods
they shouldn't have access to are also avoided.

-   [JSIS: This](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
"this" refers to the object that invoked a function. On a page with many buttons
that have access to the same function, "this" provides an easy, quick way of identifying
which button was clicked and running the function. Without "this", the page
would have to search through "button1, button2, button3, ..." to find the
correct button, then run "buttonN.function()", which implies extremely long code
and long runtimes.

-   [JSIS: This](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
Prototype is how Javascript does inheritance. A prototype contains all of the
properties and methods of an object that all objects of that type are to have
in common. For example, every Clock object should have hours, minutes, and
seconds, as well as methods for incrementing those values. Clock.prototype will
contain all of these, and when "let alarmClock = new Clock();" is called, a new
alarmClock object will be created with the Clock constructor and will contain
everything the Clock prototype has. Functions to set a wake-up time and a snooze
button can be added to the alarmClock without affecting the Clock prototype. In
addition, an alarmClock prototype can be created, and any new alarmClock objects
created from the alarmClock prototype will inherit the wake-up time and snooze
button functions, as well as the hours, minutes, seconds, and time increment
functions from the Clock prototype.

-   [JSIS: Prototype](http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/)
- I also have some experience with inheritance in Java.
```
