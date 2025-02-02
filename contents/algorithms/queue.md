---
id: queue
title: Queue
toc_max_heading_level: 2
---

## Introduction

A queue is a linear collection of elements that are maintained in a sequence and can be modified by the addition of elements at one end of the sequence (**enqueue** operation) and the removal of elements from the other end (**dequeue** operation). Usually, the end of the sequence at which elements are added is called the back, tail, or rear of the queue, and the end at which elements are removed is called the head or front of the queue. As an abstract data type, queues can be implemented using arrays or singly linked lists.

This behavior is commonly called FIFO (first in, first out). The name "queue" for this type of structure comes from the analogy to people lining up in real life to wait for goods or services.

Breadth-first search is commonly implemented using queues.

## Time complexity

| Operation | Big-O |
| --------- | ----- |
| Enqueue   | O(1)  |
| Dequeue   | O(1)  |
| Front     | O(1)  |
| Back      | O(1)  |
| isEmpty   | O(1)  |

## Learning resources

- Readings
  - [To Queue Or Not To Queue](https://medium.com/basecs/to-queue-or-not-to-queue-2653bcde5b04), basecs
- Videos
  - [Queues](https://www.coursera.org/lecture/data-structures/queues-EShpq), University of California San Diego

## Corner cases

- Empty stack
- Stack with one item
- Stack with two items

## Things to look out for during interviews

Most languages don't have a built in Queue class which to be used, and candidates often use arrays (JavaScript) or lists (Python) as a queue. However, note that the enqueue operation in such a scenario will be O(n) because it requires shifting of all other elements by one. In such cases, you can flag this to the interviewer and say that you assume that there's a queue data structure to use which has an efficient enqueue operation.

## Recommended questions

- [Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks)
- [Implement Stack using Queues](https://leetcode.com/problems/implement-queue-using-stacks)
- [Design Circular Queue](https://leetcode.com/problems/design-circular-queue)
- [Design Hit Counter (LeetCode Premium)](https://leetcode.com/problems/design-hit-counter)

## Recommended courses

import AlgorithmCourses from '../\_courses/AlgorithmCourses.md'

<AlgorithmCourses />
