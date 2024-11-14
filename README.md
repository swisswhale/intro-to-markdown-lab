# Writing a Function in JavaScript

![JS Function](https://images.unsplash.com/photo-1607799279861-4dd421887fb3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8amF2YXNjcmlwdHxlbnwwfHwwfHx8MA%3D%3D)

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax

```javascript
const functionName = (params) => {
  // code to be executed
}
```

* __const:__ const should be used whenever a function expression is assigned to a variable.
* __The function name:__ The name you choose for the function.
* __Parameters:__ Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
* __The arrow syntax:__ Indicates that this will be a function.
* __The body:__ The statements that make up the function itself. Surrounded by curly braces.

*Example:*

```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```

>Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include: `fetchData( )`, 
`calculateArea( )`, or `printReport( )`. 

## 2. Calling a function

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

*Example:*

```javascript
greet('Alice'); // Outputs: Hello, Alice!
```

## 3. Return values

Functions can process data input and output a value using the *return* keyword.

***Example:*** 

```javascript
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```

For more information on functions and how they are used in JS, check out the [MDN docs.](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

## Part 2: Create another tutorial (30 min)
1) Create a new file with a `.md` extension.

2) Choose a new topic, we’ve provided a few for inspiration:

    * How to write an HTML Boilerplate
    * The anatomy of a CSS selector
    * How to create a file using the Terminal
    * How to build the perfect sandwich

3) Practice your new skills by writing another short tutorial in Markdown!