个人的学习笔记

1、计算机网络相关：
	1）TCP和UDP的区别
	2）ARP是地址解析协议，工作原理
	3）为什么采用三次握手，若采用两次握手是否可以
	4）TCP怎样进行流量控制，拥塞控制

2、弱类型和强类型的简单理解

3、volatile+先行发生关系+线程安全：
	1）Java中的volatile 变量是什么
	2）Java内存模型是什么
	3）什么是线程安全？Vector是一个线程安全类吗？

4、Java线程相关：
	1）Java中如何停止一个线程
	2）一个线程运行时发生异常会怎样
	3）如何在两个线程间共享数据
	4）Java中notify 和 notifyAll有什么区别
	5）为什么wait, notify 和 notifyAll这些方法不在thread类里面

5、Java实现多线程：
	1）什么是线程
	2）线程和进程的一些区别
	3）如何在Java中实现多线程
	4）用Runnable还是Thread
	5）start()和run() 方法有什么区别

6、JVM+垃圾回收：
	关于JVM的垃圾回收机制(改进后的复制算法)和四种引用的解释

7、IO相关+String相关+ArrayList扩容：
	1）BIO/NIO/AIO	
	2）String相关
	3）ArrayList扩容

8、线程可见性：
	1、可见性
	2、共享变量
	3、两条规定
	4、共享变量可见性实现原理
	5、要实现共享变量的可见性，必须保证两点
	6、Java语言层面支持的可见性实现原理方式
	
9、线程的生命周期及状态：
	在线程的生命周期中，它要经过新建、就绪、运行、阻塞、死亡总共5种状态。现介绍以下三种：
		1、就绪状态
		2、运行状态
		3、阻塞状态
		
10、数据库概述：
	1、DDL、DML、DQL、DCL的相关内容，包括sql命令
	2、java与mysql的数据类型对比
	3、主键、唯一、非空约束
	4、truncate、auto_increment
	5、外键约束---处理多表间的关系
	6、多表查询---笛卡尔积、外连接、子查询
	7、附录