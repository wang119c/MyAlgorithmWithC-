
- [-, 15, 17, 19, 13, 22, 16, 28, 30, 41, 62]

### 对于完全二叉树来说，（根节点的索引是从1开始的）

1 它所有的叶子节点（没有子节点的节点）来说，
2 它们已经是最大堆（虽然堆中只有一个元素）

第一个非叶子节点的索引 == 这棵完全二叉树的元素个数 n / 2

> 对叶子节点进行shiftDown操作，直至根节点，这个过程就叫作 Heapify


**堆主要的应用还是动态数据的维护**


Heapify的算法复杂度

将n个元素逐个插入到一个空堆中，算法复杂度是O(nlogn)
heapify的算法复杂度是O(n)






