# Type 'string[]' is not assignable to type 'string'
This repository contains a TypeScript bug report and its solution. The bug arises from attempting to pass an array of strings to a function expecting a single string argument.

## Bug Description
The TypeScript compiler throws an error because the `greeter` function expects a single string argument but receives an array of strings (`string[]`).

## Solution
The solution demonstrates proper type handling by either modifying the `greeter` function to accept an array of strings or modifying the function call to pass a single string argument.