# Off-by-One Error in C++ Vector Iteration

This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`. The error occurs when the loop condition `i <= vec.size()` is used instead of `i < vec.size()`. This causes the code to attempt to access the element at index `vec.size()`, which is one past the last valid element, leading to undefined behavior.

The `bug.cpp` file contains the erroneous code, and `bugSolution.cpp` provides the corrected version.