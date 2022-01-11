1. Using loops take 10 inputs from user and find the average of all the numbers.

```js


let sum=0
for(let i=0;i<10;i++){
   a =+prompt();
    sum =sum+a
}
    
 alert (sum/10);


 ```

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;

  //error println is not defined
}
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

```js

    function getEvenSum(max=10){
          let evenSum=0
          for(let i=0;i<=10;i++){
           
            if(i%2==0){
              evenSum =evenSum+i
            }
            
          }
return evenSum;
      }


```

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

```js

    function getOddSum(max=10){
          let oddSum=0
          for(let i=0;i<=10;i++){
           
            if(i%2==0){
              oddSum =oddSum+i
            }
            
          }
return oddSum;
      }


```

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.


- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

```js

    function getProductOfDigits(num){
          let productSum=1
        
         if( num>0){
            r= num%10;
             prouctSum =productSum*r;

         }
  return productSum;
      }


```
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

check(10); // output//  `Biggger than 5` because condition is num is greater than 5
check(1); // output // 'Smaller than 5'  because condition is num is smaller than 5
check(5); // output  // 5 because in the condition no where equal to use so 5 return as value.
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // what will be the output  // `You are arya`  because name ==="Arya"
getOutput('John'); // what will be the output// `You are john`    because name==="john"
getOutput(); // what will be the output// `Who are you`   because function not call with any argument so that return a `who are you`


```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // `Who are you`
getOutput('John'); // `Who are you`
getOutput(); // `Who are you`

because function always  give a return value output.
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
yes function   have multiple return statement.
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
for and while both a loop statement condition in the for loop we use the three condition first initilization , second loop end condition, third and last we use iteration.
in while loop first we give the condition in while loop then after the statement of while block

for(let i=0;i<=10;i++){
  console.log(i);
}

let i=0;
while(i<10){
  console.log(i);
  i++
}