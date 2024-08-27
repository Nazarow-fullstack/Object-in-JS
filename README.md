# Object in JavaScript

+ In JavaScript, an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.

![](https://www.scientecheasy.com/wp-content/uploads/2022/03/javascript-object-example.png)

## method of object in JS
+ Objects in JavaScript are collections of key/value pairs. The values can consist of properties and methods, and may contain all other JavaScript data types, such as strings, numbers, and Booleans. All objects in JavaScript descend from the parent Object constructor. 

1. Object.entries()
+ The Object. entries() method returns an array of the key/value pairs of an object. The Object. entries() method does not change the original object.
```javascript
    let obj = { a: 1, b: 2, c: 3 };
    console.log(Object.entries(obj));
    // Output: [ [ 'a', 1 ], [ 'b', 2 ], [ 'c', 3 ] ]
```
2. Object.keys()
+ Object.keys() returns an array whose elements are strings corresponding to the enumerable string-keyed property names found directly upon object 
```javascript
    let obj = { a: 1, b: 2, c: 3 };
    console.log(Object.keys(obj));
    // Output: [ 'a', 'b', 'c' ]
```
3. Object.values()
+ Object.entries() returns an array whose elements are arrays corresponding to the enumerable string-keyed property key-value pairs found directly upon object 
```javascript
    let obj = { a: 1, b: 2, c: 3 };
    console.log(Object.values(obj));
    // Output: [ 1, 2, 3 ]
```


## What does destruturing mean in JavaScript?
+ Destructuring is a JavaScript expression that allows us to extract data from arrays, objects, and maps and set them into new, distinct variables. It is a convenient way to extract values from data stored in arrays or objects into distinct variables. Destructuring makes it easy to access the values of
+ objects and arrays without having to use their keys or indices. This can make your code more read
```javascript
let obje = {a: 1, b: 2, c: 3};
let obj2 = {...obj};
console.log(obj2) // {a: 1, b: 2, c: 3}
```

## What does spread mean in JavaScript?
+ The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments. It is commonly used in JavaScript to make code more readable and concise. The spread operator is denoted by three dots (...
+ The spread operator can be used to copy arrays and objects in JavaScript. When used with arrays,

```javascript
let obje = {a: 1, b: 2, c: 3}
let obj2 = {...obj, d: 4, e: 5}
console.log(obj2) // {a: 1, b: 2, c: 3, d: 4, e: 5}
```
