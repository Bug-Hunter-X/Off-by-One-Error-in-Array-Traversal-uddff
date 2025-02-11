This repository demonstrates a common yet often overlooked error in Java programming: the off-by-one error in array traversal. The `bug.java` file shows the erroneous code, while `BugSolution.java` provides the corrected version.  The error arises from the loop condition `i <= arr.length`, which attempts to access arr[5] in an array with only indexes 0-4. This leads to an ArrayIndexOutOfBoundsException. The solution corrects the condition to `i < arr.length`. 