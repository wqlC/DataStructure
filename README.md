
# 常用数据结构及其算法的Java实现

本项目主要使用Java实现各种经典常用数据结构及其算法，包括但不仅限于链表、栈，队列，树，图等经典数据结构，持续更新中...

目前，该项目具体包括如下内容：

 - 单向链表的数据结构及其相关算法：单向链表结构包含两个要素，即头结点head和链表大小size，具体操作包括：

    - 链表的增删
    - 链表是否为空
    - 链表的大小
    - 链表的打印输出
    - 删除链表重复节点
    - 链表倒数第K个元素
    - 链表的反转
    - 链表的倒序输出
    - 链表的中间节点
    - 链表是否有环
    - 链表节点的删除(不知道头结点的情况下)
    - 链表是否相交
    - 链表的交点
 
 ---------------
 
 - 栈(顺序栈/链式栈)的数据结构及其相关算法：栈结构包含两个要素，即栈顶指针top和栈大小size，具体操作包括：

    - 压栈操作push
    - 弹栈操作pop
    - 查看栈顶元素peek
    - 查看栈的大小  
    - 查看栈是否为空
    - 查看栈的最小元素(O(1)时间复杂度)
 
 ---------------
 
 - 队列(基于数组的实现、基于链表的实现和基于栈的实现)的数据结构及其相关算法：队列结构包含三个要素，即队头指针head、队尾指针rear和队列大小size，具体操作包括：

    - 入队操作put
    - 出队操作pop
    - 查看队头元素peek
    - 查看队列的大小  
    - 查看队列是否为空
 
----------

 - 二叉树(链式实现)的数据结构及其相关算法：二叉树结构包含一个要素，即二叉树的根结点，具体操作包括：

    - 以广义表形式的字符串构建二叉树：'()'前表示根结点，括号中左右子树用逗号隔开，逗号不能省略
    - 二叉树的层次/广序遍历算法(辅助队列)
    - 二叉树的前序、中序、后序遍历的递归/非递归算法（辅助栈）:对每个节点而言，三种遍历方式都需要遍历该结点三次，三者唯一区别在于该结点的访问时机；特别注意后序遍历的迭代算法的实现
    - 根据二叉树的前序、中序或中序、后序遍历结果构建二叉树
    - 根据二叉树的根结点复制一颗二叉树
    - 二叉树的高度
    - 二叉树的结点总数
    - 二叉树的根结点、孩子节点的获取
    - 以广义表的形式打印二叉树
    - 判断两颗二叉树是否相等  

----------

 - 堆(数组实现)的数据结构及其相关算法：堆结构实际上是一个完全二叉树，能方便地从中取出最小/大元素，其包含两个要素，即存储数组heap[]和堆大小size。本实现为最小堆，具体操作包括：

    - 堆的构建(创建一个空堆，基于数组的构建)
    - 堆的插入(插入到堆尾，再自下向上调整为最小堆)
    - 堆的删除(删除堆顶元素并用堆尾元素添补，再自上向下调整为最小堆)
    - 堆排序(时间复杂度：O(nlgn),空间复杂度O(1),不稳定)：升序排序一般用最大堆，不断地将堆顶元素放到数组最后并缩小堆的范围
    - 堆的打印(树的前序遍历的应用)

----------


 - 八大排序算法及其实现，具体包括直接插入排序，希尔排序，直接选择排序，堆排序，冒泡排序，快速排序，归并排序，基数排序在内的八种排序算法，同时对各种算法的基本特征做出了详细分析：

    - 算法基本思想
    - 算法的种类：插入排序(直接插入排序，希尔排序)，选择排序(直接选择排序，堆排序(在堆的相关实现中给出))，交换排序(冒泡排序，快速排序)，归并排序，分配排序(基数排序)
    - 算法的时间复杂度
    - 算法的空间复杂度
    - 算法的稳定性
    - 内部排序/外部排序

----------
 
<font color='red'><b>注意:</b></font>

 - 堆排序的源码在堆的相关实现中给出
 - 源码中每个包对应一个数据结构及其算法的实现。若项目中的源代码存在谬误，请不吝指出，在此拜谢！




