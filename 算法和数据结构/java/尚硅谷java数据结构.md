游戏

1、汉诺塔游戏

A空间内有12345数字，从小到大排列，现在有两个B、C空间，将A空间移动到C空间，一次智能移动一个数字，且每个空间数字都是按照大到小排列，空间是栈结构

```

 

```



2、八皇后





3、马踏飞燕





数据结构和算法

算法结构

内存计算框架Spark和缓存Redis计算



最小生成树 + 普利姆算法

图+弗洛伊德算法

分支算法

回溯算法



线性结构

一对一

顺序存储结构

链式存储结构

实现：数组、队列、链表、栈

非线性结构

二维数组、多维数组、表、图、书



使用数组模拟环形队列的思路分析

1. front变量的含义是指向队列的第一个元素

2. rear变量的含义是指向队列的最后一个元素的后一个位置

3. 当没超过一圈时

   1. 有效数据个数为  rear - front  = (rear -front) % maxsize = (rear  - front + maxsize) % maxsize
   2. d 

4. 当超过一圈时

   1. 有效数据个数为 rear + ( maxsize - front)  = (rear + maxsize -front) % maxsize

5. 综上

   有效个数为



链表

​		无序存储，以节点node的方式存储，每个节点包含data域和next域(指向下一个节点)

类型有带头节点的链表和没有头节点的链表

栈

栈的应用:

- 在跳往子程序前，会先将下个指令的地址存到堆栈中，直到子程序执行完后再将地址取出，以回到原来的程序中
- 处理递归调用: 和子程序的调用类似，只是除了存储下一个指令的地址外，也将参数、区域变量等数据存入堆栈中
- 表达式的转换【中缀表达式】与求值
- 二叉树的遍历
- 图形的深度优先搜索法