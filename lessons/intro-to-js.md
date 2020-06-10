---
path: "/intro-to-js"
title: "Modern Javascript"
order: 1
---

Lets get started with understading modern JS concepts. Aim of this module to provide basic understanding of new ES6 concepts which are frequently used across React. So when you come across any new ES6 syntax you will have some idea about those concepts.

## Understanding "let" and "const"

Generally we use `var` keyword to define variables in javascript. But with ES6 they have introduced two new keywords `let` and `const`.

In many ways `let` is like a cousin of `var`. It has a lot of similarities but differentiates in ways that makes ES6 a more modern-feeling language. Using `let` you can reassign variables, but its syntax is more strict than `var`.

```js
let myName = "Ujval";
console.log(myName);

myName = "Joshi";
console.log(myName);
```

The keyword `const` is an abbreviation for `constant`. Similar to `let`, it’s block-scoped, however, you can’t reassigned it.

```js
const myName = "Ujval";
console.log(myName);

myName = "Joshi"; // It will throw error
```

| Keyword | Function vs Block-scope | Redefinable |
| ------- | ----------------------- | ----------- |
| var     | function-scop           | ✅          |
| let     | block-scope             | ✅          |
| const   | block-scope             | 🚫          |

<br >

## Arrow Functions

New with JavaScript since ES6, arrow functions, also known as fat arrow functions, are a concise way to write function expressions.

### Normal Function

```js
function multiplyBy2(num) {
  return num * 2;
}
multiplyBy2(5);
```

---

### Arrow Function

```js
const multiplyBy2 = num => num * 2;
multiplyBy2(5);
```

In regular functions the `this` keyword represented the object that called the function, which could be the window, the document, a button or whatever.

With arrow functions the `this` keyword always represents the object that defined the arrow function.

## Exports & Imports

With ES6, with get built-in support for modules in JavaScript. Like with CommonJS, each file is its own module. To make objects, functions, classes or variables available to the outside world it’s as simple as exporting them and then importing them where needed in other files.

## Classes

## Spread Operator

## Destructuring
