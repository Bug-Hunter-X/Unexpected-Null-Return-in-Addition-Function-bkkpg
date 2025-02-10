# Unexpected Null Return in Addition Function

This repository demonstrates a common JavaScript bug involving unexpected null return values in a simple addition function. The function `foo` is designed to add two numbers, but it returns `null` if either input is `null`. This behavior might be unexpected and can lead to errors in applications relying on the function to always return a numerical result.

The bug is demonstrated in `bug.js`, and a solution is provided in `bugSolution.js`. The solution addresses the problem by handling null values appropriately.