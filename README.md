# Type Error in TypeScript
This repository demonstrates a common type error in TypeScript that arises when using functions with specific type parameters. The error occurs when an argument of an incompatible type is passed to the function.

## Bug Description
The `greeter` function is defined to accept a single string argument and return a string. However, an array of strings is passed as an argument to the function, resulting in a type error.

## Bug Reproduction
1. Clone this repository.
2. Compile the TypeScript code using the command `tsc bug.ts`.
3. Execute the compiled JavaScript code using Node.js.

## Bug Solution
The solution involves modifying the function to either accept an array of strings or handle the individual strings within the array.