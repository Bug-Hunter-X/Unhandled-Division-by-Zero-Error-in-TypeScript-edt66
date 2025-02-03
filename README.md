# Unhandled Division by Zero Error in TypeScript

This repository demonstrates a common error in TypeScript: forgetting to handle the potential for division by zero.  The `bug.ts` file contains a function that divides two numbers without properly handling the case where the divisor is zero. This results in a runtime error.

The `bugSolution.ts` file shows the corrected code, demonstrating how to gracefully handle the division by zero error using a `try...catch` block or by checking for the divisor being zero before performing the division.

This example illustrates the importance of comprehensive error handling in TypeScript to prevent unexpected crashes and ensure application stability.