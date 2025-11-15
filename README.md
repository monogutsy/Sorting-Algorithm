# 🧮 Sorting Algorithms

A collection of classic sorting algorithms I have learned so far.  
Each file in this repository contains an implementation of a different sorting technique.  
This project acts as a learning reference for understanding how sorting algorithms work, how efficient they are, and when they should be used.

---

## 📂 Algorithms Included

### 🔹 Basic Sorting Algorithms
- **Bubble Sort** – Repeatedly swaps adjacent elements until sorted.
- **Selection Sort** – Selects the smallest element and moves it to the sorted portion.
- **Insertion Sort** – Inserts each element into its correct position in the sorted part.

### 🔹 Efficient Comparison-Based Sorts
- **Merge Sort** – Divide-and-conquer algorithm that splits, sorts, and merges.
- **Quick Sort** – Fast divide-and-conquer algorithm using a pivot to partition the list.
- **Heap Sort** – Builds a binary heap and repeatedly extracts the max/min to sort.

### 🔹 Non-Comparison Sort
- **Radix Sort** – Sorts numbers by processing digits using counting sort as a subroutine.

---

## 📊 Time Complexity Summary

| Algorithm       | Best        | Average      | Worst        | Space     | Stable |
|----------------|-------------|--------------|--------------|-----------|--------|
| Bubble Sort    | O(n)        | O(n²)        | O(n²)        | O(1)      | ✔ Yes |
| Selection Sort | O(n²)       | O(n²)        | O(n²)        | O(1)      | ✘ No |
| Insertion Sort | O(n)        | O(n²)        | O(n²)        | O(1)      | ✔ Yes |
| Merge Sort     | O(n log n)  | O(n log n)   | O(n log n)   | O(n)      | ✔ Yes |
| Quick Sort     | O(n log n)  | O(n log n)   | O(n²)        | O(log n)  | ✘ No |
| Heap Sort      | O(n log n)  | O(n log n)   | O(n log n)   | O(1)      | ✘ No |
| Radix Sort     | O(nk)       | O(nk)        | O(nk)        | O(n + k)  | ✔ Yes |


