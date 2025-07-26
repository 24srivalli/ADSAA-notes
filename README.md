# ADSAA-notes
My personal notes on Data Structures and Algorithms



**AVL TREE**(Self balancing tree):
An AVL tree defined as a self-balancing Binary Search Tree (BST) where the difference between heights of left and right subtrees for any node cannot be more than one.
Balance Factor = left subtree height - right subtree height
For a Balanced Tree(for every node): -1 ≤ Balance Factor ≤ 1

-> Why AVL Tree is O(log n) :
The tree automatically balances itself using rotations.
After every insertion or deletion, it ensures the height difference (balance factor) is not more than 1.
This self-balancing guarantees that the height h of the tree with n nodes is always:
ℎ≤1.44log2(𝑛+2)−0.328.The height is always proportional to log(n)

**Rotations**: rotations are designed to restore balance in O(1) time while ensuring the overall time complexity remains O(log n). AVL Trees use four types of rotations to rebalance themselves after insertions and deletions:
1.Left-Left (LL) Rotation
2.Right-Right (RR) Rotation
3.Left-Right (LR) Rotation
4.Right-Left (RL) Rotation

**2-3 TREE**
