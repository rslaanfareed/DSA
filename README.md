<div align="center">
<br/>

# Data Structures & Algorithms
### C++ · UET Taxila

[![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)]()
[![University](https://img.shields.io/badge/UET-Taxila-8B0000?style=flat-square)]()

</div>

---

Implementations of fundamental data structures and algorithms in C++, written from scratch — no STL containers, no shortcuts. Every structure is built at the pointer and memory level to understand what's actually happening under the hood.

---

## Contents

| Module | What's Inside |
|---|---|
| [`Arrays_and_sorting/`](./Arrays_and_sorting) | Bubble sort, linear search, binary search with duplicate handling |
| [`LinkedLists/`](./LinkedLists) | Singly, sorted, doubly, circular — including a playlist simulation |
| [`Stacks/`](./Stacks) | Array-based & linked-list-based; string reversal, parenthesis validation |
| [`Queues/`](./Queues) | Circular queue, priority queue |
| [`Hashing/`](./Hashing) | Hash tables with linear probing and separate chaining |
| [`Tree/`](./Tree) | BST — insert, delete, search, preorder traversal |
| [`infix_and_postfix/`](./infix_and_postfix) | Infix → postfix conversion, postfix evaluation |
| [`Matrix_operations/`](./Matrix_operations) | Matrix manipulation |
| [`University_bus_scheduling/`](./University_bus_scheduling) | Applied project — real scheduling problem solved with DSA |

---

## Design Philosophy

Every implementation here is written **without STL data structures**. No `std::stack`, no `std::queue`, no `std::list`. The point isn't reinventing the wheel — it's understanding the wheel.

That means:
- Manual memory management with raw pointers
- Node-based structures built from scratch
- Explicit traversal logic, no abstractions hiding the mechanics

---

## Building & Running

Requires any C++17-compatible compiler.

```bash
git clone https://github.com/rslaanfareed/DSA.git
cd DSA/<module>
g++ -std=c++17 -o out <file>.cpp && ./out
```

---

## Complexity Reference

| Structure | Search | Insert | Delete | Space |
|---|---|---|---|---|
| Array | O(n) / O(log n)* | O(n) | O(n) | O(n) |
| Linked List | O(n) | O(1) | O(1) | O(n) |
| Stack / Queue | O(n) | O(1) | O(1) | O(n) |
| Hash Table | O(1) avg | O(1) avg | O(1) avg | O(n) |
| BST | O(log n) avg | O(log n) avg | O(log n) avg | O(n) |

*Binary search on sorted array*

---

## Author

**Arslan Fareed** — CS Student, UET Taxila  
[github.com/rslaanfareed](https://github.com/rslaanfareed)
