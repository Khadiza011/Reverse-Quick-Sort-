# Quick Sort (Descending Order) using Divide and Conquer

## Overview

This project implements the **Quick Sort Algorithm** in **C++** using the **Divide and Conquer** approach.

The program sorts an array in **descending order** by selecting the **last element as the pivot**. During execution, it also prints the array after every partition operation, allowing users to observe the sorting process step by step.

---

## Features

- User input for array size
- User input for array elements
- Quick Sort implementation using recursion
- Descending order sorting
- Displays intermediate partition results
- Displays the final sorted array

---

## Algorithm

1. Read the number of elements.
2. Input the array elements.
3. Select the last element as the pivot.
4. Partition the array:
   - Move elements greater than the pivot to the left.
   - Move smaller elements to the right.
5. Place the pivot in its correct position.
6. Recursively apply Quick Sort on the left and right subarrays.
7. Display the sorted array.

---

## Time Complexity

| Case | Complexity |
|------|------------|
| Best Case | **O(n log n)** |
| Average Case | **O(n log n)** |
| Worst Case | **O(n²)** |

The worst case occurs when the pivot always divides the array into highly unbalanced partitions.

---

## Space Complexity

- Average Case: **O(log n)**
- Worst Case: **O(n)**

---

## Sample Input

```
ENTER ARRAY SIZE: 8

ENTER ARRAY INPUTS:
12 4 7 9 1 15 3 10
```

---

## Sample Output

```
15 12 10 9 1 7 3 4

15 12 10 9 7 4 3 1

15 12 10 9 7 4 3 1

SORTED ARRAY:
15 12 10 9 7 4 3 1
```

---

## Project Structure

```
.
├── main.cpp
└── README.md
```

## Concepts Used

- Divide and Conquer
- Quick Sort
- Partitioning
- Recursion
- Pivot Selection
- In-place Sorting
- Time Complexity Analysis

---

## Notes

- The array is sorted in **descending order**.
- The **last element** is chosen as the pivot.
- Intermediate arrays are displayed after each partition step to visualize the sorting process.

---

## Author

**Khadiza Rehan**
