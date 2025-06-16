# C++ Data Structures & Algorithms Library (dsalgo.h)

 **A single-header, template-based C++ library featuring generic linked lists, sorting algorithms, and essential data structures.**
 
## Features

### Data Structures
- **Linear Structures**:
  - Singly/Doubly Linked Lists (`SinglyLL`, `DoublyLL`)
  - Stack (`Stack`) & Queue (`Queue`)
- **Circular Structures**:
  - Singly/Doubly Circular Linked Lists (`SinglyCL`, `DoublyCL`)
- **Trees**:
  - Binary Search Tree (`BST`) with traversals (Inorder/Preorder/Postorder)
 
### Algorithms
- **Array Operations** (`ArrayX`):
  - Sorting: BubbleSort, SelectionSort, InsertionSort
  - Searching: Linear, Bidirectional, Binary Search
- **Utility Methods**:
  - `Minimum()`, `Maximum()`, `Summation()`
  - Frequency counting (`CountFrequency()`), Position-based search

**Key Advantages**  
✔ **Zero dependencies**
✔ **Templated** for any data type (`int`, `string`, custom objects)  
✔ **Memory-safe** with destructors  
✔ **Competition-ready** 

## Usage Examples

### Linked List
```cpp
#include "dsalgo.h"

int main() {
    SinglyLL<std::string> list;
    list.InsertFirst("Hello");
    list.InsertLast("World");
    list.Display();  // Output: |Hello|->|World|->NULL
}
