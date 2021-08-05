# Our Topic is about Stacks and Queues


## First , What is a Stack?

![stack](https://cdn.programiz.com/sites/tutorial2program/files/stack.png)

> A stack is a data structure that consists of Nodes. Each Node references the next Node in the stack, but does not reference its previous.



### Stacks follow these concepts:

- **FILO**; **First In Last Out**

  > This means that the first item added in the stack will be the last item popped out of the stack.
- **LIFO**; **Last In First Out**
  >This means that the last item added to the stack will be the first item popped out of the stack

### Everytime we are Pushing a Node onto a stack will always be an O(1) operation. Push O(1)

### Everytime we are Popping a Node off a stack will always be an O(1) operation. Pop O(1)

### Peek O(1) , IsEmpty O(1) , so When conducting a peek, you will only be inspecting the top Node of the stack so, you would check isEmpty before conducting a peek and that will always be an O(1) operation.

## So What is a Queue?

![queue](https://www.101computing.net/wp/wp-content/uploads/queue-diagram.png)

> A Queue is a data structure that consists of Nodes. Each Node references the next Node but does not reference its previous.

### Queues follow these concepts:

#### **FIFO**, First In First Out ,this means that the first item in the queue will be the first item out of the queue.

#### **LILO** ,Last In Last Out , This means that the last item in the queue will be the last item out of the queue.

### Enqueue O(1):

> When you add an item to a queue, you use the enqueue action. This is done with an O(1) operation in time .

### Dequeue O(1)

>When you remove an item from a queue, you use the dequeue action. This is done with an O(1) operation in time

### Peek O(1)

> When conducting a peek, you will only be inspecting the front Node of the queue so, you want to check isEmpty before conducting a peek and it follows the same operation time **IsEmpty O(1)**

