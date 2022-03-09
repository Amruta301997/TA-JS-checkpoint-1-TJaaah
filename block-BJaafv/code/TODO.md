1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
//return will return a value when the function is called.

// second
function sum(a, b) {
  console.log(a + b);
}
//console.log prints the output in the console.
```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
//first
function sum3(a=2, b=3) {
  return a + b;
}
undefined

//second
function sum3(a=2, b=3) {
  console.log(a + b);
}
6

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
the output is 36 because in function first we not assign third parameter hats why it does not take third value in addition.It only take first two values.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
If you want to display output on screen then function stored in another variable and then call it.
let add=sum(12,24);

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
 ```js
 function sayHello(name){
 return `hello ${name}`;
 }
let store=say('arya');
```

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
//output-'Hello, John'
variable defined outside can be defined/access inside. 


7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1 john

showMessage(); // Output 2 Hello John

alert(userName); // Output 3 john
```

8. What is a Anonymous Function give example of three functions.
Whenever you define function expression you avoid the function name.There is no name function.
1.const addNum=function(numA,numB){
  return numA+numB;
};
addNum(10,21);
2.const sayHello=function(name){
  returns `hello ${name};
};
sayHello(arya);
3.const calculate=fuction(a,b){
  return a*b;
};
calculate(12,23);


9. Can function declaration be a Anonymous Function? Explain
no,it can be removed in function expressions  to create anonymous functions.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"getFactorial" – return a value,
"calBookPages" – calculate something,
"createAddress" – create something,
"checkTrueOrFalse" – check something and return a boolean, etc.
```
