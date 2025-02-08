# Uncommon CSS `calc()` Errors and Solutions

This repository demonstrates some uncommon errors that can occur when using the CSS `calc()` function and how to resolve them.

The `bug.css` file shows examples of `calc()` usage with incorrect syntax and nested expressions that might lead to unexpected results.

The `bugSolution.css` file provides the corrected versions with explanations of the fixes.

## Common Issues:

* **Missing Spaces Around Operators:** Ensure spaces are present around the +,-,*,/ operators in `calc()` expressions.  Missing spaces can lead to the expression being parsed incorrectly.
* **Invalid Units:** Use valid units with all operands. Inconsistent or invalid units will cause errors.
* **Nested Expressions and Order of Operations:** Be mindful of parentheses to control the order of operations when nesting `calc()` expressions.  Incorrect parenthesis placement can result in unintended calculations.