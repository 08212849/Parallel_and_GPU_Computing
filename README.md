## CUMT并行计算与GPU编程

### 作业一

Pthread多线程求和1+2+3+…+10000000。要求利用锁写出两个函数分别求1-50000和50001-100000的部分和，并在主程序中输出最终的结果。

### 作业二

利用pthread实现对矩阵相乘进行加速，要求：随机生成两个矩阵(500\*300,300\*400)，矩阵相乘要求完成串行和并行两个功能。

### 作业三

利用CUDA基于四种线程布局（2D&2D，1D&1D，2D&1D，1D&2D）对两个矩阵（16384\*16384）求和。