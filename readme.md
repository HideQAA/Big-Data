# 大数据学习路线 #
---
![](http://images.gitbook.cn/a8ea12c0-ad9e-11e7-bc4e-bd9737349028)


### 必须掌握的技能 ###
1. Java高级（虚拟机、并发）		
   
   多线程、并发包下的队列、JMS、JVM技术、反射和动态代理


2. Linux基本操作
   
   操作系统介绍和安装、常用命令、常用软件安装、Linux网络、防火墙、Shell编程


3. Zookeeper学习
   
   分布式协调技术 主要用来解决分布式环境当中多个进程之间的同步控制，让他们有序的去访问某种临界资源，防止造成"脏数据"的后果 
   
   学习博客：<http://www.cnblogs.com/wuxl360/p/5817471.html>


4. Hadoop（HDFS+MapReduce+Yarn）《Hadoop权威指南》
   
   HDFS:概念和特性、shell操作、工作机制、Java应用开发
   
   MapReduce和Java应用开发


5. Hive 《Hive开发指南》
   
   Hive是建立在Hadoop上的数据仓库基础构架。它提供了一系列的工具，可以用来进行数据提取转化加载（ETL），这是一种可以存储、查询和分析存储在Hadoop中的大规模数据的机制。
   
   Hive基本概念、基本操作、执行过程分析及优化策略
   
   学习文档：<http://www.aboutyun.com/thread-11873-1-1.html> 


6. Hbase 《Hbase权威指南》
   
   HBase– Hadoop Database，是一个高可靠性、高性能、面向列、可伸缩的分布式存储系统
   Hbase简介、安装、数据模型、命令、开发、原理


7. Scala 《快学Scala》
   
   Scala 是一门多范式（multi-paradigm）的编程语言，设计初衷是要集成面向对象编程和函数式编程的各种特性
   
   学习网站：<http://www.runoob.com/scala/scala-tutorial.html>


8. Spark 《Spark权威指南》
   
   **Spark Core**
   ![](http://images.gitbook.cn/e3202560-adda-11e7-8d75-f14e65a1bc39) 
    
   **RDD**
   ![](http://images.gitbook.cn/02ffd320-addc-11e7-9923-17951b2031c1)
   
   **Spark SQL and DataFrame/DataSet**
   ![](http://images.gitbook.cn/9e06fa70-addb-11e7-9923-17951b2031c1)

   **Spark Streaming**
   ![](http://images.gitbook.cn/4c92ed70-addb-11e7-8d75-f14e65a1bc39)
   ![](http://images.gitbook.cn/54bdafd0-addb-11e7-9923-17951b2031c1)


9. Python


10. 用虚拟机搭建一个集群，把所有工具都装上，自己开发一个小demo
    
    参考 https://blog.csdn.net/zl1zl2zl3/article/details/78372323


11. Sqoop
    
    Sqoop是一个开源的工具，它允许用户将数据从关系型数据库抽取到hadoop中，也可以把MapReduce处理完的数据导回到数据库中
    
    ![](http://images.gitbook.cn/73425e40-add8-11e7-b8aa-23aafd675e29)
    
    学习博客：http://student-lp.iteye.com/blog/2157983


12. Flume
    
    flume是一个分布式、可靠、和高可用的海量日志采集、聚合和传输的系统。支持在日志系统中定制各类数据发送方，用于收集数据;同时，Flume提供对数据进行简单处理，并写到各种数据接受方(比如文本、HDFS、Hbase等)的能力
    
    学习博客：http://www.aboutyun.com/thread-8917-1-1.html


13. Oozie
    
    Oozie是一种Java Web应用程序，它运行在Java servlet容器（即Tomcat）中，并使用数据库来存储以下内容：工作流定义、当前运行的工作流实例，包括实例的状态和变量
    
    学习博客：http://www.infoq.com/cn/articles/introductionOozie 


14. Hue
    
    使用Hue我们可以在浏览器端的Web控制台上与Hadoop集群进行交互来分析处理数据
    
    学习博客：http://ju.outofmemory.cn/entry/105162

             


              

              参考文章：<https://blog.csdn.net/zl1zl2zl3/article/details/78372323> 