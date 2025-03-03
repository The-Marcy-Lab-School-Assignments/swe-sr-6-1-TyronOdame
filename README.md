# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

Arrays, Linked Lists and Doubly Linked Lists all allow programmers to organize data in a sequence. So, how would you choose to use one over the other?

In your response, make sure to compare the time complexities for insertion, removal, and random access (grabbing a particular known element by index/position) for each data structure as well as memory usage and ease of traversal.

### Response 1
Imagine any MTA train with its carts. 


## Array
* like a train where all carts are tightly connected. You can jump to any cart fast which would give you a time complexity of (O(1)--> constant time regardless of how many carts).
* if you wanted to add or remove a cart in the middle, you would have to shift all the other carts. Resulting in a slower (insert/removal) causing you to have have a time complexity of O(n.)

## Singly Linked List
* Every cart is linked to the next one with a connector that goes one way. You can easily add or remove a cart without shifting everything which would cause a faster insert/removal time complexity of O(1)
* What may slow down this process is actually looking for a specific cart which would cause you to move one by one giving you a slower time complexity of O(n)

## Doubly Linked List
* Every cart has connectors on both sides, so you can move forward and backwards easily.


Using an ``array`` for quick access, a ``single linked list`` for frequent adding or removing and a `doubly linked list` if you need to move both ways.


## Prompt 2

Imagine you are developing a web browser's "back" button functionality. When a user clicks "back," the browser should navigate to the previously visited webpage. 

Would you use a stack or a queue to implement this functionality? 

In your response, explain what a Stack/Queue is and why it would be best for this use case. Make sure that your response includes the terms LIFO or FIFO.

### Response 2

## Prompt 3

What is an Abstract Data Type and why are they worth learning about?

### Response 3
An `Abstract Data Type` is a way to organize and use data without stressing too much how it works on the inside. Its like a shopping basket. You can add items, remove, or check what is inside. You don't exactly need to know how the basket is made or how it holds whats inside. `ADT's `are useful because they help you write cleaner, more efficient code. You focus on what you need to do with the data like adding or removing without worrying about how it is stored. Examples of ADT's are `stacks`(a pile of items where you only take from the top `LIFO --> last in first out`) or `Queues` (a line where people get in the back and leave from the front --> `FIFO first in first out`).

## Prompt 4

A few classic problems involving a stack are the `isBalanced` and `isPalindrome` functions. Choose one of these functions and provide a solution to it along with a brief lesson explaining how it works. 

### Response 4



