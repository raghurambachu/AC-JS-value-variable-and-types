## writeCode

```js
var a = 5,
  b = 10;
```

For the above code write the output next to code?

```js
a != b && a < b; //output true
a > b || a == b; //output false
a < b || a == b; //output true
!(a < b); //output  false
!(a > b); //output  true
!!a; //output true
!!(a > b); //output false
```

## writeCode

After the following code runs, what is the value of `isWeekend`?reason?

```js
var isSaturday = true;
var isSunday = false;
var isWeekend = isSaturday && isSunday; // output false
var isWeekend = isSaturday || isSunday; // output true
```

## writeCode

Print following pattern using nested loop using console.log. Take input from prompt and print results using console.log. For clarification check sample output below.

```
  For n = 4,
  output in console should look like.
  1
  2 3
  4 5 6
  7 8 9 10

let n = 4
let k = 1;
for(let i = 0; i < n; i++){
  let pattern = "";
  for(let j = 0; j <= i; j++){
    pattern += k++ + " "
  }
  console.log(pattern);
}
```
