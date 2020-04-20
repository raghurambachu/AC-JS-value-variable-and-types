## Operators-readText

In JavaScript Operator a are used for operation like assignment, comparing, arithmetic, logical etc. JavaScript supports both _unary_ and _binary_ operators.

**Unary** operators act on one operand where ad **Binary** acts on two operand(value).

Operand is what operators are applied to for Example `5 + 6` has two operands 5 and 6.

```js
-5; // unary operator
5 * 6; // binary operator * acting on 5 and 6
var x = 10;
x = -x; // unary

var x = 10,
  y = 20;
var z = x + y; // binary
```

### `+` operator

The `+` operator exists in two forms _unary_ and _binary._ It can be applied to one or two operand.

When applied to one operand it converts the operand into a number.

```js
  +5; // nothing happens because operand 5 is a number data type
  +"21; // 21 (converted string to number)
  +true; // 1 (converted boolean to number)
  +""; // 0 (converted string to number)
```

When applied on two operand it does one of the following:

- If both operands are `number` data type. It will add both number and return the final number.
- If any of the operand is a `string` it concatenate the operand and return string.

```js
21 + 23; // 44 (sum of numbers)
"hello" + "world"; // hello world (concatenate)
"21" + 23; // '2123' (concatenate)
21 + "hello"; // '21hello'
```

Above in the example `"21" + 23` first operand is `"21"` (string data type) and another operand is a number (`23`). So the second rule applies here if any of the operand is a string than both the operands are concatenated converting the number (`23`) into sting with implicit type conversion.


### `=` Assignment Operator

To learn about more operator:

[Expressions and operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
