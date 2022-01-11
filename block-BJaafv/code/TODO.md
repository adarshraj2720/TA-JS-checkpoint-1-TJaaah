1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
 ---  in this sum function when call that function it gives a value.   
// second
function sum(a, b) {
  console.log(a + b);
}

--- in this sum function when call that function that gives undefined.

```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

````js
 output- 36   ,here pass one more parameter no matter you pass more parameter.


```

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

= yes i  can store a first function in add  variable name as like as function function expression.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
  

  ```js
      
      function sayHello(name){
        return `Hello ${name}`
      }

        sayHello(`Arya`);
  ```

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();

//output- `Hello, John`
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1 //`john`

showMessage(); // Output 2 `Hello,John`

alert(userName); // Output 3 `John`
```

8. What is a Anonymous Function give example of three functions.


=Anonymous Function is Function that can store in a variable  and there is no name to this function so this type of function expression is called Anonymous function expression.

let sum = function(first,second){
  return first+second;
}


let username = function(name){
  return name;
}
9. Can function declaration be a Anonymous Function? Explain

= No function declaration be a Anonymous Function because in the function declaration function has a function name and in the function Anonymous we can store a function in the variable name and there has no name of  function.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.


//calcTwoNumber
//getDetails
//createInfo
//getNumber
//checkGreaterOrLesser
```
