# Vue & cs
Learning Vue.js and computer science!

## 内部排序算法可视化

### 交换排序
1.[冒泡排序](https://hummingg.github.io/Vue/BubbleSortVisualized.html)
  - 依次比较两个相邻的元素，如果顺序错误就把他们交换，直到没有相邻元素需要交换。
  
2.[快速排序](https://hummingg.github.io/Vue/QuickSortVisualized.html)
  - 通过一趟排序将数据按枢轴分割成独立的两部分，其中一部分都比枢轴小，另一部分都比枢轴大；如此递归进行直到整个数组有序。

### 插入排序
1.[直接插入排序](https://hummingg.github.io/Vue/InsertSortVisualized.html)
  - 将数据逐个插入到已排好的有序表中，初始时有序表中只有数组的第一个数据。
  
2.[折半插入排序](https://hummingg.github.io/Vue/BinaryInsertSortVisualized.html)
  - 直接插入排序算法的改进。
  - 由于前半部分为已排好的有序表，故采用折半查找的方法可加快寻找插入点的速度。
  
3.[希尔排序](https://hummingg.github.io/Vue/ShellSortVisualized.html)
  - 直接插入排序算法的改进。
  - 把记录按下标的增量d分组(所有距离为d的倍数的记录放在同一个组)，对每组使用直接插入排序算法排序,然后减少增量d。
  - 最后，当增量d逐渐减至1时，整个文件恰被分成一组，此时同直接插入排序。

### 选择排序
1.[简单选择排序](https://hummingg.github.io/Vue/SelectSortVisualized.html)
  - 每次从左至右扫描待排序的子序列，记下最小值的位置，再和待排序子序列的最左边的数据交换。每次能确定一个数据的最终位置。
  
2.[堆排序](https://hummingg.github.io/Vue/HeapSortVisualized.html)
  - 堆是完全二叉树，并同时满足堆的性质：即子结点的键值总是小于（或者大于）它的父节点。
  - 堆中定义以下几种操作：
  
    1.创建大根堆：将堆中的所有数据重新排序。
    
    2.大根堆调整：堆的根节点的数据逐层向下移动，直到使所有子节点都小于其父节点。
    
    3.堆排序：替换根节点的数据，并做大根堆调整的递归运算。

### [归并排序](https://hummingg.github.io/Vue/MergeSortVisualized.html)
  - 将已有序的子序列合并，得到完全有序的序列。
  - 初始时每个数据都是一个有序子序列。
  - 示例为二路归并，即每次都将两个有序表合并成一个有序表。
### [基数排序](https://hummingg.github.io/Vue/RadixSortVisualized.html)
  - 将要排序的元素分配至某些“桶”中。
  - 将所有待比较数值（正整数）统一为同样的数位长度，数位较短的数前面补零。
  - 然后，从最低位开始，依次进行一次排序。
  - 这样从最低位排序一直到最高位排序完成以后, 数列就变成一个有序序列。

## 算法经典问题可视化
1.[八(N)皇后](https://hummingg.github.io/Vue/Problems/QueensVisualized.html)
  - 递归和回溯
2.[隐马尔可夫模型](https://hummingg.github.io/Vue/Model/hmm.html)
  - 前向算法
  - 后向算法
  - 维特比算法
