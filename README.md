# Go Map Access Panic

This repository demonstrates a common error in Go: accessing a map element without checking for nil.  This can lead to unexpected runtime panics, especially when dealing with maps that might not have been initialized.

The `bug.go` file contains the buggy code. The `bugSolution.go` file presents the corrected version.

## How to reproduce the bug:
1. Clone this repository.
2. Navigate to the repository's directory.
3. Run `go run bug.go`.

This will result in a panic. 

## How to fix the bug:
Always check if a map is nil before accessing its elements to prevent panics.  The solution in `bugSolution.go` demonstrates the proper way to handle map access.
