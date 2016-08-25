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
this can be used to refer to keys or methods inside the object to which it is
bound.

For example:

let neptune = {
  species: "cat",
  sex: "male",
  color: "gray",
  sound: "meow",
  makeSound: function(){
    return this.sound;
  }
}

I do not need to write return neptune.sound because the method is inside the
object and it is just not necessary.
```
http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this
## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
this is effectively a prounoun
in JavaScript world and it makes the code easier to read and less
cumbersome. To call a method from outside the object,
however, I would have to use the object name when calling the method.
```
http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/

## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.
```md
prototype is used for inheritance of properties and methods in constructor
objects. It also allows other objects to inherit it.
Here's an example (once again, with cat fails):

function CatFail(shriek){
	this.fail = shriek;
}

CatFail.prototype.epicFail = function(){
	console.log(this.fail);
};

let neptuneFail = new CatFail("MrrrreeeeOOOOW!");

neptuneFail.epicFail();

neptuneFail has inherited from CatFail, and so it can call the epicFail method.
```
http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/
