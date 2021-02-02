1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

const percent = function percentage(marks, total) {
  return (marks * 100) / total;
};

const percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
// Function Declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```

Function Expression

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

Function Expression

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

Function Expression

```js
let percentage = (marks, total) => (marks * 100) / total;
// Function Expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

<!-- Ans

Because function is a type of object in javaScript and objects are values and values are expression that is why function definition is an expression on javaScript



 -->

4. Why is a function call an expression in JavaScript?

<!-- Ans

Function call is an expression in javaScript because it always returns a value and values are expression in javaSript .

 -->

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer // valid, because we are calling one function and sorting the value which it is returning in five.
five = add; // Answer Valid, because  we are storing a function defination in five
five = five(10, 11); // Answer, valid, because we are calling the function we stored in five and it will return one value.
five = function () {
  return "Hello";
}; // Answer // Valid,
```

6. What is the difference between function definition and function call? Explain with an example.

<!-- Ans

The difference between function defination and function call is that function defination is a series of step we take to acheive some result, A function call is the code used to pass control to a function.

 -->

7. What is the similarities between function definition and function call?

<!-- Ans

The similarities between function definition and function call is that both are expression
 -->

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log("Hello World!");
}

hello.user = "Sam"; // valid or invalid

// Valid, because function is an object and we can add properties to an object, so here we are adding user property to a function call
```

9. What is higher order function explain with an example.

<!-- Ans:

A function that accepts a function defination as an argument is known as higher order function.

 -->

10. Explain what is callback function. Why you can pass a function inside a function?

<!-- Ans:

The function that is passed as function defination is known as callback function.
 -->
