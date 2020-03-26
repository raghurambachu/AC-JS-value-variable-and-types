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

## writeTextAnswer

What are the different types of type conversions. Explain in your own words with few examples.

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

Similarly write explaining how this conversion will happen. And what will be the output.

1. `3 * "3"`

2. `1 + "2" + 1`

## writeCode

What's the output of the following, write the output next to the code as comment

1. 5 \* "5" = ?
2. 6 + "7" = ?
3. 1 + "JS" = ?
4. 1 \* "JS" = ?
5. 5 + true = ?
6. 6 - true = ?
7. 7 - false = ?
8. 8 + false = ?
9. true + true = ?
10. true + false = ?

## writeCode

Output of each line of code :

- `3 * '8'`
- 1 + '21' + 32
- "string" ? 4 : 1
- undefined ? 4 : 1
- 4 \* Number("")
- 4 \* 0
- 4 / '2'
- 4 + true
- 3 \* false
- 3 \* ""
- 3 + ""

## Operators-writeCode

Output of the following line of code.

```js
"NaN" && "undefined" && 0; // output
"AT" && "" && false; // output
"AT" && " " && false; // output
"AT" || 5; // output
" " || "AT" || false; // output
!{}; //output
!""; //output
!"OK"; //output
!false; //output
!true; //output
```

## == and === writeTextAnswer

What is the difference between double equal and tripal equal comparision operator. Explain with example.

## Double and Tripal equal-writeCode

```js
var a = 5,
  b = 10,
  c = "5";
var x = a;
```

What will be the output of the code below on the basis of above code.

```js
a == c; // output
a === c; // output
a == x; // output
a != b; // output
a > b; // output
a < b; // output
a >= b; // output
a <= b; // output
a >= c; // output
a <= c; // output
```

```js
var a = 5,
  b = 10;
```

What will be the output of the code below on the basis of above code.

```js
a != b && a < b; //output
a > b || a == b; //output
a < b || a == b; //output
!(a < b); //output
!(a > b); //output
```

## writeTextAnswer

What is the difference between `if` statement and ternary operator. Explain with example.

## writeCode

Take two value using prompt and store them in variables `num1` and `num2`. Check whether they are equal or not.

- if the input value is anything like `true`, `null` or `undefined` alert saying `Enter a valid value`.

Example:

```js
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
```

## writeTextAnswer

```js
true == 0; // output
true == 1; // output
true == 2; // output
true == 3; // output
true == 100; // output
true == 1000; // output
```
