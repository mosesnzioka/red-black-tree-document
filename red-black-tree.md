# Red-Black Tree 
## Introduction
A **Red-Black Tree**is a self-balancing binary search tree that ensures operations such as insertion, deletion, and searching remain efficient. This implementation in JavaScript adheres to the standard Red-Black Tree properties and provides functionality to insert nodes while maintaining balance.<br>

## Features of Red-Black trees
Self-balancing binary search tree.<br>
Efficient insertion with automatic property restoration.<br>
Logarithmic time complexity for:
Insertion: 
𝑂
(
log
⁡
𝑛
)
O(logn)<br>
Search: 
𝑂
(
log
⁡
𝑛
)
O(logn)<br>
Deletion (not implemented in this version): 
𝑂
(
log
⁡
𝑛
)
O(logn)
In-order traversal to display tree contents and node colors.<br>
## How Red-Black Tree Works
The Red-Black Tree maintains balance by adhering to these properties:

Each node is either red or black.<br>
The root node is always black.<br>
No two consecutive red nodes are allowed.<br>
Every path from a node to its descendant NULL pointers must contain the same number of black nodes.<br>
Newly inserted nodes are always red initially.<br>
To restore balance after insertion, the tree uses:<br>

Recoloring: Adjust the colors of nodes.<br>
Rotations: Left or right rotations to rebalance the structure.

## Code Example of Red-Black Tree
![code example](/assets/red-black%20trees.PNG);

## Out Put
![output](/assets/output.PNG)