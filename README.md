# README

## Problem 1: Sum of Distinct Elements

### Overview
Given two sets of elements represented as arrays, the task is to find the sum of all distinct elements present in either of the given sets.

### Features
- Uses Python's `set` data structure to find distinct elements efficiently.
- Computes the sum of the symmetric difference of both sets.
- Time complexity: **O(n + m)** (where n and m are the sizes of the input sets).

### Example
**Input:**
```
Set 1: [3, 1, 7, 9]
Set 2: [2, 4, 1, 9, 3]
```
**Output:**
```
Sum of distinct elements: 13 (distinct elements: 4, 7, 2)
```

## Problem 2: Dot Product and Orthogonality Check

### Overview
The goal is to calculate the dot (scalar) product of two vectors and determine if they are orthogonal. Two vectors are orthogonal if their dot product equals zero.

### Features
- Implements a `dot_product` function that computes the dot product of two vectors.
- Uses a procedure to check multiple vector pairs for orthogonality.
- Utilizes a nested loop to iterate through vector pairs.
- Time complexity: **O(n)** per vector pair.

### Example
**Input:**
```
Vectors: ([1, 2], [2, -1]), ([3, 4], [4, -3]), ([1, 0], [0, 1])
```
**Output:**
```
Vectors [1, 2] and [2, -1] are not orthogonal.
Vectors [3, 4] and [4, -3] are not orthogonal.
Vectors [1, 0] and [0, 1] are orthogonal.
```

### Usage
1. Modify the arrays to input desired sets or vectors.
2. Run the script to get the sum of distinct elements or check orthogonality.

---

**Author:** Grace Wambui Mugece


