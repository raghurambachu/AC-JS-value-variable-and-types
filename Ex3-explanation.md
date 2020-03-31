## Expression and Statement-readText (todo)

## Conditions-readText

Condition are used to perform different action based on different conditions. Like you want to `alert` only if the value if a even number.

To do this, we use the `if` statement or conditional operator `?` also known as ternary if.

## `if` statement

```
 if (condition) {
  statement 1
} else {
  statement 2
}

statement 3
```

- `if` statement evaluates a condition in the parentheses and
- if it results to `true` statement 1 is executed, then statement 3 is excuted (statement 2 doesnt excutes)
- if it results to `false` statement 1 is not executed rather statement 2 inside of else is evaluated, then statement 3 is executed

Example:

```js
var num = 33;
if (num % 2 === 0) {
  alert("Number is even");
} else {
  alert("Number is odd");
}
```

`if` statement evaluates a condition in the parentheses and if it results to `true` the block of code is executed. Or else the `else` block is executed.

If the value inside the parentheses is not resulting to `true` or `false` if converts the value into boolean. So if the value in parentheses is a truthy value `if` block is executes or `else` block is executed.

When we want to test multiple condition you can also chain several `else if` statement. Like

```js
let num = 20;
if (num === 21) {
  // you code
} else if (num === 22) {
  // your code
} else if (num === 23) {
  // your code
} else {
  // your code
}
```

## `?` ternary `if else`

`if` is a statement but `?` is an expression. `?` is also know as ternary if else. It is the only ternary operator in JS. It's called ternary because it acts on three operand. Like

```js
// syntax
let result = condition ? value1 : value2;
```

The condition is evaluated and the result is `truthy` value1 is returned or else value2 is returned. For example

```js
let isAdult = age > 18 ? true : false;
```

You can also use multiple `?` operator like this:

```js
let marks = 54;
let grade =
  marks < 40
    ? "Your grade is C"
    : marks < 60
    ? "Your Grade is B"
    : "Your grade is C";
```

## Loops-readText

Loops are used to repeat any action multiple times. Like say if you want to log all the even numbers form `1 - 10` . To do this we can do something like

```js
console.log(2);
console.log(4);
console.log(6);
console.log(8);
console.log(10);
```

The above code works but the idea of programming is to make things _easy_ not _hard._ Like say if we need list of all the numbers till `1000` this approach would become really hard. So we need a way to make way to run a piece of code multiple times. This is called loop.

Looping allows us to execute a block of code and go back to see if it meets the condition run the code again or not. If yes it will run the code again.

There are three type of loop

1. `while`
2. `do while`
3. `for`

- `while` loop

- Syntax

```
while (condition) {
  // code block to be executed
}
```

- Example

```js
let i = 1;
while (i < 10) {
  console.log(i);
  i = i + 1;
}
```

2. `do while` loop

- Syntax

do { // code block to be executed } while (condition);

exapmle - do { consoel.log(i) i = i+1; } while (i < 10);

3. for loop

Syntax

for (statement 1; statement 2; statement 3) { // code block to be executed } statement 1 :- the initial value where loop starts it is excuted only once at the begening of the loop statement 2 :- condition statement 3 :- is executed (every time) after the code block has been executed.

example for (i = 0; i < 5; i= i+1) { console.log(i); }

pointer :- 1)for and while loop are entry checking means if condition is wrong at the begening of loop it wont run But do while is exit checking means that it will at least run one time even if condition is wrong at the begening.

2. One of the common mistake made writing loop is we forget to increment the counter, so it becomes an infinite loop.(In all the above loop example you can see that variable on which condition is checked is updated inside that loop ) -->

```js
while (condition) {
  // "loop body"
}
// example
let num = 2;
while (num <= 10) {
  console.log(number);
  num = num + 2;
}
```

The above code can be simplified like this using loops.

A statement starting with `while` or `for`\* creates a loop. For `while` statement, after the keyword it accepts a expression in parentheses followed by a block of code. Every time the expression in parentheses results to `true` the block of code will be executed.

## `for` loop

```js
for (begin; condition; step) {
  // ... loop body ...
}
```
