# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The `BuggyArray.java` file contains code with the error, while `FixedArray.java` provides the corrected version.

**The Bug:**
The original code attempts to access an array element beyond its bounds, causing an `ArrayIndexOutOfBoundsException`.  This is a classic off-by-one error resulting from incorrect loop termination conditions.

**The Solution:**
The corrected code uses the condition `i < arr.length` to ensure the loop iterates only within the valid bounds of the array.