<meta http-equiv="content-type" content="text/html; charset=UTF-8">

Boot a PC
========

本文采用2007年的[版本](http://pdos.csail.mit.edu/6.828/2007/)。
原文链接(http://pdos.csail.mit.edu/6.828/2007/labs/lab1/lab1.html)

# 介绍
本节的实验被分为三部分。

- 第一部分：
> 1. 熟悉x86汇编语言
> 2. 使用Bochs x86仿真器。
> 3. PC上电开机启动过程。

-  第二部分
> 讲解了6.828内核使用的boot loader，这部分的代码位于lab1代码树的boot文件夹下。

- 第三部分
> 探讨了6.828内核的初始化部分，这个内核也称之为JOS，这部分代码位于kernel目录下。

# 环境搭建

首先你需要下载本次实验的[代码](http://pdos.lcs.mit.edu/6.828/2007/labs/lab1/lab1.tar.gz)。可以使用如下命令：


        linux% cd ~/6.828
        linux% wget http://pdos.lcs.mit.edu/6.828/2007/labs/lab1/lab1.tar.gz
        linux% gtar xzvf lab1.tar.gz
        linux% cd lab1
        linux%

**注意**原MIT课程使用了Athena系统来提供学生的上机服务。此处用用自己的实验过程来进行补充。



