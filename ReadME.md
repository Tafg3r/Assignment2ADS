Data Structures Implementation in Java

This repository contains Java implementations of commonly used data structures, including ArrayList, LinkedList, Queue, MinHeap, and Stack.

ArrayList

The MyArrayList class implements a dynamic array, which automatically grows when more elements are added. It supports operations such as adding elements, removing elements, accessing elements by index, and resizing the array when necessary.

LinkedList

The MyLinkedList class implements a doubly linked list, where each element contains references to both the next and previous elements in the list. It supports operations such as adding elements to the beginning or end of the list, removing elements, and traversing the list forwards and backwards.

Queue

The MyQueue class implements a queue data structure, which follows the First-In-First-Out (FIFO) principle. It supports operations such as adding elements to the back of the queue, removing elements from the front of the queue, and checking if the queue is empty.

MinHeap

The MyMinHeap class implements a binary min-heap, which is a complete binary tree where every parent node has a value less than or equal to the values of its children. It supports operations such as adding elements, removing the minimum element, and checking if the heap is empty.

Stack

The MyStack class implements a stack data structure, which follows the Last-In-First-Out (LIFO) principle. It supports operations such as pushing elements onto the stack, popping elements from the top of the stack, and checking if the stack is empty.


Here's a brief example of how to use MyArrayList:


MyArrayList<Integer> list = new 

MyArrayList<>(); 

list.add(10);

list.add(20);

int firstElement = list.get(0); // Should return 10