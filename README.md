# JavaScript Learning

This repository contains JavaScript learning materials, covering fundamental concepts through practical examples.

## Contents

- **Chapter 01 - JavaScript Basics**
  - `FirstprintCode.js` - Demonstrates the difference between `var` and `let` scope in loops with `setTimeout`
- **Chapter 02 - Variable Declarations**
  - `Var_example.js` - Examples using `var` (function-scoped, allows redeclaration and reassignment)
  - `Let_example.js` - Examples using `let` (block-scoped, allows reassignment but not redeclaration)
  - `Const_example.js` - Examples using `const` (block-scoped, cannot be reassigned or redeclared)

## Key Concepts Covered

### var vs let vs const

| Keyword | Scope | Redeclaration | Reassignment |
|---------|-------|---------------|--------------|
| `var` | Function | Allowed | Allowed |
| `let` | Block | Not Allowed | Allowed |
| `const` | Block | Not Allowed | Not Allowed |

### FirstprintCode.js Highlight

The `FirstprintCode.js` file demonstrates a classic JavaScript closure/scope interview question:

- Using `var` in a loop with `setTimeout` prints `3, 3, 3` because `var` is function-scoped and all callbacks share the same variable.
- Using `let` in a loop with `setTimeout` prints `0, 1, 2` because `let` is block-scoped and creates a new binding for each iteration.

## Getting Started

You can run any of the JavaScript files using Node.js:

```bash
node Chapter_01_Javascript/FirstprintCode.js
node Chapter_01_Javascript/Chapter_02_Javascript/Var_example.js
node Chapter_01_Javascript/Chapter_02_Javascript/Let_example.js
node Chapter_01_Javascript/Chapter_02_Javascript/Const_example.js
```

## Author

Learning JavaScript fundamentals step by step.
