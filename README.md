# Forest-Problem---Graph-Theory-

You are given a tree (a simple connected graph with no cycles). The tree has  N nodes with the following structure:
It has data and references to its child nodes.(max 3 child nodes).

struct node {
    int data;
    struct node* child1, child2, child3;
}

Find the maximum number of edges you can remove from the tree to get a forest such that each connected component of the forest contains an even number of vertices.

Special Case: Ignore all nodes with data value 0 while counting.
Example :
If a tree has the following vertices :
        

Then number of vertices in this forest is 2 and not 3






Sample Input:
    
Decomposed tree:



Explanation
On removing edges (1,3)  and (1,6), we get 2 as output (2 edges need to be removed to get the decomposed tree).
You are required to implement a function (assuming C here) with the following signature: 
int countEven(node * root) 
where root is constructed from step A. 
You can implement in any language of choice (port the structure and method signature accordingly)
