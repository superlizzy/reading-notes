# 08 - Operators & Loops

### Comparison Operators

You can **evaluate** (or check) a condition by using a comparison. The result of a comparison is expressed as a Boolean (i.e., `true` or `false`).

Operator | Name | Definition
---------|------|-----------
`==` | **IS EQUAL TO** | This operator compares two values to see if they are the same, and returns either `true` or `false`. You can use this operator with numbers, strings, or Booleans.
`===` | **STRICT EQUAL TO** | This operator checks two values to see if they are the same value *and* the same data type, and returns either `true` or `false`. **It is generally best practice to use the Strict Equal To operator rather than the Is Equal To operator.**
`!=` | **IS NOT EQUAL TO** | This operator compares two values to see if they are different, and returns either `true` or `false`. This operator can compare numbers, strings, and Booleans.
`!==` | **STRICT NOT EQUAL TO** | This operator checks two values to see if they are **both** different values *and* different data types, and returns either `true` or `false`. **It is generally best practice to use the Strict Not Equal To operator rather than the Is Not Equal To operator.**
`>` | **GREATER THAN** | This operator checks to see if the number on the left is of greater value than the number on the right, and returns either `true` or `false`.
`>=` | **GREATER THAN OR EQUAL TO** | This operator checks to see if the number on the left is *either* a greater value *or* the same value as the number on the right, and returns either `true` or `false`.
`<` | **LESS THAN** | This operator checks to see if the number on the left is of lesser value than the number on the right, and returns either `true` or `false`.
`<=` | **LESS THAN OR EQUAL TO** | This operator checks to see if the number on the left is *either* a lesser value *or* the same value as the number on the right, and returns either `true` or `false`.

### Logical Operators

With **logical operators**, you can compare the values of more than one comparison. Similar to comparison operators, logical operators will return the Boolean values of `true` or `false`.

Operator | Name | Definition
---------|------|-----------
`&&` | **LOGICAL AND** | If both expressions evaluate to `true`, then the expression returns `true`. But if one or both of the expressions evaluate to `false`, it will return `false`.
`||` | **LOGICAL OR** | If at least one of the expressions evaluate to `true`, then the expression will return `true`. If both evaluate to `false`, it will return `false`.
`!` | **LOGICAL NOT** | This operator reverses the Boolean value that would have originally been returned. Think of it as "Not `true` = `false`" and "Not `false` = `true`."

---

### Loops

Loops check a condition. If the loop returns `true`, it will run a specified code block. It will continue to run this code in a loop for as long as the condition returns `true`.

Loop Type | Definition
----------|-----------
**FOR** | A For Loop is the most common type of loop. It can be run a specific number of times/loops. The condition of a For Loop is usually a counter, which specifies how many times the loop should run.
**WHILE** | A While Loop is used when you're not sure how many times a specific code block should run. The condition will continue to look for as long as it continues to return `true`.
**DO WHILE** | A Do...While Loop does the same thing as a While Loop, *except* a Do...While Loop will always run at least once, even if the condition returns `false`.

---

[Back to Home](https://superlizzy.github.io/reading-notes/)