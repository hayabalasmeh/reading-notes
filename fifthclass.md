## Our Topic is about Linked lists.

![link list](https://res.cloudinary.com/practicaldev/image/fetch/s--XEtVnws7--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/trsu6uhv8j0x1fhzx53a.png)

### First let’s discover some definitions So What is a Linked List?
>A data structure that contains nodes that links/points to the next node in the list.
>A Singly linked list means that there is only one reference,
>A Doubly linked list means that there is a reference to both the Next and Previous node.
>Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
>Next - Each node contains a property called Next. This property contains the reference to the next node
>Head - The Head is a reference of type Node to the first node in a linked list.
>Current - The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list.

### How they are traversing?
- It depend on the Next value in each node to guide us where the next reference is pointing.
- The Current variable will tell us where exactly in the linked list we are and will allow us to move/traverse forward until we hit the end.
- So The best way to approach a traversal is through the use of a while() loop. 
- This allows us to continually check that the Next node in the list is not null

### Adding a Node
### There are multiple ways of adding:
1-Adding O(1), efficiency
2-Adding a Node O(n) , efficiency

### Let’s jump to the basics so we can better imagine what we are dealing with
### What is Data Structure?
>They are the different ways that we can organize our data; variables, arrays, hashes, and objects 

### What are the types of Data structures?
1-	Linear data structures, which means that there is a sequence and an order to how they are constructed and traversed
2-	Non-linear data structures, items don’t have to be arranged in order, which means that we could traverse the data structure non-sequentially.

### What about memory allocation for the linked list compared to list ?
>When we create linked list , it doesn’t need all the required bytes of memory all in one place. 
>Meaning that Linked lists don’t need to take up a single block of memory; instead, the memory that they use can be scattered throughout.

### Why it can be scattered?
- Because a node only knows about what data it contains, and who its neighbor is.
- Because a single node has the “address” or a reference to the next node, they don’t need to live right next to one another, the way that the elements have to in an array.

### Linked List vs arrays(list)?
- Arrays are static data structures
- While linked lists are dynamic data structures.

### How we can grow the link list?
1.	First, we find the head node of the linked list.
2.	Next, we’ll make our new node, and set its pointer to the current first node of the list.
3.	Lastly, we rearrange our head node’s pointer to point at our new node

### Why we would need the Big O?
- Whether we are building software as a service, choosing a front end framework, or just trying to make our code DRY and more elegant
### How to understand the concept behind the Big O?
- You can look at it in a way to express the amount of time that a function, action, or algorithm takes to run based on how many elements we pass to that function.
- Big O Notation takes into account: the speed and efficiency with which something functions when its input grows to be any (crazy big!) size.
