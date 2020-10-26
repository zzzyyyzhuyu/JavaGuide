👍推荐 [在线阅读](https://snailclimb.gitee.io/javaguide)  (Github 访问速度比较慢可能会导致部分图片无法刷新出来) 

👍 图解操作系统+HTTP+计算机网络的 PDF 资料[点此链接即可下载](https://cowtransfer.com/s/fbed14f0c22a4d)。

## 一些闲话：

> 1. **介绍**：关于 JavaGuide 的相关介绍请看：[关于 JavaGuide 的一些说明](https://www.yuque.com/snailclimb/dr6cvl/mr44yt#vu3ok) 。PDF 版本请看：[完结撒花！JavaGuide 面试突击版来啦！](./docs/javaguide面试突击版.md) 。
>2. **PDF版本** ： [《JavaGuide 面试突击版》PDF 版本](#公众号) 。
> 3. **面试专版** ：准备面试的小伙伴可以考虑面试专版：[《Java 面试进阶指南》](https://xiaozhuanlan.com/javainterview?rel=javaguide) ，欢迎加入[我的星球](https://wx.zsxq.com/dweb2/index/group/48418884588288)获取更多实用干货。
> 4. **阿里云活动** ：阿里云最近在做活动，服务器不到 10 元/月，小伙伴们搭建一个网站提高简历质量。支持国内开源做的比较好的公司！[点击此链接直达活动首页。](https://promotion.aliyun.com/ntms/yunparter/invite.html?userCode=hf47liqn)
> 5. **联系我** ：如要进群或者请教问题，请[联系我](#联系我) （备注来自 Github。请直入问题，工作时间不回复）。
> 6. **转载须知** ：以下所有文章如非文首说明皆为我（Guide哥）的原创，转载在文首注明出处，如发现恶意抄袭/搬运，会动用法律武器维护自己的权益。让我们一起维护一个良好的技术创作环境！⛽️

<p align="center">
<a href="https://github.com/Snailclimb/JavaGuide" target="_blank">
	<img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-3/logo - 副本.png" width=""/>
</a>
</p>

<p align="center">
  <a href="https://snailclimb.gitee.io/javaguide"><img src="https://img.shields.io/badge/阅读-read-brightgreen.svg" alt="阅读"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-JavaGuide-lightgrey.svg" alt="公众号"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/PDF-Java面试突击-important.svg" alt="公众号"></a>
  <a href="#投稿"><img src="https://img.shields.io/badge/support-投稿-critical.svg" alt="投稿"></a>
  <a href="https://xiaozhuanlan.com/javainterview?rel=javaguide"><img src="https://img.shields.io/badge/Java-面试指南-important" alt="投稿"></a>
</p>

<h3 align="center">Sponsor</h3>

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://t.1yb.co/5p8J">
          <img src="./media/sponsor/xiangxue.png" style="margin: 0 auto;width:450px" /></a>
      </td>  
       <td align="center" valign="middle">
        <a href="https://w.url.cn/s/AS6JeXA">
          <img src="./media/sponsor/kaikeba.png" style="margin: 0 auto;width:450px" /></a>
      </td>       
    </tr>
  </tbody>
</table>


<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Java](#java)
  - [基础](#基础)
  - [容器](#容器)
  - [并发](#并发)
  - [JVM (必看 :+1:)](#jvm-必看-1)
  - [新特性](#新特性)
- [网络](#网络)
- [操作系统](#操作系统)
- [数据结构与算法](#数据结构与算法)
  - [数据结构](#数据结构)
  - [算法](#算法)
- [数据库](#数据库)
  - [MySQL](#mysql)
  - [Redis](#redis)
- [系统设计](#系统设计)
  - [编码之道(必看 :+1:)](#编码之道必看-1)
  - [常用框架](#常用框架)
    - [Spring/SpringBoot](#springspringboot)
    - [MyBatis](#mybatis)
    - [Netty (必看 :+1:)](#netty-必看-1)
  - [认证授权](#认证授权)
    - [JWT](#jwt)
    - [SSO(单点登录)](#sso单点登录)
  - [分布式](#分布式)
    - [搜索引擎](#搜索引擎)
    - [RPC](#rpc)
    - [API 网关](#api-网关)
    - [分布式 id](#分布式-id)
    - [ZooKeeper](#zookeeper)
  - [微服务](#微服务)
  - [高并发](#高并发)
    - [消息队列](#消息队列)
    - [读写分离](#读写分离)
    - [分库分表](#分库分表)
    - [负载均衡](#负载均衡)
  - [高可用](#高可用)
    - [CAP 理论](#cap-理论)
    - [BASE 理论](#base-理论)
    - [限流](#限流)
    - [降级](#降级)
    - [熔断](#熔断)
    - [排队](#排队)
  - [大型网站架构](#大型网站架构)
- [工具](#工具)
- [面试指南](#面试指南)
- [Java 学习常见问题汇总](#java-学习常见问题汇总)
- [书单](#书单)
- [其他](#其他)
  - [待办](#待办)
  - [联系我](#联系我)
  - [捐赠支持](#捐赠支持)
  - [Contributor](#contributor)
  - [公众号](#公众号)

<!-- /code_chunk_output -->


## Java

### 基础

**知识点/面试题:**(必看:+1: )

1. **[Java 基础知识](docs/java/basis/Java基础知识.md)**
2. **[Java 基础知识疑难点/易错点](docs/java/basis/Java基础知识疑难点.md)**

**重要知识点详解：**

1. [枚举](docs/java/basis/用好Java中的枚举真的没有那么简单.md) （很重要的一个数据结构，用好枚举真的没有那么简单！）
2. [Java 常见关键字总结：final、static、this、super!](docs/java/basis/Java常见关键字总结.md)
3. [什么是反射机制?反射机制的应用场景有哪些?](docs/java/basis/反射机制.md)
4. [代理模式详解：静态代理+JDK/CGLIB 动态代理实战](docs/java/basis/代理模式详解.md)
5. [BIO,NIO,AIO 总结 ](docs/java/basis/BIO,NIO,AIO总结.md)

### 容器

1. **[Java 容器常见面试题/知识点总结](docs/java/collection/Java集合框架常见面试题.md)** (必看 :+1:)
2. **源码分析** ：[ArrayList 源码+扩容机制分析](docs/java/collection/ArrayList源码+扩容机制分析.md) 、[LinkedList 源码](docs/java/collection/LinkedList源码分析.md) 、[HashMap(JDK1.8)源码+底层数据结构分析](<docs/java/collection/HashMap(JDK1.8)源码+底层数据结构分析.md>) 、[ConcurrentHashMap 源码+底层数据结构分析](docs/java/collection/ConcurrentHashMap源码+底层数据结构分析.md)

### 并发

并发这部分内容非常重要，还是面试中的重点中的重点！但是，学习起来难度较大，因此我写了：**[多线程学习指南](./docs/java/multi-thread/多线程学习指南.md)** 帮助你学习。

**知识点/面试题:** (必看 :+1:)

1. **[Java 并发基础常见面试题总结](docs/java/multi-thread/2020最新Java并发基础常见面试题总结.md)**
2. **[Java 并发进阶常见面试题总结](docs/java/multi-thread/2020最新Java并发进阶常见面试题总结.md)**

**重要知识点详解：**

2. **线程池**：[Java 线程池学习总结](./docs/java/multi-thread/java线程池学习总结.md)、[拿来即用的线程池最佳实践](./docs/java/multi-thread/拿来即用的线程池最佳实践.md)
3. [乐观锁与悲观锁](docs/essential-content-for-interview/面试必备之乐观锁与悲观锁.md)
4. [ ThreadLocal 关键字解析](docs/java/multi-thread/万字详解ThreadLocal关键字.md)
5. [并发容器总结](docs/java/multi-thread/并发容器总结.md)
6. [JUC 中的 Atomic 原子类总结](docs/java/multi-thread/Atomic原子类总结.md)
7. [AQS 原理以及 AQS 同步组件总结](docs/java/multi-thread/AQS原理以及AQS同步组件总结.md)

### JVM (必看 :+1:)

1. **[Java 内存区域](docs/java/jvm/Java内存区域.md)**
2. **[JVM 垃圾回收](docs/java/jvm/JVM垃圾回收.md)**
3. [JDK 监控和故障处理工具](docs/java/jvm/JDK监控和故障处理工具总结.md)
4. [类文件结构](docs/java/jvm/类文件结构.md)
5. **[类加载过程](docs/java/jvm/类加载过程.md)**
6. [类加载器](docs/java/jvm/类加载器.md)
7. **[【待完成】最重要的 JVM 参数指南（翻译完善了一半）](docs/java/jvm/最重要的JVM参数指南.md)**
8. [JVM 配置常用参数和常用 GC 调优策略](docs/java/jvm/GC调优参数.md)
9. **[【加餐】大白话带你认识 JVM](docs/java/jvm/[加餐]大白话带你认识JVM.md)**

### 新特性

1.  **Java 8** ：[Java 8 新特性总结](docs/java/new-features/Java8新特性总结.md)、[Java 8 学习资源推荐](docs/java/new-features/Java8教程推荐.md)、[Java8 forEach 指南](docs/java/new-features/Java8foreach指南.md)
2.  **Java9~Java14** : [一文带你看遍 JDK9~14 的重要新特性！](./docs/java/new-features/一文带你看遍JDK9到14的重要新特性.md)

## 网络

1. [计算机网络常见面试题](docs/network/计算机网络.md)
2. [计算机网络基础知识总结](docs/network/计算机网络知识总结.md)

## 操作系统

1. [操作系统常见问题总结！](docs/operating-system/basis.md)
2. [后端程序员必备的 Linux 基础知识](docs/operating-system/linux.md)
3. [Shell 编程入门](docs/operating-system/Shell.md)

## 数据结构与算法

### 数据结构

1. [不了解布隆过滤器？一文给你整的明明白白！](docs/dataStructures-algorithms/data-structure/bloom-filter.md)
2. [数据结构知识学习与面试](docs/dataStructures-algorithms/数据结构.md)

### 算法

算法这部分内容非常重要，如果你不知道如何学习算法的话，可以看下我写的：[《硬核的算法学习书籍+资源推荐》](docs/dataStructures-algorithms/算法学习资源推荐.md) 。

**常见算法问题总结：**

- [几道常见的字符串算法题总结 ](docs/dataStructures-algorithms/几道常见的子符串算法题.md)
- [几道常见的链表算法题总结 ](docs/dataStructures-algorithms/几道常见的链表算法题.md)
- [剑指 offer 部分编程题](docs/dataStructures-algorithms/剑指offer部分编程题.md)

## 数据库

### MySQL

**总结：**

1. **[【推荐】MySQL/数据库 知识点总结](docs/database/MySQL.md)**
2. **[阿里巴巴开发手册数据库部分的一些最佳实践](docs/database/阿里巴巴开发手册数据库部分的一些最佳实践.md)**
3. **[一千行 MySQL 学习笔记](docs/database/一千行MySQL命令.md)**
4. [MySQL 高性能优化规范建议](docs/database/MySQL高性能优化规范建议.md)

**重要知识点：**

1. [数据库索引总结 1](docs/database/MySQL%20Index.md)、[数据库索引总结 2](docs/database/数据库索引.md)
2. [事务隔离级别(图文详解)](<docs/database/事务隔离级别(图文详解).md>)
3. [一条 SQL 语句在 MySQL 中如何执行的](docs/database/一条sql语句在mysql中如何执行的.md)
4. **[关于数据库中如何存储时间的一点思考](docs/database/关于数据库存储时间的一点思考.md)**

### Redis

1. [关于缓存的一些重要概念(Redis 前置菜)](docs/database/Redis/some-concepts-of-caching.md)
2. [Redis 常见问题总结](docs/database/Redis/redis-all.md)

## 系统设计

### 编码之道(必看 :+1:)

1. [RestFul API 简明教程](docs/system-design/coding-way/RESTfulAPI简明教程.md)
2. [Java 编程规范以及优雅 Java 代码实践总结](docs/java/Java编程规范.md)
3. [Java 命名之道](docs/system-design/naming.md)

### 常用框架

如果你没有接触过 Java Web 开发的话，可以先看一下我总结的 [《J2EE 基础知识》](docs/java/J2EE基础知识.md) 。虽然，这篇文章中的很多内容已经淘汰，但是可以让你对 Java 后台技术发展有更深的认识。

#### Spring/SpringBoot (必看 :+1:)

**知识点/面试题:** 

1. **[Spring 常见问题总结](docs/system-design/framework/spring/Spring常见问题总结.md)**
2. **[SpringBoot 指南/常见面试题总结](https://github.com/Snailclimb/springboot-guide)**

**重要知识点详解：**

1. **[Spring/Spring 常用注解总结！安排！](./docs/system-design/framework/spring/SpringBoot+Spring常用注解总结.md)** 
2. **[Spring 事务总结](docs/system-design/framework/spring/Spring事务总结.md)** 
3. [Spring 中都用到了那些设计模式?](docs/system-design/framework/spring/Spring-Design-Patterns.md)

#### MyBatis

- [MyBatis 常见面试题总结](docs/system-design/framework/mybatis/mybatis-interview.md)

#### Netty (必看 :+1:)

1. [剖析面试最常见问题之 Netty（上）](https://xiaozhuanlan.com/topic/4028536971)
2. [剖析面试最常见问题之 Netty（下）](https://xiaozhuanlan.com/topic/3985146207)

### 认证授权

**[《认证授权基础》](docs/system-design/authority-certification/basis-of-authority-certification.md)** 这篇文章中我会介绍认证授权常见概念： **Authentication**,**Authorization** 以及 **Cookie**、**Session**、Token、**OAuth 2**、**SSO** 。如果你不清楚这些概念的话，建议好好阅读一下这篇文章。

#### JWT

1. [JWT 优缺点分析以及常见问题解决方案](docs/system-design/authority-certification/JWT优缺点分析以及常见问题解决方案.md)
2. [适合初学者入门 Spring Security With JWT 的 Demo](https://github.com/Snailclimb/spring-security-jwt-guide)

#### SSO(单点登录)

**SSO(Single Sign On)** 即单点登录说的是用户登陆多个子系统的其中一个就有权访问与其相关的其他系统。举个例子我们在登陆了京东金融之后，我们同时也成功登陆京东的京东超市、京东家电等子系统。相关阅读：**[SSO 单点登录看这篇就够了！](docs/system-design/authority-certification/SSO单点登录看这一篇就够了.md)**

### 分布式

[分布式相关概念入门](docs/system-design/distributed-system/分布式.md)

#### 搜索引擎

用于提高搜索效率，功能和浏览器搜索引擎类似。比较常见的搜索引擎是 Elasticsearch（推荐） 和 Solr。

#### RPC

RPC 让调用远程服务调用像调用本地方法那样简单。

1. [Dubbo 总结：关于 Dubbo 的重要知识点](docs/system-design/distributed-system/rpc/关于Dubbo的重要知识点.md)
2. [服务之间的调用为啥不直接用 HTTP 而用 RPC？](docs/system-design/distributed-system/rpc/服务之间的调用为啥不直接用HTTP而用RPC.md)

#### API 网关

网关主要用于请求转发、安全认证、协议转换、容灾。

1. [为什么要网关？你知道有哪些常见的网关系统？](docs/system-design/distributed-system/api-gateway/为什么要网站有哪些常见的网站系统.md)
2. [如何设计一个亿级网关(API Gateway)？](docs/system-design/distributed-system/api-gateway/如何设计一个亿级网关.md)

#### 分布式 id

在复杂分布式系统中，往往需要对大量的数据和消息进行唯一标识。比如数据量太大之后，往往需要对进行对数据进行分库分表，分库分表后需要有一个唯一 ID 来标识一条数据或消息，数据库的自增 ID 显然不能满足需求。相关阅读：[为什么要分布式 id ？分布式 id 生成方案有哪些？](docs/system-design/micro-service/分布式id生成方案总结.md)

#### ZooKeeper

> 前两篇文章可能有内容重合部分，推荐都看一遍。

1. [【入门】ZooKeeper 相关概念总结](docs/system-design/distributed-system/zookeeper/zookeeper-intro.md)
2. [【进阶】ZooKeeper 相关概念总结](docs/system-design/distributed-system/zookeeper/zookeeper-plus.md)
3. [【实战】ZooKeeper 实战](docs/system-design/distributed-system/zookeeper/zookeeper-in-action.md)

### 微服务

1. [ 大白话入门 Spring Cloud](docs/system-design/micro-service/spring-cloud.md)
2. [微服务/分布式大厂真实面试问题解答](https://xiaozhuanlan.com/topic/2895047136)

### 高并发

#### 消息队列

消息队列在分布式系统中主要是为了解耦和削峰。相关阅读： **[消息队列总结](docs/system-design/data-communication/message-queue.md)** 。

1. **RabbitMQ** : [RabbitMQ 入门](docs/system-design/distributed-system/message-queue/RabbitMQ入门看这一篇就够了.md)
2. **RocketMQ** : [RocketMQ 入门](docs/system-design/distributed-system/message-queue/RocketMQ.md)、[RocketMQ 的几个简单问题与答案](docs/system-design/distributed-system/message-queue/RocketMQ-Questions.md)
3. **Kafka** ：**[Kafka 常见面试题总结](docs/system-design/distributed-system/message-queue/Kafka常见面试题总结.md)**

#### 读写分离

读写分离主要是为了将数据库的读和写操作分不到不同的数据库节点上。主服务器负责写，从服务器负责读。另外，一主一从或者一主多从都可以。

**读写分离可以大幅提高读性能，小幅提高写的性能。因此，读写分离更适合单机并发读请求比较多的场景。**

#### 分库分表

**分库分表是为了解决由于库、表数据量过大，而导致数据库性能持续下降的问题。** 常见的分库分表工具有：`sharding-jdbc`（当当）、`TSharding`（蘑菇街）、`MyCAT`（基于 Cobar）、`Cobar`（阿里巴巴）...。

**推荐使用 `sharding-jdbc`** 。 因为，`sharding-jdbc` 是一款轻量级 `Java` 框架，以 `jar` 包形式提供服务，不要我们做额外的运维工作，并且兼容性也很好。

#### 负载均衡

负载均衡系统通常用于将任务比如用户请求处理分配到多个服务器处理以提高网站、应用或者数据库的性能和可靠性。

常见的负载均衡系统包括 3 种：

1. **DNS 负载均衡** ：一般用来实现地理级别的均衡。
2. **硬件负载均衡** ： 通过单独的硬件设备比如 F5 来实现负载均衡功能（硬件的价格一般很贵）。
3. **软件负载均衡** ：通过负载均衡软件比如 Nginx 来实现负载均衡功能。

### 高可用

高可用描述的是一个系统在大部分时间都是可用的，可以为我们提供服务的。高可用代表系统即使在发生硬件故障或者系统升级的时候，服务仍然是可用的 。

相关阅读： **《[如何设计一个高可用系统？要考虑哪些地方？](docs/system-design/high-availability/如何设计一个高可用系统要考虑哪些地方.md)》** 。

#### CAP 理论

CAP 也就是 Consistency（一致性）、Availability（可用性）、Partition Tolerance（分区容错性） 这三个单词首字母组合。

关于 CAP 的详细解读请看：[《CAP理论解读》](docs/system-design/high-availability/CAP理论.md)。

#### BASE 理论

**BASE** 是 **Basically Available（基本可用）** 、**Soft-state（软状态）** 和 **Eventually Consistent（最终一致性）** 三个短语的缩写。BASE 理论是对 CAP 中一致性和可用性权衡的结果，其来源于对大规模互联网系统分布式实践的总结，是基于 CAP 定理逐步演化而来的，它大大降低了我们对系统的要求。

关于 CAP 的详细解读请看：[《BASE理论解读》](docs/system-design/high-availability/BASE理论.md)。

#### 限流

限流是从用户访问压力的角度来考虑如何应对系统故障。

限流为了对服务端的接口接受请求的频率进行限制，防止服务挂掉。比如某一接口的请求限制为 100 个每秒, 对超过限制的请求放弃处理或者放到队列中等待处理。限流可以有效应对突发请求过多。相关阅读：[限流算法有哪些？](docs/system-design/high-availability/limit-request.md)

#### 降级

降级是从系统功能优先级的角度考虑如何应对系统故障。

服务降级指的是当服务器压力剧增的情况下，根据当前业务情况及流量对一些服务和页面有策略的降级，以此释放服务器资源以保证核心任务的正常运行。

#### 熔断

熔断和降级是两个比较容易混淆的概念，两者的含义并不相同。

降级的目的在于应对系统自身的故障，而熔断的目的在于应对当前系统依赖的外部系统或者第三方系统的故障。

#### 排队

另类的一种限流，类比于现实世界的排队。玩过英雄联盟的小伙伴应该有体会，每次一有活动，就要经历一波排队才能进入游戏。

#### 集群

相同的服务部署多份，避免单点故障。

#### 超时和重试机制

**一旦用户的请求超过某个时间得不到响应就结束此次请求并抛出异常。** 如果不进行超时设置可能会导致请求响应速度慢，甚至导致请求堆积进而让系统无法在处理请求。

另外，重试的次数一般设为 3 次，再多次的重试没有好处，反而会加重服务器压力（部分场景使用失败重试机制会不太适合）。

### 大型网站架构

- [8 张图读懂大型网站技术架构](docs/system-design/website-architecture/8%20张图读懂大型网站技术架构.md)
- [关于大型网站系统架构你不得不懂的 10 个问题](docs/system-design/website-architecture/关于大型网站系统架构你不得不懂的10个问题.md)

## 工具

1. **Java** ：[JAD 反编译](docs/java/JAD反编译tricks.md)、[手把手教你定位常见 Java 性能问题](./docs/java/手把手教你定位常见Java性能问题.md)
2. **Git** ：[Git 入门](docs/tools/Git.md)
3. **Docker** : [Docker 基本概念解读](docs/tools/Docker.md) 、[一文搞懂 Docker 镜像的常用操作！](docs/tools/Docker-Image.md)

## 面试指南

> 这部分很多内容比如大厂面经、真实面经分析被移除，详见[完结撒花！JavaGuide 面试突击版来啦！](./docs/javaguide面试突击版.md)。

1. **[【备战面试 1】程序员的简历就该这样写](docs/essential-content-for-interview/PreparingForInterview/程序员的简历之道.md)**
2. **[【备战面试 2】初出茅庐的程序员该如何准备面试？](docs/essential-content-for-interview/PreparingForInterview/interviewPrepare.md)**
3. **[【备战面试 3】7 个大部分程序员在面试前很关心的问题](docs/essential-content-for-interview/PreparingForInterview/JavaProgrammerNeedKnow.md)**
4. **[【备战面试 4】Github 上开源的 Java 面试/学习相关的仓库推荐](docs/essential-content-for-interview/PreparingForInterview/JavaInterviewLibrary.md)**
5. **[【备战面试 5】如果面试官问你“你有什么问题问我吗？”时，你该如何回答](docs/essential-content-for-interview/PreparingForInterview/面试官-你有什么问题要问我.md)**
6. [【备战面试 6】应届生面试最爱问的几道 Java 基础问题](docs/essential-content-for-interview/PreparingForInterview/应届生面试最爱问的几道Java基础问题.md)
7. **[【备战面试 6】美团面试常见问题总结(附详解答案)](docs/essential-content-for-interview/PreparingForInterview/美团面试常见问题总结.md)**

## Java 学习常见问题汇总

1. [Java 学习路线和方法推荐](docs/questions/java-learning-path-and-methods.md)
2. [Java 培训四个月能学会吗？](docs/questions/java-training-4-month.md)
3. [新手学习 Java，有哪些 Java 相关的博客，专栏，和技术学习网站推荐？](docs/questions/java-learning-website-blog.md)
4. [Java 还是大数据，你需要了解这些东西！](docs/questions/java-big-data.md)

## 书单

1. [「基础篇」Java 书单](./docs/books/java基础篇.md)

---

## 其他

### 贡献者

[你可以点此链接查看JavaGuide的所有贡献者。](https://github.com/Snailclimb/JavaGuide/graphs/contributors) 感谢你们让 JavaGuide 变得更好！如果你们来到武汉一定要找我，我请你们吃饭玩耍。

*悄悄话：JavaGuide 会不定时为贡献者们送福利。*

### 待办

- [x] Netty 总结
- [ ] 数据结构总结重构
- [ ] 将 JavaGuide 的基础知识部分抽出来单独弄一个 CS-Guide

### 联系我

![个人微信](https://cdn.jsdelivr.net/gh/javaguide-tech/blog-images/2020-08/wechat3.jpeg)

### 捐赠支持

项目的发展离不开你的支持，如果 JavaGuide 帮助到了你找到自己满意的 offer，请作者喝杯咖啡吧 ☕ 后续会继续完善更新！加油！

[点击捐赠支持作者](https://www.yuque.com/snailclimb/dr6cvl/mr44yt#vu3ok)


### 公众号

如果大家想要实时关注我更新的文章以及分享的干货的话，可以关注我的公众号。

**《Java 面试突击》:** 由本文档衍生的专为面试而生的《Java 面试突击》V3.0 PDF 版本[公众号](#公众号)后台回复 **"面试突击"** 即可免费领取！

![我的公众号](https://cdn.jsdelivr.net/gh/javaguide-tech/blog-images/2020-08/167598cd2e17b8ec.png)

