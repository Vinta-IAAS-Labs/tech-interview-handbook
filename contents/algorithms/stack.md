---
id: stack
title: Stack
toc_max_heading_level: 2
---

## Introduction

A a stack is an abstract data type that supports the operations **push** (insert a new element on the top of the stack) and **pop** (remove and return the most recently added element, the element at the top of the stack). As an abstract data type, stacks can be implemented using arrays or singly linked lists.

This behavior is commonly called LIFO (last in, first out). The name "stack" for this type of structure comes from the analogy to a set of physical items stacked on top of each other.

Stacks are an important way of supporting nested or recursive function calls and is used to implement depth-first search. Depth-first search can be implemented using recursion or a manual stack.

## Time complexity

| Operation | Big-O |
| --------- | ----- |
| Top       | O(1)  |
| Push      | O(1)  |
| Pop       | O(1)  |
| isEmpty   | O(1)  |

## Learning resources

- Readings
  - [Stacks and Overflows](https://medium.com/basecs/stacks-and-overflows-dbcf7854dc67), basecs
- Videos
  - [Stacks](https://www.coursera.org/lecture/data-structures/stacks-UdKzQ), University of California San Diego

## Corner cases

- Empty stack. Popping from an empty stack
- Stack with one item
- Stack with two items

<!-- ## Techniques

TODO: Monotonic stacks -->

## Recommended questions

- [Valid Parentheses](https://leetcode.com/problems/valid-parentheses)
- [Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks)
- [Implement Stack using Queues](https://leetcode.com/problems/implement-queue-using-stacks)
- [Min Stack](https://leetcode.com/problems/min-stack)
- [Asteroid Collision](https://leetcode.com/problems/asteroid-collision)
- [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation)
- [Basic Calculator](https://leetcode.com/problems/basic-calculator)
- [Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii)
- [Daily Temperatures](https://leetcode.com/problems/daily-temperatures)
- [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water)
- [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram)

## Recommended courses

import AlgorithmCourses from '../\_courses/AlgorithmCourses.md'

<AlgorithmCourses />
