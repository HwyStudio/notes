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
	
11、JDBC相关
	1、jdbc操作步骤及jdbc-api详解
	2、配置文件及ResourceBundle工具类快速获取配置信息
	3、连接池及装饰者模式
	4、DBCP与C3P0
	5、使用dbutils完成curd操作
	6、QueryRunner、DbUtils、ResultSetHandler
	
12、xml与tomcat相关
	1、xml(包括书写规范等)及其组成部分(声明、元素、属性、注释、CDATA)
	2、xml解析
	3、xml(DTD约束、SCHEMA约束)
	4、tomcat与其目录结构
	5、web项目的目录结构及其项目发布方式
	
13、servlet相关
	1、request方式（请求行 请求头 请求体）、response方式（响应行 响应头 响应体）
	2、servlet概述、体系结构
	3、servlet常用方法、GenericServlet常用方法
	4、servlet生命周期 （init、service、destroy）
	5、ServletContext（全局管理者）
	6、域对象

14、Linux基本内容
	1、根目录下的各目录的基本意义
	
15、request和response
	1、response(操作响应行、操作响应头(setHeader、addHeader)、操作响应体(response.setContentType("text/html;charset=utf-8")))
	2、文件下载方式
	3、request(操作请求行、操作请求头(getHeader(String key))、操作请求参数(getParameterMap()))
	4、请求的中文乱码,对于post(request.setCharacterEncoding("utf-8")),域对象(request)
	5、请求转发和重定向区别

16、cookie与session
	1、JSP（概念、执行流程、JSP脚本）
	2、cookie：浏览器端会话技术
	3、session：服务器端会话技术