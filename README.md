# **Writing a Function in _JavaScript_**

![Bahrain in 1992](https://images.unsplash.com/photo-1745949779026-f7fdd1470f8c?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

### In _JavaScript_, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in _JavaScript_.

1. Basic syntax ```
const functionName = (params) => {
  // code to be executed
} ```
 * **const**: const should be used whenever a function expression is assigned to a variable.
* **The function name**: The name you choose for the function.
* **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
* **The arrow syntax**: Indicates that this will be a function.
* **The body**: The statements that make up the function itself. Surrounded by curly braces.
 _Example_:
```javascript
(name) => {
  console.log("Hello, " + name + "!");
}
```

>  _Tip_: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include 
```javascript fetchData( ), calculateArea( ), or printReport( ). ```

 
2. Calling a function
To execute the function, you _call_ or _invoke_ it by using its name followed by parentheses.

_Example_:

``` greet('Alice'); // Outputs: Hello, Alice!```

3. Return values
Functions can process data input and output a value using the _return_ keyword.

_Example_:
```javascript
 const addNums = (numA, numB) => {
  return numA + numB
}
const total = addNums(2, 4);
console.log(total) // Expected value: 6
```

For more information on functions and how they are used in JS, check out the MDN docs.
[Click Here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

