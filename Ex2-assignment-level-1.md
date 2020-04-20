## writeCode

Define 5 values of types number and string and store it in a variable.

## writeCode

- Declare a variable `user` and take the name using `prompt`. Display the value stored in `user` using `alert`.
- Now re-assign the value stored in the above example into a new variable `userName`. Log the value of both `user` and `userName` in console using `console.log`.
- Declare `age` and `gender` in the same line as `userName` i.e. declare multiple variables in one line.
- Now change the value of `user` to "John" and log the value of both `user` and `userName`.

let user = prompt("Enter your Name !!");
alert(user);

let age, gender, userName = user;
console.log(user);
console.log(userName);

user = "John";
console.log(user);
console.log(userName);

## writeCode

Use `prompt` to take two numbers from user and store it in variable `numA` and `numB`. Create a third variable called `sum`, using `+` operator add numA and numB , store it in varible `sum` and using alert display `sum` in browser.

let numA = +prompt("Enter Number 1", "");
let numB = +prompt("Enter Number 2, "");
let sum = numA + numB;
alert(sum);

## writeCode

Define 10 variables and store any kind of value in it. Like name, age etc

let firstName = "Raghuram";
let lastName = "Bachu";
let age = "26";
let degree = "BE";
let location = "Navi Mumbai";
let landmark = "GrandCentral Mall";
let fav = "nothing";
let hobbies = "everything";
let phone = 98698885757;
let school = "closed";

## writeTextAnswer

- Declare variables with the name `break`, `class`, `const`, `for`, `else`, `if`, `import` and `return`. Explain in your own words what did you observe.
The above mentioned words are reserved keywords and trying to declare variables with this name will lead to error. Like for instance if we try to declare 

let break ; 
We will get the error unexpected token : break
"Uncaught SyntaxError: Unexpected token 'break'"

## writeTextAnswer

- What is a truthy and falsey values.
Anything that is not a falsey value is a truthy value.

## writeTextAnswer

- What are falsey values?
Falsey values are one which in boolean context evaluate to false value. For instance we have null, undefined, 0, false  and empty string("") which evaluate out to falsey values in case of boolean context. For instance
if(0) {
  console.log("This block will not execute as 0 within if evaluates to false.")
} else if(1){
  console.log("This block will execute as 1 within if evaluates to true as it is truthy value.")
}

## writeCode

- Declare three variables `name,` `newUser` and `isAdmin`.
  - Assign your name as the value of `name`.
  - Reassign the value `newUser` to `name`.
  - Set the value of `isAdmin` to `true`.
  - Prompt the values of all the three variables.
  //FEEDBACK : I think it should be alert the values rather than prompt the values.

  let name, newUser, isAdmin;
  name  = "Raghuram";
  newUser = name;
  isAdmin = true;
  alert(name);
  alert(newUser);
  alert(isAdmin);


## writeTextAnswer

What is the error in the given variable declaration:

```js
let user name = "John";
//There should be a space in variable declaration. No special character is allowed in declaring the identifier/variable.
//Exception only $ and underscore could be used.
let userName = "John" //is the right way
```

## writeQuiz

Q. What does the 'mkdir' command do?

- [x] "Welcome to JavaScript"
- [ ] 'Welcome to JavaScript"
- [ ] "Welcome to JavaScript'
- [ ] 'Welcome to JavaScript'

//FEEDBACK: The options mentioned above seem to be out of context to the questions asked.

## writeTextAnswer

Find out the `valid` and `invalid` variables. In case of `invalid` declarations give reasons. Just below every line.

- let monk; 
//Valid

- let 1stName;
//Invalid : In this case variable name starts with number, an identifier should either start with letters or $ or _. Though thereafter the identifier can contain a number

- let places3;
//Valid

- let -name;
//Invalid : "-" special character cannot be used to declare a variable. 

- let bigPanther;
//Valid

- let 35;
// Invalid : Identifier name cannot start with a number.

- let 43 = 30;
// Invalid : Identifier name cannot start with a number.

- let \$48;
// Invalid : Variable cannot start with special character except $ or _.

- var \*gt = 350;
// Invalid : Variable cannot start with special character except $ or _.

- let userName;
//Valid

- let a, b, c;
//Valid

- let x = 3, y = 11, z = 13;
//Valid

- let x = 2 + 5 + 7;
//Valid

- let user = "Brienne of Tarth"; "Sansa Stark"; "Lyanna Mormont";
//Valid declaration but the user will be assigned value of "Brienne of Tarth"

## writeCode

Follow instructions and write code. In case of an error write the error in your own words.

```js
var wiseMan = "Tyrion Lannister";
```

- Reassign the value of `wiseMan` to "Samwell Tarly"
- Declare a variable `userName` with value "Lysa Arryn"
- Declare a variable as `oddNumber` and assign a value `57`.
- Reassign the value of `oddNumber` to 61

wiseMan = "Samwell Tarly";
let userName = "Lysa Arryn";
let oddNumber = 57;
oddNumber = 61;

## writeCode

Using mathematical operations find the solutions. `(+, -, \*, / , etc.)`

```js
let amount = 4280;
```

- Declare a new variable `reducedAmount` . In it store the value that is 24 less than the value of amount.
- Declare another variable `addedAmount` . Its value should be 32 more than the value of amount.
- Declare a variable `multipleAmount` . Its value should be 7 times the value of amount.
- Declare a variable `dividedAmount` . It should store the resultant of amount divided by 57.

let reducedAmount = amount - 24;
let addedAmount = amount + 32;
let multipleAmount = amount * 7;
let dividedAmount = amount / 57;

## typeof-writeCode

What will be the output of the following

1. `typeof NaN`   
//"number"

2. `typeof phone`
//"undefined"

3. `typeof null`
//"object"

4. `typeof undefined`
//"undefined"

5. `typeof "abc"`
//"string"

6. `typeof -0`
//"number"

7. `typeof 4`
//"number"

## Number Type Conversion-writeCode

Output of the following code

1. `Number("6")`
// 6

2. `Number("6.76")`
// 6.76

3. `Number(" 6.76 ")`
// 6.76

4. `Number(" 6 . 7 6 ")`
// NaN

5. `Number(" ")`
// 0

6. `Number("")`
// 0

7. `Number("5+6")`
// NaN

8. `Number(true)`
// 1

9. `Number(false)`
// 0

10. `Number("text")`
// NaN

## String Type Conversion-writeCode

Output of the following code

1. `String(456)`
// "456"

2. `String(1.25)`
// "1.25"

3. `String(10+20)`
// "30"

4. `String(true)`
// "true"

5. `String(false)`
// "false"

6. `String(NaN)`
// "NaN"

7. `String("text")`
// "text"

8. `String("This", "is", "text")`
// "This"

9. `String["This", "is", "text"]`
//  undefined[Why no error and why we are getting undefined]

10. `String{"This", "is", "text"}`
//  Unexpected token error : {

11. `String("This"+"is"+"text")`
//  "Thisistext"

## Boolean Type Conversion-writeCode

Output of the following code

1. `Boolean(1)`
// true

2. `Boolean(0)`
// false 

3. `Boolean(-5)`
// true

4. `Boolean(5-5)`
// false

5. `Boolean(undefined)`
// false

6. `Boolean(null)`
// false

7. `Boolean(NaN)`
// false

8. `Boolean("text")`
// true

9. `Boolean(" ")`
// true

10. `Boolean("")`
// false

## Operators-writeCode

Output of the following line of code.

```js
20 > 5 && 5 < 20; //output: true
20 > 5 && 20 < 5; //output: false
NaN && NaN; //output: NaN
NaN && undefined; //output: NaN
undefined && " "; //output: undefined
"" && "Arya"; //output: false
"Arya" && 5; //output: 5
10 && "Arya"; //output: "Arya"
" " && 10; //output: 10
NaN && undefined; //output: NaN
" " || 10; //output: " "
undefined || " "; //output: " "
10 || "Arya"; //output: 10
"" || "Arya"; //output: "Arya"
!undefined; //output: true
!null; //output: true
!20; //output: false
!0; //output: true
!NaN; //output: true
```

## writeQuiz

What is the value of x?

```js
var a = 5,
  b = 10,
  c = "5";
var x = a + "5";
```

- [ ] 5
- [ ] 10
- [ ] 15
- [x] 55

## Condition-writeCode

Write a program that asks the user his/her age and check for the following conditions :

- `if` the age is between 12-55 then print the message "You can participate in the marathon".
- `if` the age is between 4-11 then print the message " You are too young to participate in the marathon".
- `if` the age is less than 4 then print the message " Hey Kiddo! Can You Walk ?"
- `if` the age is greater than 55 then print the message " You are too old to participate in the marthon".

let age = +prompt("Hey there, Please enter your age! ","");

if(age < 4) {
  console.log("Hey Kiddo! Can You Walk ? ");
} else if (age >= 4 && age <= 11) {
  console.log("You are too young to participate in the marathon.")
} else if (age >= 12 && age <= 55) {
  console.log("You can participate in the marathon.");
} else if (age > 55) {
  console.log("You are too old to particpate in the marathon.");
}

## writeCode

Write a program that asks the user for the house name and check the following conditions :

- `if` house name is "stark" then print the message " Winter is coming"
- `if` house name is "lannister" then print the message " A lannister always pays his debt"
- `else` print the message " All men must die"

let houseName = prompt("Please enter the house name","");
if(houseName === "stark") {
  console.log("Winter is coming.");
} else if(houseName === "lannister") {
  console.log("A lannister always pays his debt.");
} else {
  console.log("All men must die.");
}

## writeCode

Write a program that asks the user for a number and check the following conditions :

- `if` the number is even print the message " number is even"
- `if` the number is odd print the message "number is odd"

let inputNum = +prompt("Please enter a number","");
if(inputNum % 2 === 0) {
  console.log("number is even.");
} else {
  console.log("number is odd.");
}

### Convert the above code using `?` terniary operator

## writeCode

1. Print the odd numbers from 9 through 1(both inclusive) using a for loop. There is no input involved.
2. Add numbers from 5 through 0(both inclusive) in descending order using a while loop. There is no input involved.
3. Program to calculate the sum of first n natural numbers(1,2,3...n are known as natural numbers). Prompt user to enter n(using prompt modal window) then based on input provided calculate and show result in alert modal window.
4. Write a program to print from 1 to 10 but quit if multiple of 7 is encountered. There is no input involved.

for(let i = 9; i >= 1; i--) {
  if(i % 2 !== 0) {
    console.log(i);
  }
}

let num = 5;
let sum = 0;
while(num >= 0){
  sum += num;
  num--;
}

let n = +prompt("Enter a number! We will calculate the sum till the number starting from 1","");
let sumOfN = 0;
for(let i = 0; i <= n; i++){
  sumOfN += i;
}
alert(sumOfN);


for(let i = 1; i <= 10; i++) {
  if(i === 7){
    break;
  }
  console.log(i);
}

## writeCode

Complete the following code to make the output be 0 2 4 6 8 10?

```js
for (let j = 0; j <= 10; j += 2 ) console.log(j);
```
