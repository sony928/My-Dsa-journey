# Time and Space Complexities 📘

## Common Complexities
- **O(1):** Constant time → Accessing an element by index.
- **O(log n):** Logarithmic → Binary Search.
- **O(n):** Linear → Traversing an array/linked list.
- **O(n log n):** Log-linear → Merge Sort, Quick Sort (average).
- **O(n²):** Quadratic → Nested loops, Bubble Sort.
- **O(2^n):** Exponential → Recursive Fibonacci.
- **O(n!):** Factorial → Travelling Salesman brute force.

---

## Sorting Algorithms
| Algorithm        | Best Case | Average Case | Worst Case | Space Complexity |
|------------------|-----------|--------------|-------------|------------------|
| Bubble Sort      | O(n)      | O(n²)        | O(n²)       | O(1)             |
| Insertion Sort   | O(n)      | O(n²)        | O(n²)       | O(1)             |
| Selection Sort   | O(n²)     | O(n²)        | O(n²)       | O(1)             |
| Merge Sort       | O(n log n)| O(n log n)   | O(n log n)  | O(n)             |
| Quick Sort       | O(n log n)| O(n log n)   | O(n²)       | O(log n)         |
| Heap Sort        | O(n log n)| O(n log n)   | O(n log n)  | O(1)             |
| Counting Sort    | O(n+k)    | O(n+k)       | O(n+k)      | O(k)             |
| Radix Sort       | O(nk)     | O(nk)        | O(nk)       | O(n+k)           |

---

## Search Algorithms
| Algorithm         | Time Complexity | Space Complexity |
|-------------------|-----------------|------------------|
| Linear Search     | O(n)            | O(1)             |
| Binary Search     | O(log n)        | O(1)             |
| Hash Table Search | O(1) avg, O(n) worst | O(n)       |

---

## Data Structures
| Data Structure     | Access | Search | Insert | Delete | Space |
|--------------------|--------|--------|--------|--------|-------|
| Array              | O(1)   | O(n)   | O(n)   | O(n)   | O(n)  |
| Stack              | O(n)   | O(n)   | O(1)   | O(1)   | O(n)  |
| Queue              | O(n)   | O(n)   | O(1)   | O(1)   | O(n)  |
| Singly Linked List | O(n)   | O(n)   | O(1)   | O(1)   | O(n)  |
| Doubly Linked List | O(n)   | O(n)   | O(1)   | O(1)   | O(n)  |
| Binary Search Tree | O(log n) | O(log n) | O(log n) | O(log n) | O(n) |
| Hash Table         | N/A    | O(1) avg, O(n) worst | O(1) | O(1) | O(n) |

---

