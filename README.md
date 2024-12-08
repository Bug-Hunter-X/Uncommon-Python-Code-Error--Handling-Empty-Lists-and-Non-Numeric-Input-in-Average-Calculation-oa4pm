# Python Code Bug: Average Calculation

This repository demonstrates a common yet subtle bug in Python code related to calculating the average of a list of numbers. The initial code lacks proper handling for empty lists and lists containing non-numeric values. The solution provides a robust approach to address these edge cases.

## Bug Description

The `calculate_average` function, in its initial form, doesn't correctly handle empty input lists or lists with non-numeric elements. This can lead to either a `ZeroDivisionError` (for empty lists) or a `TypeError` (for lists with non-numeric values).

## Solution

The solution refactors the function to include explicit checks for empty lists and attempts to convert list elements to numbers, handling potential `ValueError` exceptions gracefully.  This enhances the function's robustness and prevents unexpected errors.