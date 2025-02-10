# Append to Integer Variable in Go

This repository demonstrates a common error in Go: attempting to append to an integer variable instead of a slice.  The `bug.go` file contains the erroneous code, while `bugSolution.go` shows the corrected version.

**Error:** Go's `append` function works specifically with slices.  Applying it to an integer variable leads to a compiler error because integers are not slices.

**Solution:** Use a slice of integers and correctly append to it. 