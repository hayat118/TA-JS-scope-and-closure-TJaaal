1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percen = function(marks, total) {
  return (marks * 100) / total;
}
```


2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
let func = function(marks,total){
  return (marks * 100/ total)
}
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
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

Function Expression allows us to create an anonymous function which doesn't have any function name which is the main difference between Function Expression and Function Declaration.

4. Why is a function call an expression in JavaScript?

A function call expression is used to execute a specified function with the provided arguments

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer....valid
five = add; // Answer.....valid
five = five(10, 11); // Answer...valid
five = function () {
  return 'Hello';
}; // Answer...valid
```

6. What is the difference between function definition and function call? Explain with an example.

A function is procedure to achieve a particular result while function call is using this function to achive that task.

7. What is the similarities between function definition and function call?

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid....valid
```

9. What is higher order function explain with an example.

A “higher-order function” is a function that accepts functions as parameters and/or returns a function.


10. Explain what is callback function. Why you can pass a function inside a function?
A Callback is a function that is to be executed after another function has finished executing 
