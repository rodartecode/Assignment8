# Assignment8
Binary Search Tree


This is a two part assignment.  In Part 1 you will modify the add() function in a binary tree implementation
to add nodes in random places in the tree.  In Part 2 you will answer some questions about binary search trees.


Part 1 - Binary Tree with Random Add

For part 1 of the assignment, you will add a function to a Binary Tree Implementation.  First, download and
compile the code base using the instructions on my website: 


Once you are up and running, examine the add() function in BinaryNodeTree.cpp.  It uses a balancedAdd() helper 
function to add a node, ensuring that the resulting tree remains balanced.


Instead of using balancedAdd() here, create a new function randomAdd(), which adds nodes in random places in the 
tree, and use that function instead.  A random place should be determined by starting at the root, and traversing 
down the tree left or right with 50% probability each time.  When you get to a point in the tree where left or 
right has no child, insert the node at this location.

