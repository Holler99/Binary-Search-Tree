# Binary-Search-Tree


## Overview

A binary search tree (BST) is a data structure consisting of a collection of nodes in which each node has a key with an associated value.  

In a BST, the value of the key to the left sub-tree is less than the root node's key, and the value of the key to the right sub-tree is greater than or equal to the root node's key. Each node can have up to 2 child nodes. [Source 1.](https://www.tutorialspoint.com/data_structures_algorithms/binary_search_tree.htm)



## How Does a Binary Search Tree Work?

A BST works by having each node own a *comparable key* (and associated value) that satisfies the restriction that the key in any node is larger than the keys in all nodes in that node's left subtree and smaller than the keys in all nodes in that node's right subtree. [Source 2.](https://algs4.cs.princeton.edu/32bst/)  

Thus, a BST can be explained as follows:
>left_subtree (keys) < node (key) ≤ right_subtree (keys)


### Pictoral Example:  
![image](https://user-images.githubusercontent.com/78120051/200489601-fa5eff6a-1855-4ee2-bf03-c3e4a17b680b.png) [Source 3.](https://www.geeksforgeeks.org/binary-search-tree-data-structure/#basic)


### Pseudo Code:  
![image](https://user-images.githubusercontent.com/78120051/200489044-26002947-45a6-45f2-af16-6dbe3c3ec07e.png) [Source 4.](https://www.researchgate.net/figure/Binary-search-tree-pseudo-code_fig3_347423919)



## How Is a Binary Search Tree Useful?
Binary search trees are used for searching and sorting data in a hierarchial fashion. Because of this, you can see BST's being used in AI decision trees, routing tables, data compression (Huffman coding), indices for databases, sorting algorithms, and expression evaluation. [Source 5.] (https://www.baeldung.com/cs/applications-of-binary-trees#:~:text=In%20computing%2C%20binary%20trees%20are,insertion%2C%20deletion%2C%20and%20traversal.)  

Another perk of BST is that it has a time complexity of **O(log N)**.

## Works Cited
1. Tutorials Point - (https://www.tutorialspoint.com/data_structures_algorithms/binary_search_tree.htm)
2. Algorithms 4th Edition by Robert Sedgewick | Kevin Wayne - (https://algs4.cs.princeton.edu/32bst/)
3. GeeksforGeeks - (https://www.geeksforgeeks.org/binary-search-tree-data-structure/#basic)
4. Pesudo-Code by Fadhi Hujainah - (https://www.researchgate.net/figure/Binary-search-tree-pseudo-code_fig3_347423919)
5. Baeldung - (https://www.baeldung.com/cs/applications-of-binary-trees#:~:text=In%20computing%2C%20binary%20trees%20are,insertion%2C%20deletion%2C%20and%20traversal.)
