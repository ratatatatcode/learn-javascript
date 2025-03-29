**Different Typing Cases**<br>
```js
camelCase
PascalCase
snake_case
kebab-case
SCREAMING_SNAKE_CASE
Train-Case
iCount // Hungarian Notation
```

**Array**<br>
Linear data structure, collection of elements.
```js
const arr = [1, 2, 3, "Hi", "Hello"];
```

Similar to string, we can also access the array with its index,
```js
console.log(arr[0]); // 1
```

Printing all elements inside the 'arr' using a for loop,
```js
for (let i = 0; i < arr.length; i++) {
    console.log(arr[i]);
}

/* Output:
    1
    2
    3
    Hi
    Hello
*/
```

**Nested Array**
```js
const nested_array = [[1, 2, 3], [4, 5, 6]];
```

Accessing the nested array using 2 for loops, using row and col to make it easier to understand. this is how it looks so you can understand it better.<br>

row == 0 -> [1, 2, 3]<br>
row == 1 -> [4, 5, 6]<br><br>

This is an example of 2-dimensional array.
```js
for (let row = 0; row < 2; row++) {
    for (let col = 0; col < 3; col++) {
        console.log(nested_array[row][col]);
    }
}

/* Output:
    1
    2
    3
    4
    5
    6
*/
```

**Multi-Dimensional Arrays**
```js
const md_arr = [[1, 2, 3],
                [4, 5, 6],
                [[7, 8, 9], [10, 11, 12]]];
console.log(md_arr[2][1][0]); // 10
```

**Spread vs Rest Operator**<br>
Spread takes things out of an array or object,
```js
const normal_arr = [1, 2, 3];
const spread_arr = [...normal_arr, 4, 5, 6];
console.log(spread_arr); // [ 1, 2, 3, 4, 5, 6 ];
```
Rest puts multiple values into an array or object,
```js
function sum(...numbers) {
    // body
}
console.log(sum(1, 2, 3, 4, 5));
```