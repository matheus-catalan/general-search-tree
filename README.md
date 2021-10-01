# General Search Tree

A general tree has the following characterics: Each node can have not more than one parent. Only one node can have no parent, this node is the root of the tree. Each node can have any number of children

Assuming you want to create a tree with the following structure:

```
        1
     /     \
   2         3
           / | \
         4   5   6
       /  \
     7      8
```

to generate a tree, in the main method, you must instantiate a new Tree class passing to its constructor the number of nodes that this tree will contain, and then using the "addNode" method itself, passing as parameter the value of the root you want reference and the value of your neighbor, as many neighbors as you want:

```
    Tree tree(8);

    /* adding neighbors to the element 1 */
    tree.addNode(1, 2);
    tree.addNode(1, 3);

    /* adding neighbors to the element 3 */
    tree.addNode(3, 4);
    tree.addNode(3, 5);
    tree.addNode(3, 6);

    /* adding neighbors to the element 4 */
    tree.addNode(4, 7);
    tree.addNode(4, 8);
```





## Authors

- [@matheus-catalan](https://www.github.com/matheus-catalan)