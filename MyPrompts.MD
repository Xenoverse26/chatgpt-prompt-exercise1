prompts
what is a class in JavaScript?
In JavaScript, a class is a blueprint for creating objects with shared properties and methods. It is a way to define a template or a structure 

for objects that you want to create in your code.
 
 JavaScript introduced class syntax in ECMAScript 6 (ES6), making it easier to work with object-oriented programming concepts.

Here's a basic example of how to define and use a class in JavaScript:

class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  sayHello() {
    console.log(`Hello, my name is ${this.name} and I am ${this.age} years old.`);
  }
}

// Creating objects (instances) of the class
const person1 = new Person("Alice", 30);
const person2 = new Person("Bob", 25);

// Calling a method on objects
person1.sayHello(); // Output: Hello, my name is Alice and I am 30 years old.
person2.sayHello(); // Output: Hello, my name is Bob and I am 25 years old.

In the example above:

Person is a class definition, and it has a constructor method that is called when a new object is created from the class.

 The constructor sets the initial properties of the object.
sayHello is a method defined within the class, which can be called on instances of the Person class.

Classes provide a convenient way to organize and structure your code, making it more readable and maintainable, especially when dealing with complex objects and their behaviors.

 They are a fundamental concept in object-oriented programming (OOP) and are widely used in modern JavaScript development.





