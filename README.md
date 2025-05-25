# JS-Fundamentals

## 0. First constant, first print

**Task:** Write a script that prints “JavaScript is amazing”.

- Declared a constant variable `myVar` with the value "JavaScript is amazing"
- Used `console.log(...)` for output
- Did not use `var`

**File:** `0-javascript_is_amazing.js`

**Run with:**
```bash
node 0-javascript_is_amazing.js

## 1. 3 languages

**Task:** Write a script that prints 3 lines:
- C is fun
- Python is cool
- JavaScript is amazing

**File:** `1-multi_languages.js`

**Run with:**
```bash
node 1-multi_languages.js
## 2. Arguments

**Task:** Script prints a message depending on number of arguments passed.

- No arguments → "No argument"
- One argument → "Argument found"
- Two or more arguments → "Arguments found"

**File:** `2-arg
## 3. Value of my argument

**Task:** Script prints the first argument passed.

- If an argument is passed → prints it
- If no argument → prints "No argument"

**File:** `3-value_argument.js`

**Rules:**
- Uses `process.argv[2]`
- No use of `.length`
- `console.log(...)` used directly

**Run with:**
```bash
node 3-value_argument.js
node 3-value_argument.js School
## 4. Create a sentence

**Task:** Script prints two arguments in the format: `firstArg is secondArg`.

**File:** `4-concat.js`

**Run with:**
```bash
node 4-concat.js c cool
node 4-concat.js c
node 4-concat.js
## 5. An Integer

**Task:** Script prints an integer value from the first argument passed.

**File:** `5-to_integer.js`

**Rules:**
- Uses `parseInt()` to convert
- If result is a valid number → print `My number: <value>`
- If not → print `Not a number`
- Uses `isNaN()` (no `try/catch`)

**Run with:**
```bash
node 5-to_integer.js
node 5-to_integer.js 89
node 5-to_integer.js "89"
node 5-to_integer.js 89.89
node 5-to_integer.js School
## 6. Loop to languages

**Task:** Script prints 3 lines using an array and a loop.

**File:** `6-multi_languages_loop.js`

**Rules:**
- Uses an array to store strings
- Uses a loop to print each line
- No `var`, no `if/else`
- Only one `console.log(...)` per loop iteration

**Run with:**
```bash
node 6-multi_languages_loop.js
## 7. I love C

**Task:** Script prints "C is fun" x times, where x is the first argument.

**File:** `7-multi_c.js`

**Rules:**
- Uses a loop to print
- If no valid number is passed, prints: `Missing number of occurrences`
- Only 2 console.log statements used
- No `var`, only `const` and `let`

**Run with:**
```bash
node 7-multi_c.js 3
node 7-multi_c.js
node 7-multi_c.js -2
## 8. Square

**Task:** Script prints a square using the first argument as the size.

**File:** `8-square.js`

**Rules:**
- Prints a square of `X` characters
- If input is invalid or missing, prints `Missing size`
- Uses loops and `repeat()` for each row
- Only `const` and `let` allowed

**Run with:**
```bash
node 8-square.js 4
node 8-square.js
node 8-square.js School
## 9. Add

**Task:** Script adds 2 integers provided as arguments and prints the result.

**File:** `9-add.js`

**Rules:**
- Defines a function `add(a, b)`
- Uses `parseInt()` to convert arguments
- Outputs sum using `console.log(...)`
- No use of `var`

**Run with:**
```bash
node 9-add.js 4 5
node 9-add.js 10 100
node 9-add.js 1

