**Comments**<br>
```js
// Comment (Ctrl + /)
```

```js
/*
    Multi-line comment (Shift + Alt + A)
*/
```

**Data Types**<br>
```js
number, bigint, boolean
string, object, symbol
undefined, null
```

**Examples**<br>
```js
str = "string"
num = 123
```

**Symbol**<br>
A Symbol in JavaScript is a unique and immutable primitive data type used as a key for object properties.

```js
let sym1 = Symbol("test");
let sym2 = Symbol("test");

console.log(sym1 == sym2); // false
```

**Variables**<br>
Variables (var), this is where we store and somehow manipulate data.
Similar to how x and y we use in mathematics.

```js
var myName = "James"; // or
myName = "Michael";
```

**Assigning the Value of One Variable to Another**<br>
```js
var a;
a = 1;
var b;
b = a;
console.log(b); // 1
```

**It's common to initialize value.**<br>
If we are going to create a sum and we won't be using it right away, we could initialize a value of zero (0) to it.

```js
var sum = 0;
```

We can use it to 'sum += num' and the 0 won't affect the result.

**We are different variable/function names**<br>
JavaScript is case sensitive, capitalization matters.

```js
var MYNAME;
var myName;
```

**Difference between var and let**<br>
'var' allows you to reuse the same variable name but with 'let', you can only use the variable name once.

```js
var num = 1;
var num = 2;

let num2 = 3;
let num2 = 3; // already been declared
```

**const**<br>
'const' is almost the same with 'let' but const is read-only. You can't change the value inside the const.

**Operators**<br>
```js
const sumOf = 1 + 2;
console.log(sumOf); // 3;

const differenceOf = 2 - 1;
console.log(differenceOf); // 1

const productOf = 1 * 2;
console.log(productOf); // 2

const quotientOf = 3 / 3;
console.log(quotientOf); // 1
```

**increment and decrement**<br>
```js
x++; // similar to 'x += 1;'
x--; // similar to 'x -= 1;'
```

**modulo**<br>
'modulo' returns the remainder from the division of two numbers.

```js
const modulo = 3 % 2;
console.log(modulo); // 1
```

It is commonly used to check whether a number is even or odd.

**escape literals**<br>
```js
const singleQuote = 'Yes, I am "James"';
const doubleQuotes = "Hi, I am \"James\"";
```

**string concatenation**<br>
```js
const firstStr = "First"
const secondStr = "Second"

const combinedStr = firstStr + " " + secondStr;

console.log(combinedStr); // Hello World

const str = "Hello " + "World";
console.log(str); // Hello World
```

**length of a string**<br>
console.log("Hello".length); // 5

**index of an array**<br>
index of an array always start with '0' and ends with '.length - 1'

```js
arr[0];
arr[arr.length - 1];
```

**strings are immutable**<br>
You can't just change the value of a string with accessing its index, instead you need to reassign new value to it.

```js
let color = "glue";
color[0] = "b"; // cannot assign to read only property
```

you can do this instead,
```js
color = "blue";
```
