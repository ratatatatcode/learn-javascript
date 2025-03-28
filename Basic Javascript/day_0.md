**Comments**
// Comment (Ctrl + /)

/*
    Multi-line comment (Shift + Alt + A)
*/

**Data Types**
number, bigint, boolean
string, object, symbol
undefined, null

**Examples**
str = "string"
num = 123

**Symbol**
A Symbol in JavaScript is a unique and immutable primitive data type used as a key for object properties.

let sym1 = Symbol("test");
let sym2 = Symbol("test");
console.log(sym1 == sym2); // false

**Variables**
Variables (var), this is where we store and somehow manipulate data.
Similar to how x and y we use in mathematics.

var myName = "James"; // or
myName = "Michael";

**Assigning the Value of One Variable to Another**
var a;
a = 1;
var b;
b = a;
console.log(b); // 1

**It's common to initialize value.**
If we are going to create a sum and we won't be using it right away, we could initialize a value of zero (0) to it.
var sum = 0;

We can use it to 'sum += num' and the 0 won't affect the result.

**We are different variable/function names**
JavaScript is case sensitive, capitalization matters.

var MYNAME;
var myName;

**Difference between var and let**
'var' allows you to reuse the same variable name but with 'let', you can only use the variable name once.

var num = 1;
var num = 2;

let num2 = 3;
let num2 = 3; // already been declared

**const**
'const' is almost the same with 'let' but const is read-only. You can't change the value inside the const.

**Operators**
const sumOf = 1 + 2;
console.log(sumOf); // 3;

const differenceOf = 2 - 1;
console.log(differenceOf); // 1

const productOf = 1 * 2;
console.log(productOf); // 2

const quotientOf = 3 / 3;
console.log(quotientOf); // 1

**increment and decrement**
x++; // similar to 'x += 1;'
x--; // similar to 'x -= 1;'

**modulo**
'modulo' returns the remainder from the division of two numbers.

const modulo = 3 % 2;
console.log(modulo); // 1

It is commonly used to check whether a number is even or odd.

**escape literals**
const singleQuote = 'Yes, I am "James"';
const doubleQuotes = "Hi, I am \"James\"";

**string concatenation**
const firstStr = "First"
const secondStr = "Second"

const combinedStr = firstStr + " " + secondStr;

console.log(combinedStr); // Hello World

const str = "Hello " + "World";
console.log(str); // Hello World

**length of a string**
console.log("Hello".length); // 5

**index of an array**
index of an array always start with '0' and ends with '.length - 1'
arr[0];
arr[arr.length - 1];

**strings are immutable**
You can't just change the value of a string with accessing its index, instead you need to reassign new value to it.

let color = "glue";
color[0] = "b"; // cannot assign to read only property

you can do this instead,
color = "blue";