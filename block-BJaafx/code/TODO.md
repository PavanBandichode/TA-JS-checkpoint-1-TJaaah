1. Using loops take 10 inputs from user and find the average of all the numbers.
num1=+promt("enter number1");
num2=+promt("enter number2");
num3=+promt("enter number3");
num4=+promt("enter number4");
num5=+promt("enter number5");
num6=+promt("enter number6");
num7=+promt("enter number7");
num8=+promt("enter number8");
num9=+promt("enter number90");
num10=+promt("enter numbe10");
sum=num1+num2+num3+num4+num5+num6+num7+num8+num9+num10;
alert(`sum of all 10 numbers is ${sum}`);
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```
//VM61:3 Uncaught ReferenceError: println is not defined

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
function getEvensum(max=10){
  for(let i==1;i<=max;i++)
  {
    if(i%2==0)
    sum= sum+i;
  }
  alert(`sum = ${sum}`);
}
4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
function getEvensum(max=10){
  for(let i==1;i<=max;i++)
  {
    if(i%2!==0)
    sum= sum+i;
  }
  alert(`sum = ${sum}`);
}

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.
function getSum(n)
{

    let product = 1;
 
    while (n != 0)
    {
        product = product * (n % 10);
    }
    return product;

}
 
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

check(10); //'Bigger than 5'
check(1); // 'Bigger than 5'
check(5); // 'Bigger than 5'
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); //'You are arya'
getOutput('John'); // 'You are john'
getOutput(); // 'Who are you'
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output
getOutput('John'); // what will be the output
getOutput(); // what will be the output
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
