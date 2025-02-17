# COBOL Loop Control Bug

This repository demonstrates a common, subtle bug in COBOL programs involving loop control and off-by-one errors. The `bug.cob` file contains the erroneous code.  The correct version is provided in `bugSolution.cob`.  The error is in the loop termination condition and how it interacts with the counter increment and the summation operation within the loop.