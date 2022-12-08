# study-guide

**Table of Contents:**
* [Variables](#variables)
* [Functions](#functions)
* [If Statements](#if-statements)
* [Arrays](#arrays)
* [Objects](#objects)
* [For Loops](#for-loops)
* [Array Iteration](#array-iteration)

## Variables

**Definition**: A variable holds onto a data value. A variable is created by assigning a data value to a name (called the variable's "identifier"). Once created, referencing the variable's name/identifier will return the held data value. Variables are useful for keeping track of changing or unknowable data throughout the lifetime of a program.

**Syntax**: A reassignable variable is **declared** using the `let` keyword followed by the variable's name.  A variable is assigned a value by writing the variable's name followed by `=` followed by a data value. 

```js
let x;          // declare a variable named `x`
x = 5;          // assign the value `5` to the variable `x`
x = 10;         // assign the value `10` to the variable `x`
x = x + 1;      // use the current value of `x` to calculate a new value assigned to `x`

let y = 10;     // declare AND assign a variable in one line;

let z = x + y;  // use the values of x and y to calculate the value assigned to the newly declared variable `z`
```

In this example above, the variable `x` is declared and then reassigned multiple times. It's final value will be `11`. Then, the variable `y` is declared and assigned a value `10` in one line (also called "initialized"). Finally, `z` is declared and assigned a value `21`, calculated by the expression `x + y`. 

**Notes:** 

* Variables declared with `const` can't be reassigned

```js
const name = "ben";
name = "carmen"; // Throws a TypeError
```

* Variables declared with `const` and `let` are block scoped and are not hoisted.
* Variables decalred with `var` are function scoped, are reassignable, and have their declarations hoisted.

## Functions

## If Statements

## Arrays

## Objects

## For Loops

## Array Iteration
