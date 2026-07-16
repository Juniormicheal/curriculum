---
author: enki-ai
category: feature
type: normal
practiceQuestion:
  context: relative
  formats:
    - fill-in-the-gap
revisionQuestion:
  context: relative
  formats:
    - fill-in-the-gap
---

# String Methods

---
## Content

Kotlin offers methods to manipulate strings, like changing case or finding length.

- Transform text (using `uppercase()`, `lowercase()`, `trim()`)
- Search within text (with `contains()`, `indexOf()`, `startsWith()`)
- Extract information (via `substring()`, `split()`)
- Format data (through `format()`, `padStart()`, `padEnd()`)


```kotlin
val language = "Kotlin"
val text = "I am learning $language"

println(text.uppercase()) // Outputs: I AM LEARNING KOTLIN
println(text.length) // Outputs: 20

// check if the text contains the word "Kotlin"
println(text.contains("Kotlin")) // Outputs: true

// position in text where "Kotlin" starts
println(text.indexOf("Kotlin")) // Outputs: 14

// extract the chunk of text starting at position 14
println(text.substring(14)) // Outputs: Kotlin

// split the text into a list of words
println(text.split(" ")) // Outputs: [I, am, learning, Kotlin]
```

> 💡 Manipulating text is essential to building web apps, mobile apps, and more.

---
## Practice

What does `"world".uppercase()` return?

???

- WORLD
- world
- World


---
## Revision

The `length` method returns the ??? of characters in a string.

???

- `number`
- `type`
- `color`
