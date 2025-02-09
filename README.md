# JavaScript Null and Undefined Handling Bug

This repository demonstrates a common error in JavaScript related to handling `null` and `undefined` values in functions.  The original code correctly handles `null` values but omits `undefined`, which can cause unexpected results.

The `bug.js` file contains the faulty code.  The `bugSolution.js` file shows the corrected version that correctly addresses both `null` and `undefined` inputs.

## Bug:
The `foo` function handles `null` gracefully but fails to handle `undefined` inputs. This leads to a potential `TypeError` or other unexpected results depending on how the function is used. 

## Solution:
The improved function explicitly checks for both `null` and `undefined` values to ensure robust handling of various input types. 
