# JavaScript + Operator Behavior with undefined and null

This repository demonstrates a subtle but important behavior of the `+` operator in JavaScript when dealing with `undefined` and `null` values.

## The Bug

When performing addition using the `+` operator, JavaScript handles `undefined` and `null` differently, leading to unexpected results.

- Adding a number to `undefined` results in `NaN` (Not a Number).
- Adding a number to `null` treats `null` as `0`.

This inconsistency can cause unexpected errors in applications, particularly when dealing with potentially missing or null values.

## Solution

To avoid unexpected behavior, explicitly check for `undefined` and `null` values and handle them appropriately before performing the addition.

## Usage

1. Clone this repository.
2. Open `bug.js` to observe the unexpected behavior.
3. Open `bugSolution.js` to see how to handle `undefined` and `null` values correctly to prevent this bug.
