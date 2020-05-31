# read-14
### 28 may 2020

## Read: 
- [Trees](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)

Node Tree
the very first node at the top of the tree is hte root. to the left of the root goes values less than the root, and on the right of the root is values that are greater than the root. a leaf is the node connected to the left or right child of the root. the connection to the leaf is called the edge, the number of edges it takes to get to the lowest leaf from the root is the height. a tree with a root, a left child, and one leaf, would have a height of 2, because there are two connections between the 3 values. 

Pre order transversal goes depth first, from the root, all left values, then all right values.
in order transversal goes depth first, from the lowest left value, the root, then the right values
post order transversal goes depth first, from the lowest left value, the right values, then the root

recursion transversals use a call stack, when going through the tree the call stack holds the valles but has not called them yet, this allows you to start from the bottom and travel back up the tree. the root is held in teh call stack and is poped off when it has no left or right. 

breadth first transversals go through each level of the tree using a queue rather than a call stack.
when the value is put into the queue, it gets dequeued and enqueues its children. 