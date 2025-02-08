# Java ArithmeticException: Integer Division by Zero

This repository demonstrates a common Java error: the `ArithmeticException` thrown when dividing an integer by zero. The `bug.java` file contains the erroneous code, while `bugSolution.java` provides a corrected version that handles potential division by zero.

**Bug:**
The bug arises from attempting to divide an integer by zero. This results in an `ArithmeticException` that halts the program's execution.

**Solution:**
The solution involves adding a check to ensure the divisor is not zero before performing the division. This prevents the exception and allows the program to continue running gracefully, potentially handling the error or displaying an appropriate message.