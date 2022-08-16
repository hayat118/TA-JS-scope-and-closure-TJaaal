1. What does thread of execution means in JavaScript?

thread of execution means performing step wise action.

2. Where the JavaScript code gets executed?

Global Execution Context (GEC)  is the base/default Execution Context where all JavaScript code that is not inside of a function gets executed.



3. What does context means in Global Execution Context?


The global context is the fallback context in JavaScript. If you run a function and no context is setthen the fallback is the global context. 

4. When do you create a global execution context.

Whenever the JavaScript engine receives a script file



5. Execution context consists of what all things?

variable scope ,function arguments, and the value of the this object.

6. What are the different types of execution context?

There are two kinds of Execution Context in JavaScript: Global Execution Context (GEC) Function Execution Context (FEC).

7. When global and function execution context gets created?


The Global Execution Context gets created when we load the JavaScript file, even when it is empty. It creates two special things for us in its creation phase, that is the window object and this . In Global Execution context, the window object and this are equal.27

8. Function execution gets created during function execution or while declaring a function.

 Function execution gets created during function execution 


9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)