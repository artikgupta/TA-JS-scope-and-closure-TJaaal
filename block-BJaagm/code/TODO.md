1. What does thread of execution means in JavaScript?

<!-- Ans

JavaScript executes code line by line, that is known as thread of execution.

 -->

2. Where the JavaScript code gets executed?

<!-- Ans

In the javaScript Engine

 -->

3. What does context means in Global Execution Context?
<!-- Ans

Context is the environment in which we are executing our code.

-->

4. When do you create a global execution context.

<!-- Ans

The first thing javaScript engine does as a code snippet gets executesd is that it creates a global execution context
 -->

5. Execution context consists of what all things?

<!-- Ans

global execution context and functional execution context

 -->

6. What are the different types of execution context?

<!-- Ans

global execution context and functional execution context
 -->

7. When global and function execution context gets created?

<!-- Ans

The first thing javaScript engine does as a code snippet gets executesd is that it creates a global execution context

The function execution gets created whenever a function is executed
 -->

8. Function execution gets created during function execution or while declaring a function.

<!-- Ans
Function execution gets created during function execution.
 -->

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.

```js
var user = "Arya";

function sayHello() {
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/1.jpg)

```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount) {
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/2.jpg)

```js
var age = 21;

function customeMessage(userAge) {
  if (userAge > 18) {
    return `You are an adult`;
  } else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/3.jpg)
