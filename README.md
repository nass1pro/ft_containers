
# ft_containers

## Introduction

**ft_containers** is a project aimed at re-implementing some of the standard C++ container types in compliance with **C++98**. This hands-on exercise, part of the 42 School curriculum, helps students delve into the internal mechanics of container implementations by creating simplified versions of commonly used data structures.

---

## Features Implemented

### 1. `ft::vector`
- Mimics the dynamic array behavior, offering random-access iterators, size management, and reallocation mechanisms.

### 2. `ft::list`
- Implements a doubly linked list structure, providing bidirectional iterators and efficient insertion/removal anywhere in the container.

### 3. `ft::map`
- A balanced binary search tree (typically a Red-Black Tree) handling key-value pairs with logarithmic time insertions, deletions, and lookups.

### 4. `ft::stack`
- Adapts an underlying container (commonly `ft::vector` or `ft::list`) to provide Last-In-First-Out (LIFO) operations.

### 5. `ft::queue`
- Adapts an underlying container (commonly `ft::list`) for First-In-First-Out (FIFO) operations.

---

## Key Details

Each container is built to mirror its STL counterpart, ensuring:
- Similar methods
- Compatible iterators
- Comparable time complexity

---

