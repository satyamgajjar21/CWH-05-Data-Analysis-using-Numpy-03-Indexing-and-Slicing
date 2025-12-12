# Indexing and Slicing in NumPy

## Overview
This project demonstrates how to access elements of NumPy arrays using indexing and slicing. It includes examples of one dimensional and two dimensional arrays and shows how to extract specific rows columns and ranges of values.

## One Dimensional Indexing
The notebook creates a one dimensional NumPy array and accesses individual elements by index.

```python
import numpy as np

arr = np.array([1, 2, 3, 4, 5, 6])
print(arr[0])
print(arr[2])
print(arr[-1])

## One Dimensional Slicing

## Slicing allows selecting a continuous range of values.

print(arr[1 4])
print(arr[:3])
print(arr[3:])
print(arr[::2])

## Two Dimensional Indexing

## Two dimensional arrays allow selection of rows and specific elements using row and column indices.

arr2 = np.array([[10, 20, 30],
                 [40, 50, 60],
                 [70, 80, 90]])

print(arr2[0][1])
print(arr2[2][2])

## Two Dimensional Slicing

## Rows and columns can be sliced just like one dimensional arrays but with two indices.

print(arr2[0:2, 1:3])
print(arr2[:, 1])
print(arr2[1:, :2])

## Key Learnings

1 Indexing retrieves single elements
2 Slicing retrieves ranges of elements
3 Two dimensional arrays use row and column positions
4 Slicing can target specific rows columns or submatrices
