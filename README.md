# Writing a Function in JavaScript

![Computer with Code](https://images.unsplash.com/photo-1634838037553-66f5ce322212?w=400&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8Y29kZSUyMGNhdHxlbnwwfHwwfHx8MA%3D%3D)


In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. ___Basic Syntax___

const functionName = (params) => {
  // code to be executed
}

1. **const**: const should be used whenever a function expression is assigned to a variable.
2. **The function name**: The name you choose for the function.
3. **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () 4. is still required.
5. **The arrow syntax**: Indicates that this will be a function.
6. **The body**: The statements that make up the function itself. Surrounded by curly braces.

___Example___:
```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}

```

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

## 2. ___Calling___ a ___function___

To execute the function, you call or invoke it by using its name followed by parentheses.

Example:
```javascript
greet('Alice'); // Outputs: Hello, Alice!
```

## 3. ***Return values***

Functions can process data input and output a value using the return keyword.

___Example___: 
```javascript
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```

For more information on functions and how they are used in JS, check out this the [MDN Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
