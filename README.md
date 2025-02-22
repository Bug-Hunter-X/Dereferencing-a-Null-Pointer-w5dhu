# Dereferencing a Null Pointer in C++

This repository demonstrates a common error in C++: dereferencing a null pointer.  Dereferencing a null pointer attempts to access memory at address 0, which typically leads to a segmentation fault (crash) or other undefined behavior. This can be difficult to debug because the error doesn't always manifest consistently. 

The `bug.cpp` file contains the faulty code. The `bugSolution.cpp` demonstrates how to prevent this error by checking for null pointers before dereferencing.