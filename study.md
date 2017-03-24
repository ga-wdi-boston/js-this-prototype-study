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
"this" in short help defines our code so that it becomes more rebust. for example:
if you set a obj and 'this' is a function within that obj. 'this' Will pull the obj.
that would be more rebust then if you had a function that had the obj.xxxx.  Since
that would be easy to break.

answer was off the top of my head but read the study guide and watch youtube videos
google to other sites etc.
```

## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
'this' is defined to what you are pointing it too.  for example: if you have it
in a obj as a context within that function the 'this' will point to that obj.
it could be used for a method etc.  'this' also === windows (golbal object) when
not defined within a function/object or not pointed to.  if in a function and used
'use strict' it could give a response of undefine if its not defined or if not strict
will go back to windows (golbal object).

answer was off the top of my head but read the study guide and watch youtube videos
google to other sites etc.
```

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
prototype is like a delegate, it will delegate to the object that you define.
like for example if had a prototypeof (aaa, bbb) it will look at object aaa and if
can't find what its looking for look at object bbb.  In short, it like setting up
a backup for an object to seach for the thing that might be missing.
Also prototype does not create a copy not like class.

Look at random you tube videos and read our documentation and other site.
```
