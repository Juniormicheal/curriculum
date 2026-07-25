---
author: nene
levels:
  - basic
  - advanced
  - medium
type: normal
category: feature
links:
  - '[ES6 Symbols Guide](https://javascript.info/symbol){website}'
  - >-
    [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol){website}
practiceQuestion:
  formats:
    - fill-in-the-gap
  context: relative
revisionQuestion:
  formats:
    - fill-in-the-gap
  context: relative
---

# Symbols in ES6


---

## Content

ES6 has a new primitive type called `Symbol`. A symbol is used as a unique key for an object property.

You can create a unique symbol using the function `Symbol()`:

```
let sym1 = Symbol();

```

You can give the symbol a description by passing a string parameter:

    let sym1 = Symbol('sym1');

Symbols can be used as unique property keys:

    const A_KEY = Symbol(); // unique key
    let obj = {};
    obj[A_KEY] = 'Enki';
    console.log(obj[A_KEY]); // 'Enki'
          


---

## Practice

Complete the following code snippet where symbols are used as unique property keys: 

```javascript
const key = ???(); 
let foo = {};
???[???] = 'Enki';
```

- Symbol
- foo
- key
- new
- symbol
- property
- sym
- a_key


---

## Revision

Create a symbol with `enki` description:

```javascript
let sym = ???(???);

```

- Symbol
- "enki"
- Sym
- Object
- property
 
