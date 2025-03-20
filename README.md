# javaScript_course

# JavaScript Basics

## 1. var, let, and const

```js
function fun(){
    var a = 5; // redeclarable and function-scoped
    if (a == 5) {
        let b = 10; // block-scoped
        const c = 20; // block-scoped, not reassignable
        console.log(a);
        console.log(b);
        console.log(c);
    }
    console.log(a);
    console.log(b);
    console.log(c);
}
fun();
```

## 2. == vs ===

```js
let a = 5;
let b = '5';
console.log(a == b); // true
console.log(a === b); // false
```

## 3. Arrays in JavaScript

```js
a = 4;
b = 5;
c = 'Hello';
const arr = [a, b, c];
console.log(arr);
