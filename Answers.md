# Questions

## 1. What are the order of insertions/removals for the following data structures?
* Stack: Last in, first out. (LIFO)
* Queue: First in, first out. (FIFO)


## 2. What is the retrieval time complexity for the following data structures?
* Linked List: Linked list access time is 𝛩(n) in the worst case.
* Hash Table: Hash table search takes 𝛩(n) in the worst case, and 𝛩(1) in average cases.
* Binary Search Trees: BST's retrieval time is logarithmic in average cases 𝛩(log(n)), and linear in the worst case 𝛩(n).

## 3. What are some advantages to using a Hash Table over an array in JavaScript?
  * A Hash table becomes a more efficient way to store data over an array as the data size becomes larger. Most operations can be done in constant time 𝛩(1) in average cases, and if the set of keys being stored is static search operations can be done in constant time 𝛩(1) in worst cases.
