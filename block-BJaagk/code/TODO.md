1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let result = (marks, total) => {
  return (marks * 100) / total;
}
let result = function(marks, total) [
  return (marks * 100) / total;
]

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
let result = (marks, total) => {
  return (marks * 100) / total;
}



```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

let result = (marks, total) => {
  return (marks * 100) / total;
}

```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

let percentage = (marks, total) => {
  return (marks * 100) / total;
}

```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

4. Why is a function call an expression in JavaScript?

Ans: A function call expression is used to execute a specified function with the provided arguments. If the function being called is overloaded, the compiler will attempt to match the argument types with the function parameter types. 

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer // 
 Ans:  5
five = add; // Answer
five = five(10, 11); // Answer
Ans: 21
five = function () {
  return 'Hello';
}; // Answer

invalid

```

6. What is the difference between function definition and function call? Explain with an example.

7. What is the similarities between function definition and function call?

Ans:  Unless a function is called there is no use of that function. ... So the difference between the function and function call is, A function is procedure to achieve a particular result while function call is using this function to achive that task.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid
```

9. What is higher order function explain with an example.

Ans:Higher-order functions are functions that take other functions as arguments or return functions as their results. ... sort, reduce, filter, forEach 

10. Explain what is callback function. Why you can pass a function inside a function?

Ans: Callbacks are generally used when the function needs to perform events before the callback is executed,

   
