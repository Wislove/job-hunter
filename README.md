# job-hunter

>9年Java Coder的求职总结以及一些八股文的总结，主要针对面试，在工作中遇到的，可能出现在面试中的，都做一个简单总结

仓库时间线：

2025-04-14 初次创建

当前状态：

2025-04 在职，寻找机会中


# 目录

## 面试准备

#### [个人简历（更新至2025-04-02）](resume/resume.md)
#### [面试来临时的准备](tongyong.md)
#### [自我介绍](tongyong.md)
#### [问面试官的问题](tongyong.md)
#### [模拟面试](#模拟面试)


## Java八股文

### [Spring相关问题](spring/springboot.md)
- [SpringBoot启动原理，会做哪些事情](spring/springboot.md)
- [SpringBoot启动慢，该如何优化](spring/springboot.md)
- Spring的Bean加载过程，Bean初始化过程
- Spring Bean为什么默认单例模式？什么场景会使用到非单例模式？
- Spring中用到的设计模式和实际例子
- Spring IOC的原理和实现逻辑
- Spring APO的实现原理， 动态代理和静态代理的区别，实际例子
- Spring 声明式事务的传播和失效
- Spring 如何解决循环依赖
- Spring 相较使用的比较少的注解: @PostConstruct, @PreDestroy
- Spring Boot应用运行一段时间，内存占用越来越高，响应越来越慢，该如何优化，谈谈思路（内存泄漏）
- Spring Boot应用启动一段时候，自动exit退出，可能是哪些原因，谈谈思路（容器退出，JVM退出）
### Java相关
- [JVM内存模型和GC](java/jvm_gc.md)
- [实战-线上OOM排查](java/java.md)
- [实战-JVM调优实例](java/java.md)
- Java的双亲委派模型，如何破坏双亲委派

### Mysql
- [Mysql存储引擎,MyISAM和InnoDB](db/mysql.md)
- [Mysql索引，索引数据结构](db/mysql.md)
- [Mysql的日志binlog，redo log，undo log相关问题](db/mysql.md)
- [Mysql的事务，ACID，隔离级别，脏读幻读，MVCC](db/mysql.md)
- [Mysql的锁，锁类型，行锁表锁，共享排他，乐观锁等](db/mysql.md)
- [Mysql死锁如何排查，如何避免死锁](db/mysql.md)
#### Mysql性能优化
- [Mysql性能优化:索引，表结构，SQL优化](db/mysql.md)
- [Mysql执行计划EXPLAIN的分析](db/mysql.md)
- [Mysql读写分离，主从复制，分库分表实现方案](db/mysql.md)
### Redis
- [Redis的数据结构，高频问题](cache/redis.md)
- [Redis实现限流，限流算法和方案](cache/redis.md)
- [Redis实现分布式锁](cache/redis.md)
- [Redis事务](cache/redis.md)
- [Redis缓存读写策略，以及如何选择](cache/redis.md)
- [Redis集群Cluster和Sentinel](cache/redis.md)

### 其他中间件
#### 消息队列Kafka，RocketMQ
- RocketMQ顺序支持较好，支持事务消息，定时消息，消息过滤（kafka使用kafka stream）,支持服务端触发重新发送
- Kafka的顺序是通过partition支持的，一个partition里面是顺序性

#### Nginx相关

#### EleasticSearch



### 系统设计相关
- 安全设计，常见加密算法：MD5,SHA,对称加密(AES,DES),非对称(RSA,DSA)
- 敏感词过滤的方案，用户输入敏感词，如果过滤
- 数据脱敏处理方案：存储脱敏，查询返回脱敏的方案
- 使用Websocket和SSE实现Web消息推送
- 使用MQTT实现Web消息推送(没想到MQTT也可以吧)

### 分布式
- 分布式基础算法：Paxos，Raft
- [分布式CAP，BASE理论及分布式事务以及实现方案](https://developer.aliyun.com/article/1460045)
- 分布式锁以及实现方案
- 分布式配置中心
- 分布式协议：HTTP和RPC
#### 高可用
- 高可用架构：集群，限流，熔断，超时重试，异步，缓存，消息队列，幂等
- 如何实现幂等，接口幂等的方案
- 服务限流实现方案，redis限流，zookeeper限流，sentinel限流，Hystrix限流，限流算法，限流方案
#### 高性能
- 高性能： CDN代理，负载均衡，读写分离，主从复制，分库分表，缓存，冷热分离，SQL优化，消息队列削峰，解耦
- 常见的负载均衡算法，客户端负载和服务端负载
- Nginx实现负载均衡的方案
- 读写分离如何实现

## 模拟面试
- [DeepSeek](https://www.deepseek.com/)
- [豆包](https://www.doubao.com/chat/)

## 面试记录





