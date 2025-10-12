Tree Traversal :
1. [Pre order](https://leetcode.com/problems/binary-tree-preorder-traversal/)

2. [Inorder](https://leetcode.com/problems/binary-tree-inorder-traversal)

3. [Postorder](https://leetcode.com/problems/binary-tree-postorder-traversal/)
   1. with 1 stack and 2 stack.


Based on Basic Recusrion(DFS) :

1. Max depth of BT
2. Is BT Balaced (height diff at any node<2 ans -1 approach).
3. Diameter of BT (max left + right depth).
4. Max depth sum (if node is -ve make it 0).
5. Two BT are identical(for symmentric instaed of 2 BT use root->left , root->right).
6. Root to Node path (back track pushed element).
7. LCS (common decendent ancestor [move left if right null and vice versa else you got that ancestor])

Based on Level order Traversal (BFS) :
1. Zig-Zag ptint BT(maintain flag).
2. Width of Tree (maintain 2i+1 and 2i*2 for left right child).

Based on Fixed logic :
1. Boundary BT(Left node right node + leaves node[bottom last]).
2. verticle Order Traversal (maintain queue{v,level,node{multiset}}).
3. Top View (first element of veticle Order travesal , use map<int,itn>).
4. Right view 
   a. brute force : level order last element.
   b. optimse : Traversal with [Root Right Left]
5. left view
   a. brute force : level order first element.
   b. optimse : Traversal with [Root Right Left]



