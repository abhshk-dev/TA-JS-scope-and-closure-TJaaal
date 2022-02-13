1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let percent= function percentage(marks,total){
  return (marks*100)/total;
}

let percent= function(marks,total){
  return (marks*100)/total;
}
let perc= (marks,total)=>{
  return (marks*100)/total;
}

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
//

```
Function declaration.
```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

```

Function expression.
```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
Function expression
```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
 Function expression
```js
let percentage = (marks, total) => (marks * 100) / total;
```
Function expression.

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

4. Why is a function call an expression in JavaScript?

----> function call is an expression because it evaluates to a value.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer VALID , it calls the function add with parameters.
five = add; // Answer VALID it gives the reference.
five = five(10, 11); // Answer  VALID returns 21 as output.
five = function () {
  return 'Hello';
}; // Answer VALID function expression.
```

6. What is the difference between function definition and function call? Explain with an example.

----> Function definition is defining a set of statements which takes some input and carries out operation on the inputs to achieve desired outputs. A function call is calling the defined function with the set of inputs to get the desired outputs.
for example:--> 
```js
//function definiton
function multiply(a,b){
  return a*b;
}
//function call
multiply(3,4);
```

7. What is the similarities between function definition and function call?
-----> Both can be treated as  expression.
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid 
```

9. What is higher order function explain with an example.

----> A funciton that accepts another function definition as a parameter or returns a function definition is a HOF.

10. Explain what is callback function. Why you can pass a function inside a function?

----> A function that is being passed to another function is called a callback function.