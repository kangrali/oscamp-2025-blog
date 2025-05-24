# oscamp-2025-blog
记录oscamp2025的学习记录

## 阶段一 rust编程（3.31 - 4.4）
初学rust语言编程，完成rustlings练习巩固学习成果
[实验仓库](https://github.com/LearningOS/2025s-rustling-kangrali)

### 3.31
阅读官方Rust程序设计语言电子书，安装rust开发环境，学习基本语法

安装rustlings环境

### 4.1
阅读完Rust book前6章内容，学习了rust所有权，结构体，枚举和模式匹配等部分的内容

完成rustlings相关部分的练习

### 4.2
阅读完Rust book 7-9章的内容，学习了用mod管理项目内容，常见集合(Vec、HashMap)的用法，以及用Result类型进行简单的错误处理

完成rustlings相关部分练习

### 4.3
阅读完Rust book 10-14章的内容，重点学习了范型、trait等相关内容，这一部分体现了rust语言的强大表达能力，trait机制相比cpp的继承机制要灵活很多。学习了迭代器的使用。

完成rustlings相关练习

### 4.4
阅读完Rust book 15-20章内容，学习智能指针，并发、异步编程

完成rustlings剩余的练习

## 阶段二 rcore（4.7 - 4.29）
学习os，完成rCore实验

[实验仓库及实验报告](https://github.com/LearningOS/2025s-rcore-kangrali)

### 4.7 - 4.10
预习os和risc-v特权指令的相关内容

### 4.11
开始rCore实验，看实验指导书，配置实验环境。Mac apple芯片机器本地环境下不方便，在docker容器中开发

### 4.12 - 4.15
看ch1 - ch3的内容，了解了kernel启动需要的过程，学习了用户特权级与内核特权级之间的切换过程（重点理解了trap上下文的保存以及__restore函数恢复的过程）

完成ch3的实验和实验报告

### 4.15 - 4.18
阅读第四章的内容，学习地址空间及页表机制，完成实验ch4，写实验报告

### 4.19 - 4.21
阅读第五章内容，学习进程管理及调度，完成实验ch5，写报告

### 4.22 - 4.25
阅读第六章，学习easy-fs，完成ch6实验及报告

### 4.26 - 4.29
阅读第七、第八章，学习线程管理，锁机制、信号量、条件变量的实现，完成ch8实验和报告

## 阶段三 Arceos (5.4 - 5.9)
主要通过观看课程视频回放，学习arceos基础内容，完成实验

[实验仓库](https://github.com/LearningOS/2025s-arceos-kangrali)

### 5.4 - 5.5
看unikernel的三个课时视频，做前四个练习

- 练习一：在axhal中加入ANSI转义字符时，所有的输出都会变颜色。在axstd的宏中加转义字符时，只有最后的打印部分会变色
- 练习二：阅读rust std中的hashmap实现，在axstd中加入了hashbrown的hashmap
- 练习三：实现alt alloc中的内存分配算法
- 练习四：实现ramfs的rename

### 5.6 - 5.7
看宏内核的三个课时视频，完成练习五，实现sys_mmap

### 5.8 - 5.9
看hypervisor的三个课时视频，完成练习六
