## Example readCode

```js
let age = 21;
if (age > 18) {
  alert("You are an adult.");
}
```

```js
let age = 21;
age > 18 && alert("You are an adult.");
```

- Above two code examples are equivalent. You can use `&&` on the place of `if` statement.
- `&&` looks for first `falsey` value so `alert` will only execute if the fist expression is a truthy statement.

## writeCode

Logical operations with variables. Solve the following examples using logical operations. `(<, >, &&, ||)`.

```js
var vegetablesPrice = 54;
var cerealsPrice = 149;
```

- Find which one is costlier?
- Which item is cheaper?
- Check if the prices of both the items are equal.
- Define a new variable. Assign the price of vegetables to it.
- Calculate the average price of these two commodities.
if(vegetablesPrice > cerealsPrice) {
  console.log("Vegetables is costlier");
} else {
  console.log("Cereals is costlier");
}


if(vegetablesPrice < cerealsPrice) {
  console.log("Vegetables is cheaper");
} else {
  console.log("Cereals is cheaper);
}

if(vegetablesPrice === cerealsPrice){
  console.log("Prices of both items are equal");
}

## writeTextAnswer

What are the different types of type conversions. Explain in your own words with few examples.
//There are two types of type conversions. 
1. Implicit type conversion - Automatically performed by javascript engine. For instance if we have "53" + 63 , the output of this will be 5363 and not 116. as whenever binary + operator is used javascript engine checks for a string and if atleast one of the operands is string and other is number, the operand with type of number will automatically be converted into string and thus leading to subsequent concatenation.

2. Explicit type conversion : This is explicitly performed by the user like sometimes we receive input in the form of string, like say "73" but we need to add with some other number, then we need to ensure that "73" is converted to number type and this can be done by Number("73") which will convert into number 73;


## writeQuiz

Q. What will be the output of the following code.

```js
var num = 1011;
if (num === 1011) {
  var num = 205;
  console.log(num);
}
```

- [ ] 1011
- [ ] 1000
- [ ] `error`
- [x] 205

## writeTextAnswer

`3 + '4'` in this code first value `3` is a Number data type and `'4'` is a String. Because both values are not same `implicit type conversion` will happen to bring both the value in the same data type. So `string` will be converted to `number` because of preference of number. `Number('4')` is equal to `4`. Now `3` and `4` is number and result is `7`.
//FEEDBACK: I am not able to understand, like how string is converted to number because in case of binary addition of string and number there would be string concatenation.

Similarly write explaining how this conversion will happen. And what will be the output.

1. `3 * "3"` // 9 
// mathematical operators like -, *, / ensure the string to be converted to number. So 3 * 3 = 9

2. `1 + "2" + 1`
// Initially 1 + "2" will lead to concatenation ie they will output "12" + 1, will finally lead to "121"

## writeCode

What's the output of the following, write the output next to the code as comment

1. 5 \* "5" = ?// Invalid token like two operators being used and violate the binary operator principle where operator needs to be surrounded by two operands.

2. 6 + "7" = ?// "67"

3. 1 + "JS" = ?// "1JS"

4. 1 \* "JS" = ?// Invalid token like two operators being used and violate the binary operator principle where operator needs to be surrounded by two operands.

5. 5 + true = ?// 6

6. 6 - true = ?// 5

7. 7 - false = ?// 7

8. 8 + false = ?// 8

9. true + true = ?// 2

10. true + false = ?// 1

## writeCode

Output of each line of code :

- `3 * '8'` // 24
- 1 + '21' + 32 // "12132"
- "string" ? 4 : 1  // 4
- undefined ? 4 : 1 // 1
- 4 \* Number("") //  error
- 4 \* 0  // error
- 4 / '2' // 2
- 4 + true  // 5
- 3 \* false  // error
- 3 \* "" //  error
- 3 + ""  // "3"

## Operators-writeCode

Output of the following line of code.

```js
"NaN" && "undefined" && 0; // output 0
"AT" && "" && false; // output ""
"AT" && " " && false; // output false
"AT" || 5; // output  "AT"
" " || "AT" || false; // output " "
!{}; //output //doubt
!""; //output true
!"OK"; //output false
!false; //output  true
!true; //output false
```

## == and === writeTextAnswer

What is the difference between double equal and tripal equal comparision operator. Explain with example.
Triple equals is strict equality comparision. Whereas double equals allows for two different data types to be compared. In case if there is type mismatch between the operands being compared the == operator does the implicit type conversion. For example if we 
take

53 == "53", here "53" is converted to a number type and then comparision is performed leading to equality that is output is true;
but when we use triple equality that is 53 === "53", there is no implicit type conversion leading to output as false.

## Double and Tripal equal-writeCode

```js
var a = 5,
  b = 10,
  c = "5";
var x = a;
```

What will be the output of the code below on the basis of above code.

```js
a == c; // output true
a === c; // output  false
a == x; // output true
a != b; // output true
a > b; // output false
a < b; // output  true
a >= b; // output false
a <= b; // output true
a >= c; // output true
a <= c; // output true
```

```js
var a = 5,
  b = 10;
```

What will be the output of the code below on the basis of above code.

```js
a != b && a < b; //output true
a > b || a == b; //output false
a < b || a == b; //output true
!(a < b); //output  false
!(a > b); //output  true
```

## writeTextAnswer

What is the difference between `if` statement and ternary operator. Explain with example.
Ternary operator is one which as three operands and it is condensed form of if else statement.

## writeCode

Take two value using prompt and store them in variables `num1` and `num2`. Check whether they are equal or not.

- if the input value is anything like `true`, `null` or `undefined` alert saying `Enter a valid value`.

Example:

```js
let num1 = prompt("Enter Number 1");
let num2 = prompt("Enter Number 2");
if( (num1 === true || num1 === undefined || num1 === null) || (num2 === true || num2 === undefined || num2 === null) ) {
  alert("Enter a valid Value");
} else {
  if(+num1 === +num2) {
    console.log("Both are Equal");
  } else {
    console.log("Numbers inputted are not equal")
  }
}


21, 21; // true
21, "21"; // true
"21", "21"; // true
"hello", -21; // false
```

## writeCode

Given a positive integer `n`. Print one word in format of heeeello(letter 'e' must be repeated `n` times). Take input from prompt and print the result in alert.

Example:

```
for n = 1
result should be hello.
for n = 7,
result should be heeeeeeello (e repeated 7 times).

let n = +prompt("Enter the number of times you want to repeat e's in hello");
let es = "";

for(let i = 1; i <= n; i++) {
  es += "e";
}

console.log("h" + es + "llo");
```

## writeTextAnswer

```js
true == 0; // output  true
true == 1; // output  true
true == 2; // output  false
true == 3; // output  false
true == 100; // output  false
true == 1000; // output false
```
