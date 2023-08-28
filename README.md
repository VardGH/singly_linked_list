# singly_linked_list Implementation in C++

This project provides a C++ implementation of a singly linked list data structure along with various operations like insertion, deletion, sorting, and more.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)

## Introduction

A singly linked list is a fundamental data structure that consists of nodes, each containing data and a pointer to the next node in the sequence. This implementation provides a dynamic and memory-efficient way to manage collections of elements.

## Features

- Insert elements at the beginning, end, or at specific positions.
- Remove elements from the beginning, end, or at specific positions.
- Clear the entire list.
- Check if the list is empty.
- Get the size of the list.
- Reverse the list in-place.
- Sort the list using the merge sort algorithm.

## Usage

You can use this implementation by including the `linked_list.hpp` and `node.hpp` header files in your project. The `linked_list` class provides a comprehensive set of methods to interact with the singly linked list data structure. Here's a simple example:

```cpp
#include "linked_list.hpp"

int main() {
    linked_list<int> list;
    list.push_back(42);
    list.push_back(17);
    list.push_back(31);

    list.print_list(); // Output: 42 17 31

    list.pop_back();
    list.print_list(); // Output: 42 17

    return 0;
}
