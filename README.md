# Java ArrayIndexOutOfBoundsException Bug
This repository demonstrates a common Java programming error: an ArrayIndexOutOfBoundsException caused by an off-by-one error in a for loop.

The `BuggyArray.java` file contains the buggy code. The loop iterates one element beyond the array's bounds, leading to the exception.

The `FixedArray.java` file provides the corrected code.  The loop condition is changed to ensure the loop stops before accessing an invalid index.

This example highlights the importance of carefully considering loop boundaries when working with arrays in Java.