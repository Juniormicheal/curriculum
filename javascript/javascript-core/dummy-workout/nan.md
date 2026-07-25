---
author: adamMontgomerie
levels:
  - basic
  - beginner
type: normal
category: feature
tags:
  - NaN
  - numbers
  - not-a-number
links:
  - '[NaN Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/NaN){website}'
practiceQuestion:
  formats:
    - fill-in-the-gap
  context: relative
revisionQuestion:
  formats:
    - fill-in-the-gap
  context: relative
---

# `NaN`


---

## Content

`NaN` stands for 'Not a Number' and is used when a number value is expected but a value which is not a number is produced.

For example, when attempting to parse a string that does not contain a number value:
```javascript
Number("Enki"); //NaN
```
`"Enki"` cannot be converted into a valid number so `NaN` is returned.

Additionally:
```javascript
let x = 0/0; //NaN
```
`x` will be `NaN`, which is the result of `0/0`.


---

## Practice

What does the following code return? ???

```javascript
NaN === NaN
```

- False
- True
- 0
- Undefined


---

## Revision

What will each of these output?

```javascript
console.log(Number("enki")); // ???
console.log(0/0 ===
   Number("five")); // ???
```

- NaN
- false
- enki
- True
- true
- 0
 
