# Tcl Division by Zero Bug

This repository demonstrates a common error in Tcl: division by zero. The `badproc` procedure doesn't handle the case where the first argument is 0, leading to an error.  The solution shows how to properly handle this case.

## Bug
The `bug.tcl` file contains the buggy code.  Running this script will result in an error.

## Solution
The `bugSolution.tcl` file provides a corrected version of the procedure, preventing the division by zero error.