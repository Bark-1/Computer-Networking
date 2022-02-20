<div align='center' ><font size='70'>武汉大学计算机学院本科生实验报告</div>

<center><font size='6'>tracert一个服务器</center>

> 课程：计算机网络
>
> 学号：2020302111274
>
> 姓名：杨俊奇

[TOC]

## 1. 实验目的

​		tracert（跟踪路由）是路由跟踪实用程序，用于确定IP数据包访问目标所采取的路径。本次实验需要tracert一个服务器。

## 2. 实验环境

​		Windows 10

## 3. 实验步骤

1. **打开命令控制台**

​		在电脑开始菜单中点击运行选项，或Win+R，在运行窗口中输入cmd，确定，进入命令控制台。

![image-20220219100727160](C:\Users\Bark\AppData\Roaming\Typora\typora-user-images\image-20220219100727160.png)

2. **使用tracert指令**

​		在命令控制台中输入“tracert www.baidu.com”即可。

​		“tracert -d www.baidu.com”可以不将地址解析成主机名，能够更快地显示路由器路径。

​		“tracert -h maximum_hops www.baidu.com”可以设置搜索目标的最大跃点数。

​		“tracert -w timeout www.baidu.com”表示等待每个回复的超时间。

## 4. 实验结果与总结

​		通过以上操作，可得到实验结果：

![image-20220219101119410](C:\Users\Bark\AppData\Roaming\Typora\typora-user-images\image-20220219101119410.png)

​		通过本次实验，掌握了tracert的用法，学会了tracert一个服务器的方法步骤，也更加理解tracert命令。

