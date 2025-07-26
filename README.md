# ADSAA-notes
My personal notes on Data Structures and Algorithms
**Why AVL Tree is O(log n)**
In an AVL tree:
The tree automatically balances itself using rotations.
After every insertion or deletion, it ensures the height difference (balance factor) is not more than 1.
This self-balancing guarantees that the height h of the tree with n nodes is always:
ℎ≤1.44log2(𝑛+2)−0.328
 The height is always proportional to log(n)
