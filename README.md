This project implements an algorithm that processes a singly linked list by dividing its nodes into sequential, non-empty groups whose sizes follow the sequence of natural numbers: 1, 2, 3, 4, and so on. Specifically:

The 1st node is placed in the 1st group (size 1).

The 2nd and 3rd nodes are placed in the 2nd group (size 2).

The 4th, 5th, and 6th nodes are placed in the 3rd group (size 3).

This pattern continues, with each subsequent group increasing in size by 1.

If the total number of nodes is insufficient to complete a group, the final group may contain fewer nodes than its intended size, but it will still include all remaining nodes.

Objective: Reverse the nodes in each group only if the group has an even length, then return the head of the modified linked list.

This behavior ensures a partially reversed list depending on the parity of the group sizes.

