### 思想：分治
1. 实现：递归+双指针
2. 条件：left<=right
3. 单次逻辑：povit 左边的数据都比基准小，右边的数据都比基准大

### 2 堆排序
+ 参考：https://blog.csdn.net/u010452388/article/details/81283998
1. 堆：完全二叉树
2. 实现数组
3. 插入
4. 删除
6. 实现
  + std::priority_queue<std::pair(int,int)> mq;
7. 如何构造堆：log(n)




## 队列、栈
1. 适配器
2. 实现方式：vector 、list 、deque
3. 初始化
   + std::stack <int,std::vector>
   + std::queue <int,std::list> ;std::queue<int.std::deque> q;
4. 单调栈：第一个大于目标的元素
   + 单调递增栈：栈顶元素最小
   + 单调递减栈：栈顶元素最大