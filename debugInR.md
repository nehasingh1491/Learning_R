### Debugging in R

Bugs can be fixed using
1. Output variables to the screen. e.g.,print() or browser() for an interactive session
2. Using built-in commands in R. e.g., traceback() for the call stack
3. Interactive debugger using RStudio

Exception handling can be used in R for preventing bugs

**browser()** interrupts the execution of an expression and allows you to
inspect the environment of where browser() was called from.

**traceback()** prints the call stack of the last uncaught error (i.e., the sequence of calls that lead to the error).

**try()** is a wrapper to run an expression that might fail and allow the user's code to handle error-recovery (won't stop execution of the program).
