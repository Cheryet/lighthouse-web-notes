# Key things to know

## This file will be updated with topics that questions frequently include.

### Equality operators

In JavaScript, there are two sets of equality operators. The triple-equal operator === behaves like any traditional equality operator would: evaluates to true if the two expressions on either of its sides have the same type and the same value. The double-equal operator, however, tries to **coerce** the values before comparing them. It is therefore generally good practice to use the === rather than ==. The same holds true for !== vs !=.

### 6 JS data types
* Boolean
* Number
* String
* Null
* Undefined
* Symbol


### Loops

 Objects can only interate via for...in loops, in which the key will be returned

#### for...in loops

```js
const object = { a: 1, b: 2, c: 3 };

for (const property in object) {
  console.log(`${property}: ${object[property]}`);
}

// expected output:
// "a: 1"
// "b: 2"
// "c: 3"
```

#### for...of loops

```js
const array1 = ['a', 'b', 'c'];

for (const element of array1) {
  console.log(element);
}

// expected output: "a"
// expected output: "b"
// expected output: "c"
```

