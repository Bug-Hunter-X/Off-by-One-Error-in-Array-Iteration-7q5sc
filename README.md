# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error occurs because the loop condition `i <= arr.length` includes the index that is out of bounds.

**bug.java** contains the erroneous code.
**bugSolution.java** provides the corrected version.

This example highlights the importance of carefully checking loop boundaries when working with arrays in Java to prevent unexpected exceptions.