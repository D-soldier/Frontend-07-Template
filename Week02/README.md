# 学习笔记
### 堆排序
堆排序是使用数组来存储平衡二叉树，所有的父节点都在n/2 - 1之前的数组中，每个父节点的子节点为2*n + 1 和2*n + 2的位置上；
堆排序过程，从最后一个父节点开始，使父节点大于全部子节点（大根堆），当交换父节点和子节点之后要继续检查孙节点是否为大根堆或小根堆,将整个堆变为大根堆/小根堆
当整个堆变为大根堆或小根堆后，交换根节点与最后一个元素，重新对堆进行调整，调整完成后再次交换根节点与次后一个元素，直到整个数组有序；

### A*算法的优缺点
根据起点终点距离的A*算法相比广度优先寻路算法在路径为正向的时候时间要远远大于广度优先算法，当路径为逆向的时候，时间基本等于广度优先算法；寻路的时间长短取决于A*算法的指示函数
想法: 如果同时对起点和终点使用A*算法，每次排序使用

### css的lineHight
子元素的行号取决于父元素的lineHight；整个地图在没有设置父元素行高的时候，行间距特别大，当把父元素的行高设置为0时，子元素行间距消失

