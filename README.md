# Forest-Problem---Graph-Theory-

You are given a tree (a simple connected graph with no cycles). The tree has  N nodes with the following structure:
It has data and references to its child nodes.(max 3 child nodes).

struct node {
    int data;
    struct node* child1, child2, child3;
}

Find the maximum number of edges you can remove from the tree to get a forest such that each connected component of the forest contains an even number of vertices.

You are required to implement a function (assuming C here) with the following signature: 
int countEven(node * root) 
where root is constructed from step A. 
You can implement in any language of choice (port the structure and method signature accordingly)
