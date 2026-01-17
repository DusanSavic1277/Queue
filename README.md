# Custom Queue Implementation in Java

This project demonstrates a custom implementation of the Queue data structure
using a circular array without relying on java.util.Queue.

## Features
- FIFO (First In First Out)
- enqueue
- dequeue
- peek
- isEmpty / isFull
- O(1) time complexity

## Why Circular Array?
It avoids shifting elements and ensures efficient memory usage.

## Example
enqueue(10)
enqueue(20)
enqueue(30)
dequeue() -> 10
