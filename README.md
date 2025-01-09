# JavaScript Type Coercion Bug

This repository demonstrates a common error in JavaScript related to type coercion in arithmetic operations.  When adding a number and a string, JavaScript will perform string concatenation instead of numerical addition, which can lead to unexpected results.

## Bug Description

The `foo` function attempts to add two numbers.  However, if one of the arguments is a string, the '+' operator will perform string concatenation.  This results in the incorrect output of '11' instead of 2 in one case.

## Solution

The solution involves explicit type conversion to ensure both arguments are numbers before performing the addition.