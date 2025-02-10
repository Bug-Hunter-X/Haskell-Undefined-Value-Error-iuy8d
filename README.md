# Haskell Undefined Value Error

This repository demonstrates a common runtime error in Haskell: using the `undefined` value.  The `bug.hs` file contains the erroneous code, while `bugSolution.hs` provides a corrected version.

The error arises from attempting to use a value that hasn't been properly defined, resulting in a runtime exception. This is a frequent mistake, especially when dealing with incomplete or partially implemented functions. This example showcases how to identify and fix this issue.

## Running the Code

To reproduce the error, compile and run `bug.hs` using a Haskell compiler like GHC:

```bash
ghc bug.hs
./bug
```

To see the corrected code, compile and run `bugSolution.hs`:

```bash
ghc bugSolution.hs
./bugSolution
```