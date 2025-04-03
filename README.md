# C++ Data Structures & Algorithms Library (dsalgo.h)

🚀 A **single-header, templated** C++ library implementing essential data structures and algorithms with clean, reusable code.

## Features

### Data Structures
- **Linear**: 
  - Singly/Doubly Linked Lists (`SinglyLL`, `DoublyLL`)
  - Stack (`Stack`) & Queue (`Queue`)
- **Circular**:
  - Singly/Doubly Circular Linked Lists (`SinglyCL`, `DoublyCL`)
- **Trees**:
  - Binary Search Tree (`BST`)

### Algorithms
- **Array Operations** (`ArrayX`):
  - Sorting: BubbleSort, SelectionSort, InsertionSort
  - Searching: Linear, Bidirectional, Binary Search
- **Utility Methods**:
  - `Minimium()`, `Maximum()`, `Summation()`
  - Frequency counting, position-based search

## Usage
```cpp
#include "generic.h"

int main() {
    // Example 1: Stack
    Stack<int> stack;
    stack.Push(10);
    std::cout << "Popped: " << stack.Pop() << "\n";

    // Example 2: BST
    BST<float> tree;
    tree.Insert(3.14f);
    tree.Inorder();  // Output: 3.14
}
---


