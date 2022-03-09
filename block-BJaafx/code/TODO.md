1. Using loops take 10 inputs from user and find the average of all the numbers.

let total;
 let grades = [90, 30, 40, 50, 60,23,45,56,34,12]; 

 for (let i = 0; i < grades.length; i++) {  
         total += grades[i]; 
             }           
      let avg = total / grades.length;      
      console.log(avg)


2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
//output 2
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

function getEvenSum(max=10){
  for(let i=1;i<=10;i++) {
    if(i%2==0) {
     let sum=sum+i. }
}
let sumOfEven=getEvenSum();
console.log(sumOfEven);


4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

function getOddSum(max=10){
  for(let i=1;i<=10;i++) {
    if(i%2!==0) {
     let sum=sum+i. }
}
let sumOfOdd=getOddSum();
console.log(sumOfOdd);

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // output Bigger than 5
check(1); // output Smaller than 5
check(5); // output 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you?';
}

getOutput('Arya'); // You are arya 
getOutput('John'); //You are john
getOutput(); // Who are you?
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you?';
}

getOutput('Arya'); // You are arya  Who are you?
getOutput('John'); // You are john   Who are you?
getOutput(); //Who are you?
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
Answer-YES
example-
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}
we use multiple return statement but execute only one return statement.


10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
for loop- for loop going through a block of code until the counter reaches a specified number.
example-for(let i=0;i<=10;i++){
  alert(i);
}

while loop-while takes the condition if it is true then go to the body(code of execution) otherwise condition false,loop ends.
let num=0;
while(num<5{
alert(i);
})
