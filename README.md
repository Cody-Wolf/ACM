# Golang-in-ACM

为方便算法竞赛选手在各大OJ刷题而开发的基础使用模板

将会优化 Go 的刷题体验，在写题速度上，尽可能接近 C++ 甚至 Python

模板在 template 文件夹下，直接复制一份即可

# 使用说明

只需要将解题代码写入 Solve 函数即可

如果需要读入多组数据，请将 main 函数中的 T := 1 改为 T := 0

# 特性

函数和数据结构都有写注释，可以自行查看，

### 函数

目前有以下函数（部分实现了 64 位版本）：

- scan 读入（快速） 
- print 输出（快速）
- println 换行输出（快速）
- ri 读入一个整数
- rs 读入一个字符串
- min 最小值
- max 最大值
- sum 求和
- reverse 翻转切片
- lowerBound 二分查找（第一个大于等于 k 元素的位置）
- upperBound 二分查找（第一个大于 k 元素的位置）
- unique 切片去重
- valSet 给切片的全部元素设置值

## 数据结构

目前有以下数据结构（部分实现了 64 位版本）：

- Stack 栈
- Queue 队列
- PriorityQueue 优先队列
