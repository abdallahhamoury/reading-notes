## Error Handling & Debugging

There are two types of errors in JavaScript. The first is a programming error, where we, the JavaScript developers, do something wrong. These types of errors are typically found using our favorite browser and our favorite debugger.

At a minimum, what we need from a debugger is the ability to stop program execution and then examine variables and objects at that point. It also helps if we can continue the program by steps, drill into functions, and examine network activity and the state of the DOM at any time. However, we can usually manage debugging if we have the ability to stop a program and examine object values.

The second type of error occurs when the web page reader answers a question incorrectly, pushes the wrong button, or tries to type in a Social Security number when we’re expecting a name. Or the error can happen when we’re mixing libraries and something goes wrong between them. We’ll look at these kinds of errors first, and then we’ll get into the various browsers and their debugging capabilities.



![erorr](https://www.valentinog.com/blog/static/199d49f6c5443ce3336c96cf4e2395f8/c1b63/error-handling-javascript.png)

> A simple way to return an error from a function is through the result. The important point to remember is that the return value and type need to match what you would expect from the data type of the result if things had gone well.

In the solution, the global `NaN` value is returned if the array was empty, or has at least one entry that isn’t a number.
The result is tested with the is `NaN` function, and if the result is `NaN`, a message to that effect is given.



![erorr](https://miro.medium.com/max/2514/1*s8MYrR4abDGWXrOKDUEFGA.png)


Error types
Besides the generic Error constructor, there are other core error constructors in JavaScript. For client-side exceptions, see Exception handling statements.

- EvalError
Creates an instance representing an error that occurs regarding the global function eval().
- RangeError
Creates an instance representing an error that occurs when a numeric variable or parameter is outside of its valid range.
- ReferenceError
Creates an instance representing an error that occurs when de-referencing an invalid reference.
- SyntaxError
Creates an instance representing a syntax error.
- TypeError
Creates an instance representing an error that occurs when a variable or parameter is not of a valid type.
- URIError
Creates an instance representing an error that occurs when encodeURI() or decodeURI() are passed invalid parameters.
- AggregateError
Creates an instance representing several errors wrapped in a single error when multiple errors need to be reported by an operation, for example by Promise.any().


