#### Read: Class 09
---------------------------------------------------------------------------------

##  FUNCTIONAL PROGRAMMING

### 1-What is functional programming?

Functional Programming is a programming paradigm where you mostly construct and structure your code using functions. ... It presents an answer to its elegant function in a straightforward manner. It's also worth noting that JavaScript is a multi-paradigm programming language and Functional Programming is one of them
![Image of Yaktocat](http://softwarebrothers.co/blog/content/images/2020/02/funtional-js.png)

### 2-What is a pure function and how do we know if something is a pure function?
A pure function is a function which: Given the same input, will always return the same output. Produces no side effects

### 3-What are the benefits of a pure function?

One of the major benefits of using pure functions is they are immediately testable. They will always produce the same result if you pass in the same arguments. They also makes maintaining and refactoring code much easier.

### 4-What is immutability?

In JavaScript, only objects and arrays are mutable, not primitive values. ... A mutable object is an object whose state can be modified after it is created. Immutables are the objects whose state cannot be changed once the object is created. Strings and Numbers are Immutable

### 5-What is Referential transparency?

Referential Transparency emphasizes that an expression in a JavaScript program may be replaced by its value or any other variable having the same value without changing the result of the program

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 1-What is a module?

Module pattern. The Module pattern is used to mimic the concept of classes (since JavaScript doesn't natively support classes) so that we can store both public and private methods and variables inside a single object — similar to how classes are used in other programming languages like Java or Python

### 2-What does the word ‘require’ do?

The require() method is used to load and cache JavaScript modules. So, if you want to load a local, relative JavaScript module into a Node. js application, you can simply use the require() method.

### 3-How do we bring another module into the file the we are working in?
The static import statement is used to import read only live bindings which are exported by another module

### 4-What do we have to do to make a module available?
The first thing you do to get access to module features is export them. This is done using the export statement. You can export functions, var , let , const , and — as we'll see later — classes. They need to be top-level items; you can't use export inside a function
![Image of Yaktocat](https://cdn-media-1.freecodecamp.org/images/1*bcZz-qb_DNpvrNNwQBhQmQ.jpeg)

