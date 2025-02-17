# JavaScript Error Handling: undefined length property

This repository demonstrates a common JavaScript error related to handling undefined values when checking for length.

## The Bug
The `foo` function attempts to access the `length` property of an object.  This works fine for arrays and other objects with a length property, however, when passed `undefined`, it throws a TypeError.

## The Solution
The solution involves checking if the input value is either `null` or `undefined` before attempting to access the `length` property.  This prevents the error and handles both cases gracefully.