## Variable (Storing a value)-readText

In the above module we learned about value (information) and different value types like `number` , `string` , `boolean` etc.

Variable is a named storage that is used to store any value. You can imagine a variable to be like a box with name that is used to store number, boolean, string, null, undefined, object, BigInt and Symbol.

Example:

```js
var username = "Arya";
```

In the above code we are using multiple things let's understand all of those.

- `var` Keyword to create a new box.

- `username` To name a box.

- `=` assignment operator assign a value `"Arya"` to the box named `username`

![Store of value](./assets/variable-box.png)

![variable](assets/variable-var.png)

**On the right hand side of `=` can only be a value.**

You can also change the value of a variable using `=` (assignment operator) like below

```js
var username = "Arya";
username = "John";
```

The value of the `"Arya"` will be replaced with `"John"` this is called re-assignment.

![Re-assignment](assets/re-assignment.png)

variable can only hold one value at a time.

There are multiple ways of creating a box in JavaScript i.e `var` , `let`, `const`

```js
var username = "Arya";
let house = "Stark";
const brother = "John";
```

You can create boxes using multiple ways but all the boxes behaves differently.

### `var`

### `let`

### `const`

Box created with const keyword can't be re-assigned to another value.
