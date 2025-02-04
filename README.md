# Data Structures Course

> Prerequisites: Although all of the topics, which we will need throughout the course are present in C++ revision, it is still highly recommended to have a basic understanding of C++ language before reading all of this. Below are the topics which Hakobyan recommends to revise before even starting to listen lectures and read the materials:
- std::cout, std::cin
- int, unsigned int, long, unsigned long, long long, unsigned long long, short, unsigned short
- float, double
- bool
- pointers
- C-style arrays. C-strings
- std::string
- functions, main function

# C++ Revision (Mandatory to pass this course)

1. **Revising C++**  
   - References, pointers  
   - Stack segment and heap segment  
   - Operators `new`/`delete`  
   - Function overloading and default parameters  
   - Passing variables by value and by reference/const reference  
   - l-value vs r-value  

2. **Revisiting OOP in C++**  
   - `struct`  
   - Member variables and member functions  
   - Default constructors, constructors with parameters  
   - Operator overloading  

3. **Function/Class Templates**  
   - Basic implementation of a fixed-size array in C++  
   - Destructor, copy constructor, assignment operator  
   - Access specifiers: `private`, `public`, `protected`  
   - `class` vs `struct`  
   - `const` member functions  

4. **Advanced References & Casting**  
   - l-value/r-value references  
   - `std::move`, move constructor, move assignment operator  
   - Type casting in C++: `static_cast`, `reinterpret_cast`, `const_cast`  

5. **Virtual Functions & Exception Handling, 4 OOP concepts**  
   - Virtual functions  
   - Function overloading vs function overriding  
   - Usage of virtual functions (examples), virtual destructors
   - Pure virtual functions, abstract classes
   - Exception handling  
   - OOP concepts
     - Encapsulation
     - Inheritance
     - Polymorphysm
     - Abstraction
---

# Linear Data Structures and Their Implementation in STL

6. **Asymptotic Analysis**  
   - Big O / Omega / Theta notation definitions  
   - Amortized analysis (examples)  

7. **Vector**  
   - `std::vector` and its member functions:  
     - Default constructor  
     - Constructor with size parameter  
     - Constructor with size and value parameters  
     - `operator[]`, `at()`, `size()`, `empty()`, `push_back()`, `pop_back()`, `front()`, `back()`, `clear()`  
   - About `std::vector` implementation, complexity analysis
   - Amortized analysis of `push_back()` complexity  

8. **Singly Linked List**  

   - Implementation details  
   - `std::forward_list`  
   - `pop_front()`, `push_front()`, `front()`  
   - Comparison with `std::vector`  
   - Iterating through `std::forward_list` by range-based `for` loop  
9. **Doubly Linked List**  
   - Implementation details  
   - `std::list`, member functions, complexities  

10. **Iterators in C++**  
    - `insert()`, `erase()`, `std::find()`, `std::sort()`, `std::count()` usage on `std::vector`, complexities
    - Iterator implementation for fixed-size arrays  
    - Iterator categories  
    - `std::distance` and `std::advance` (implementations)  
    - Lambda functions in `std::find()`, `std::sort()`, `std::count()`

11. **Deque**  
    - Implementation using `std::vector` / `std::list`  
    - Implementation with a circular buffer  
    - Corresponding STL implementation  
    - Complexity analysis for `std::deque`  

12. **`std::queue` and `std::stack`**  
    - Problems that may require their usage  

13. **Recursion**  
    - Ricursive algorithms and their complexities on linear data structures  
    - `binary_search`  
    - `merge_sort`, `quick_sort`  

---

# Sorted Containers and Their Implementation in STL

14. **Trees**  
    - Definition of a tree and corresponding concepts (height, level, binary tree, etc.)  
    - Binary tree traversals: pre-order, post-order, in-order  
    - Traversing a tree using BFS  

15. **Binary Search Trees (BST)**  
    - Algorithms for finding/inserting/removing an element  
    - Complexity analysis  
    - Definition of a balanced tree  
    - Asymptotic estimate of the height of a balanced tree  

16. **Tree Rotations & AVL Trees**  
    - Inserting/finding/removing an element from an AVL tree  

17. **Red-Black Trees**  
    - Definition  
    - Asymptotic estimate for the height of a red-black tree  

18. **`std::set`, `std::map`, `std::multiset`, `std::multimap`**  
    - Their member functions  
    - Iterators  

19. **Definition of a Heap**  
    - Inserting/removing element from heap  
    - Constructing a heap from a `std::vector`  
    - Complexity analysis  
    - `std::priority_queue`  

---

# Hash Tables and Their Implementation in STL

20. **Definition of a Hash Function and a Hash Table**  
    - Closed addressing  
    - Complexity analysis  
    - `std::unordered_set`, `std::unordered_map`, `std::unordered_multiset`, `std::unordered_multimap`  
    - Examples of hash functions  

21. **Open Addressing Techniques**  
    - Linear probing  
    - Quadratic probing  
    - Double hashing  
    - Cuckoo hashing  
    - Complexities  

---

# Other Data Structures

22. **Disjoint Sets (Union-Find)**
    - Union and Find operations
    - Complexity analysis  

23. **Graphs**  
    - Definition of a graph  
    - Ways to store a graph in memory  
    - `DFS` / `BFS`  

---

# C++ Advanced Concepts

24. **Smart Pointers**  
    - `unique_ptr`, `shared_ptr`, `weak_ptr`  
    - Their usage  
