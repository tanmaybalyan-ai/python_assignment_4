# python_assignment_4
(a) Key Features of NumPy & Differences Between NumPy Arrays and Python Lists
Key Features of NumPy

Efficient Multi-Dimensional Arrays
NumPy provides the ndarray object which supports 1D, 2D, and multi-dimensional arrays.

Fast Numerical Computation
Operations in NumPy are implemented in C, making them much faster than Python lists.

Vectorization
NumPy allows performing operations on entire arrays without loops.
Example:
a = np.array([1, 2, 3])
print(a * 2)     # Output: [2 4 6]
Mathematical and Statistical Functions
Functions like sum(), mean(), sqrt(), dot(), etc., make scientific computing easy.

Memory Efficiency
NumPy uses less memory compared to Python lists because it stores elements of the same data type.

Support for Broadcasting
Enables operations between arrays of different shapes.

Integration with Other Libraries
Libraries like Pandas, SciPy, Matplotlib depend on NumPy
Example Comparison
Python List
lst = [1, 2, 3]
print(lst * 2)     
# Output: [1, 2, 3, 1, 2, 3] → Repetition, NOT multiplication

NumPy Array
import numpy as np
arr = np.array([1, 2, 3])
print(arr * 2)
# Create one-dimensional and two-dimensional arrays
import numpy as np

arr1 = np.array([10, 20, 30, 40, 50])

arr2 = np.array([[1, 2, 3],[4, 5, 6]])

print("----- One-Dimensional Array -----")
print("Array:", arr1)
print("Shape:", arr1.shape)
print("Dimensions:", arr1.ndim)
print("Data Type:", arr1.dtype)

print("----- Two-Dimensional Array -----")
print("Array:", arr2)
print("Shape:", arr2.shape)
print("Dimensions:", arr2.ndim)
print("Data Type:", arr2.dtype)
