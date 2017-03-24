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
<!-- your answer here -->
```
The 'this' keyword can be used in a function to refer to the actual object
that invoked the function. For example,

  var car = {
    model: "DB8",
    make: "Aston Martin",
    topSpeed: function () {
      console.log("There is no top speed when driving an " + this.make + " " + this.model)
      console.log("There is no top speed when driving an " + car.make + " " + car.model)
    }
  }
  car.topSpeed()

Both console commands yield the same answer. However it is prefereable to use 'this'
because sometimes you might need to invoke an object that doesn't have a name
(annonymous object) and you could use 'this' in that case.


Source:
http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/


## This is what

In your own words explain "this".  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
<!-- your answer here -->

As I mentioned above (I'm not sure in the differences in Q1 and Q2 to be honest)
the 'this' keyword can be used in a function to refer to the actual object
that invoked the function.
There was a good analogy on sources below of not referening to someone's name
continually in a conversation. Instead you'd use 'he' or 'she' after naming that
person at the beginning. Similarily you'd declare and assign a variable initially
and then use the 'this' keyword thereafter to refer to that variable rather than
referring to it using ObjectName.attribute. You could just use this.Attribute.

It really acts like a shortcut or pointer to the Object itself.

Apart from attributes, when the this keyword is used in a function as in the example
above in Q1, it's value is associated to the actual object that invoked that function.

One other thing I read on the source below is that the this keyword is not assigned
any value until an object invokes the function.



Source:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this

http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/


## A Prototype is what

In your own words explain what a prototype is.  In your answer, be
sure to cite any relevant sources you consulted in your search.

```md
<!-- your answer here -->
Prototypes are a type of inheritance that is found in the Java language for example.
In JavaScript, you implement inheritance with the prototype property.

I think this example will help explain my understanding of a prototpe better than
writing words here. In keeping with the car theme, here goes:

//PARENT function:
function Vehicle () {
  this.model = 'DB9'
  this.make = 'Aston Martin'
}

Vehicle.prototype.showWhatYoudLike = function () {
	console.log("I would like to drive an " + this.make + " and the model must be a " + this.model + " and it must have the color " + this.color + ' and be a ' + this.roof)
}


//CHILD function
function Car (color, roof) {
  this.color = color
  this.roof = roof
}

//The Car is a child of the Vehicle prototype:
Car.prototype = new Vehicle ()

//Even though you pass in 2 args, 4 are used in the function above from both parent and child functions
var dreamCar = new Car ('red', 'convertible')
console.log(dreamCar.showWhatYoudLike())




Source:
http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/
http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/

```
