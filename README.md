# CDH-Platform-Practice-Guide
# CDH平台实战指南书
----
### 1.准备入门  
* 谈谈怎样入门大数据 
* 谈谈怎样做好一个大数据平台的运营工作 

### 2.介绍      
* Cloudera官网介绍
* 在企业中如何选择CDH版本
* CDH三种部署方式解读

### 3.企业真正离线部署及卸载
* 阿里云集群环境准备
* 集群初始化工作
* MySQL离线部署
* CM离线部署
* Parcel离线源部署
* 正式安装集群
* 如何卸载集群

### 4.CDH全面管理    
* CDH集群正确启动和停止顺序 
* CDH体系架构梳理
* CDH配置文件深度解析 
* CM的常用命令 
* 生产上如何定位log及错误
* CDH Web界面解读 
* CDH Tsquery Language及监控

### 5.CDH维护操作  
* HDFS HA 配置 及hadoop/hdfs常规命令 
* Yarn HA 配置 及yarn常规命令 
* Other CDH Components HA 配置 
* CDH添加删除服务(hive/hbase)
* CDH添加删除机器 
* CDH升级(5.12.0-->5.16.1) 
* 如何自定义parcel部署Kafka及Console案例
* 如何自定义parcel部署Spark2及生产上Spark job on Yarn案例

### 6.CDH资源管理  
* Linux Cgroups 
* 静态资源池 
* 动态资源池 
* 多租户案例 

### 7.集群调优    
* Memory/CPU/Network/Disk及集群规划 
* Linux参数 
* HDFS参数 
* MapReduce及Yarn参数 
* 其他服务参数 

### 8.案例分享
* CDH4&5之Alternatives命令 的研究 
* CDH5.8.2安装之Hash verification failed 
* 记录一次CDH4.8.6 配置HDFS HA 坑 
* CDH5.x集群IP更改 
* CDH5.x集群启用iptables防火墙规则
* CDH的active namenode exit(GC)和彩蛋分享 
* HBase生产中如何维护

### 9.CDH Kerberos
* Kerberos简介
* Kerberos体系结构
* Kerberos工作机制
* Kerberos安装部署
* CDH启用kerberos

### 10.生产如何玩转Kerberos
* Phoenix官网解读
* Phoenix定制化
* HBase集成Phoenix
* DBeaver连接Phoenix对HBase操作
* IDEA开发Java操作Kerberos HBase 
* 如何做HBase kerberos+ACL 用户权限控制及代码集成
* Spark 如何提交job到Kerberos Yarn平台
* Spark 如何操作Kerberos HBase

### 11.Summary         
* 课程总结
* 未来我们应该如何学

-------------
#### PS:Blog&Video
* [早年的CDH Blog](http://blog.itpub.net/30089851/cid-179475-abstract-1/)
* Tar部署--[CDH5.16.1企业集群真正离线部署(全网最细，配套视频和文档安装包，生产可实践](https://www.bilibili.com/video/av52167219?from=search&seid=17801304070861960646)
* Rpm部署--[全网最详细的CDH5.8.2离线安装](https://www.bilibili.com/video/av30031910?from=search&seid=17377111964874052140)
* [Hadoop集群调优&CDH常规管理](https://www.bilibili.com/video/av34829124?from=search&seid=5997611269097610423)
