## 技术栈展示

- 先列举一下我们**日常工作开发的技术栈**，先感受一下，下面会规划的。

|                            技术栈                            | 是否重点 |
| :----------------------------------------------------------: | -------- |
|                           **基础**                           |          |
|      1.java流程控制之循环结构-----for循环以及while循环       |          |
|                          2.Java数组                          |          |
|                      3.面向对象三大特性                      |          |
|                          4.Java异常                          |          |
|     5.Java字符串---string类、stringBuffer、StringBuild类     |          |
|                   6.Java集合List、Map集合                    | 是       |
|                          7.Java泛型                          |          |
|                         8.Java多线程                         |          |
|                           9.JavaIO                           |          |
|                                                              |          |
|                           **高级**                           |          |
|        10.java8新特性 lambda表达式，配合List和Map使用        | 是       |
|                         11.Maven仓库                         | 是       |
|                      12.git版本控制管理                      | 是       |
|               13.JSON使用，推荐阿里的FastJSON                | 是       |
|     14.正则表达式（知道怎么回事就行，一般都是网上现找）      |          |
|                         15.Java反射                          |          |
|           16.MySQL(能掌握多表查询即可，比如左查询)           | 是       |
|                                                              |          |
|                                                              |          |
|                           **框架**                           |          |
|                        17.Spring框架                         | 是       |
|                        18.Mybatis框架                        |          |
|                      19.springBoot框架                       | 是       |
|                     20.**spring cloud**                      | 是       |
|                                                              |          |
|                          **中间件**                          |          |
|                           21.Redis                           | 是       |
| 22.消息中间件(比如**RabbitMQ**，RockerMQ，kafka）可以学个最简单的RabbitMQ | 是       |



--------------



再列举一下**面试常问造火箭**技术栈

- JVM
  - JVM内存构成
  - JVM垃圾回收算法
  - JVM垃圾回收器
- 集合类
  - HashMap底层原理
  - ConcurrentHashMap原理    
- 并发编程
  - Synchronized
  - volatile
  - LOCK接口
  - AQS
  - AQS实现类
  - Aotomic原子类
  - 线程&线程池
- mysql
  - 索引
  - B+树
  - sql优化
- redis
  - 数据结构
  - 应用场景
  - 缓存雪崩
  - 缓存穿透
  - 缓存积压
  - 持久化
- 消息中间件
  - 应用场景
  - 消息积压
  - 消息重复
  - 顺序消息
  - 分布式事务
- spring
  - IOC
  - AOP
  - 事务

- 分布式框架(spirng cloud)

-----------

======================**学习规划从这里开始**=================================

======================**学习规划从这里开始**=================================

======================**学习规划从这里开始**=================================

## 学习路径规划

### 基础(2天)

**直接看jdk8特性，前面的基础可以先不看了，等后面再说，不然一直在基础这里。**

下面列举的基础是比较**重要**的，**需要重点看，对应的代码需要敲出来，例举出来的也是需要看的，简单过一下就行，407集之后都不需要看，比如这些技术栈（IO，socket这个工作上用的很少，过一下就行，知道怎么回事就行了，不会影响下面的学习的），另外超过jdk8的新特性都不需要看。下面列举的都是**重点：


1. 基本语法(https://www.bilibili.com/video/BV18J411W7cE?p=1 -P98)
2. **面向对象**（https://www.bilibili.com/video/BV18J411W7cE?p=99    —P114）
3. 常用类、枚举 （https://www.bilibili.com/video/BV18J411W7cE?p=115   —P133）
5. **list**  (https://www.bilibili.com/video/BV18J411W7cE?p=134  — P149)
6. 面向对象三大特性、接口、抽象类(https://www.bilibili.com/video/BV18J411W7cE?p=150  — P188)
7. 异常 (https://www.bilibili.com/video/BV18J411W7cE?p=215 —P219)
8. 集合类(https://www.bilibili.com/video/BV18J411W7cE?p=220  —P268)

------------

**从这里开始看**，**如果上面忘了，可以回过头来看**

**从这里开始看**，**如果上面忘了，可以回过头来看**

**从这里开始看**，**如果上面忘了，可以回过头来看**



**JDK8新特性中的lambda表达式（替换视频里面的P355 —P394,直接看下面的视频就行了，p355-394就不用看了）**

- https://www.bilibili.com/video/BV14W411u7Ly
- 主要就是学习**集合类**的流操作，其他的不是很重要，**这个就是过一遍API就行了，知道怎么用就行了。**
- JAVA 8新特性(**一定要会**，工作上每天都用，方便快捷，每个增删改查都在用）
- JDK8笔记（https://shimo.im/docs/wWvvcHHvxJRq9hYK/ ）



- **idea的破解使用**：https://shimo.im/docs/hDWcxK9gjdvd98wH/ 《Idea 旗舰版使用指南》，可复制链接后用石墨文档 App 或小程序打开

-------------------

### IDEA版本断点DeBug调试(0.5天)

https://www.bilibili.com/video/BV1E3411k71R，这个还是比较重要的，会了代码调试可以解决很多问题。

---

### 算法

算法不是一天两天能快速提升的，可以每天刷个1-2题保持手感，是一个长期积累的过程。

**数据结构基础**：https://www.bilibili.com/video/BV1E4411H73v，这个就是算法入门。

如果感觉贪心，dp这些难以理解，可以看看《**牛客网算法视频**（**主要讲解刷题方法，视频讲的挺好的，基础学完可以看这个**）》和《**数据结构与算法之美**》

（链接：https://pan.baidu.com/s/1onKwLJSBDc8OcBIH1Syh6Q 提取码：9dcz ）

剑指offer必刷：https://leetcode-cn.com/problem-list/xb9nqhhg/

常见200题刷题路径https://github.com/JuiceZhou/Leetcode

热题100：https://leetcode-cn.com/problem-list/2cktkvj/

---

### 数据库(1天复习)

mysql: https://www.bilibili.com/video/BV1xW411u7ax   （**只需要看P1-P124，后面的都不需要看**)

------

### Servlet && JDBC(2天，仅仅了解)

这个比较简单，工作上早就不用这些技术了，可以看看博客了解一下就行，知道是怎么回事就好，最多敲一遍例子就行，仅仅**了解**，不要花费太多的时间。现在工作都是后面规划用的框架。

现在都是前后端分离的项目，工作上根本都不会写前端，项目里面也不会涉及到前端，所以jsp的东西不需要学习。

- servlet可以参考  https://www.bilibili.com/video/BV1Y7411K7zz  或者参考文档：https://www.liaoxuefeng.com/wiki/1252599548343744/1304265949708322（主要熟悉一下Servlet，知道原理，推荐看博客快速了解一下就行了）

- jdbc可以参考：https://www.bilibili.com/video/BV1eJ411c7rf 或者参考文档更快，https://www.liaoxuefeng.com/wiki/1252599548343744/1255943820274272

  后面学习的ORM(用java语言操作数据库的框架)框架都是依赖于JDBC技术的，所以了解一下就行了，工作上也不会用jdbc进行写代码了。

----

### 开发工具(1天)

仅仅作为日常开发的工具，就像**编译器**一样会用就好，日常必不可少的工具。

- Maven视频：https://www.bilibili.com/video/BV1e3411t7eB，对应笔记：https://shimo.im/docs/T9tJT6Vwg3x8hrDY/ 《Maven快速入门》

-------

### 数据传输(0.5天)

**fastjson**:https://www.bilibili.com/video/BV1y5411s7jk（能知道什么是序列化，什么是反序列化就行，已经对应的API（方法），其他的可以不看）

-----

### 框架(5天)

Spring MVC可以不用学了，当然也可以了解一下。现在都是前后端分离的项目，Spring boot把整合的时候会顺便带一下的。

- Mybatis(https://www.bilibili.com/video/BV1qq4y1y7qz），课程源码地址：https://gitee.com/beifeng_java/mybatis-study 课程笔记：https://shimo.im/docs/XpwJx9VYGjx9YrDr
- Spring（https://www.bilibili.com/video/BV1Vf4y127N5）（P1-P52**) 后面不需要看**
- Spring boot(https://www.bilibili.com/video/BV1gW411W76m 只需要看 **P1-p27**，因为涉及到前端的东西还有`thymeleaf` 都不用学，至于为什么不推荐学习2.0之后的版本，是因为我们在工作中都是把**spring boot当场spring来用**，高级功能根本用不到，所以学习1.x版本就可以了)
- Spring Boot和Mybatis 框架快速整合，以及PostMan的使用（https://www.bilibili.com/video/BV1hQ4y1q7oP)，对应笔记https://shimo.im/docs/VCXxX8y66vcgVGrH/ 《Spring Boot和Mybatis 快速整合课堂笔记》

----------

### 中间件与微服务(1周)

**redis**: https://www.bilibili.com/video/BV1Rv41177Af（先看P1-P20，后面的东西在面试考点也都会学习的。

P21-P47基本都是面试的考察点，可以等后面再看，也可以快速刷一遍。关于集群配置，持久化操作，知道是真怎么一回事就行了，不需要去搭建）

- 推荐使用windos版本的redis，方便快捷，安装教程(https://shimo.im/docs/473QywGNOgSZM63w/ 《Windos安装redis》)，Mac推荐用docker安装，方便快捷。



**rabbitMQ**：https://www.bilibili.com/video/BV1cb4y1o7zz  (只需要看P1-P70就行了，后面的都不需要看)

对应笔记https://shimo.im/docs/3dyyjyyPq9Wcdqdt/ 

推荐使用Windos版本的Rabbitmq，安装教程如下(https://shimo.im/docs/KrkEVLg5G5u4KLAJ/ 《Windows安装RabbitMq》)



**Spring cloud**：https://www.bilibili.com/video/BV18E411x7eT（**关于zookeeper、Consul、Bus、Stream的章节都不需要看，工作面试都不用。**）

--------------

### 项目（15天）

谷粒商城，之所以用电商，是因为他涉及到了三高，微服务，技术栈比较多，我们主要是学**技术栈在项目中的使用**，一些业务，一些场景。

视频地址：https://www.bilibili.com/video/BV1np4y1C7Yf

这个项目分为三篇，**基础篇，高级**，架构篇。不需要从零开头搭建一个完整的项目，学习这个项目主要学习技术在项目里面的应用，因此完全没有必要从零去构建。因此可以用easycode搭建其中的一个模块就行了，主要还是学习技术的应用。

**个人推荐了解一下项目背景，直接看我下面列举的重点就行了，因为最重要的环节(80%)在面试相关**。因此这个阶段主要是了解并发、中间件在项目中的应用。等后面面试的东西看完了，有时间的话，可以再回头看项目，理解起来更容易了，也能知道面试造火箭的技术栈在项目中的应用了，达到事半功倍的效果。

- 基础篇

  - 基础篇是前后端分离的，前端也会讲，建议前端直接跳过。(比如reren-fast-vue不需要构建)，只要后端接口能用**postman**掉通就行。
  - 基础篇前端的东西比较多，前端的东西可以直接跳过，需要搭建一个生成代码的页面，这个可以用easycode插件直接生成就行了。
  - 这个阶段主要是搭建一个分布式的项目。

- 高级篇**（重点）**

  - 这里面比较重要，涉及到了很多的技术栈，比如ES，如果不想学的话，可以跳过，但是不影响整体项目的，但是也是可以学习的，也是**从零搭建**的。

- 架构篇（不需要看）面试工作都用不到

  

  #### 日常工作提升重点看的内容（可以跳着看）

  - JSR303校验相关：https://www.bilibili.com/video/BV1np4y1C7Yf?p=66

  - 异步编排：https://www.bilibili.com/video/BV1np4y1C7Yf?p=193

  
#### **面试重点看的章节：主要为简历上的项目赋能**

看这个的原因就是可以写在简历上，让简历有**亮点**。而且可以直接看，无需要依赖前面的业务，主要就是学习技术方案的

- Redis相关：https://www.bilibili.com/video/BV1np4y1C7Yf?p=150  —— p166
  - threadlocal:https://www.bilibili.com/video/BV1np4y1C7Yf?p=239
  - MQ相关：https://www.bilibili.com/video/BV1np4y1C7Yf?p=248  ——P261
  - 分布式事务相关：https://www.bilibili.com/video/BV1np4y1C7Yf?p=284    ——P291

--------------

### 面试相关(20天)

主要搭配我给你的**面试题**，可以先过一遍。特别是**并发编程、MQ底层、mysql底层、redis底层**，要详细的去看，可搭配视频和专栏。百度网盘链接：https://pan.baidu.com/s/1K-XNqq0PXFsPE50G0_FmDA  （用到再下载）提取码：d4jb 

#### 优先级

- **高**：MySQL底层、并发编程(mysql执行速度和接口执行速度很重要，在面试中问的频率很高，工作上也能遇到)
- **中**：Redis底层、MQ底层
- 低：框架源码---Spring源码，看这个源码太浪费时间，而且现在问的也不是很多，可以先看看除了源码之外的考察重点，比如ioc，aop，循环注入，传播机制等，有时间的话再去看源码这块，对于以后工作coding有很大的提升。

#### 总体大纲(推荐先看)

**下面的课程能快速掌握一些面试点,推荐先看这里的，很快就能把基本重要的知识点过一遍**

**关于dubbo和zookeeper的内容不需要看了，因为这个技术已经被spring cloud替代了，所以不需要再看了。**

- HashMap必看：https://www.bilibili.com/video/BV1LJ411W7dP
- HashMap、并发编程、JVM、Redis、Spring、mysql：https://www.bilibili.com/video/BV1zE411G72m 
- **MVCC相关的三篇文章，一定要看**
  -  https://mp.weixin.qq.com/s?__biz=MzI4Mjg2NjUzNw==&mid=2247484638&idx=1&sn=6645ae0033ce4b7f2b85a6933b2b4b99&scene=21#wechat_redirect
  - https://mp.weixin.qq.com/s?__biz=MzI4Mjg2NjUzNw==&mid=2247484664&idx=1&sn=ece7631a6d6109efb62cf12c9efae5ff&scene=21#wechat_redirect
  - https://mp.weixin.qq.com/s/QCyzs91AavUD0o23Y4wLjw
- AQS：https://www.bilibili.com/video/BV1Hy4y1B78T中的AQS
- **只需要看**对应的MQ、Redis、分布式锁、分布式(其他的都不需要看)：https://www.bilibili.com/video/BV1kJ411n7u7 
- 分布式锁推荐看的视频：https://www.bilibili.com/video/BV1Hy4y1B78T中的分布式锁
- AQS推荐看视频：https://www.bilibili.com/video/BV1Hy4y1B78T?p=7
- thradlocal推荐看看：[https://www.bilibili.com/video/BV1fA411b7SX](https://www.bilibili.com/video/BV1fA411b7SX?from=search&seid=6966993745227957275)   
- Spring循环依赖相关：https://www.bilibili.com/video/BV1Hy4y1B78T中的循环依赖

---

**基本上上面的视频+我整理的面试考点，能覆盖面试所有的知识点。下面的资料，是更深入的去了解底层原理，一般情况下，把上面的看懂吸收80%左右，基本上就可以达到面试水平，现在基本上大厂应届生、社招1-5都是面试的这些东西。**

-----

**如果哪个面试点还是不是很明白，下面可以深入**

#### 并发编程&JVM

##### JVM

- 我写的笔记
- 《从 0 开始带你成为JVM实战高手》

##### 并发编程(重要)

##### 并发编程

- 《玩转Java并发工具，精通JUC，成为并发多面手》

- 可以搭配博客https://juejin.im/post/5aeed586f265da0b8262b019

- **专栏**

  ​	《Java并发编程实战》

 #### mysql

- **专栏**

  ​	 《MySQL实战45讲》

#### Redis

​		**专栏**

- 《Redis核心技术与实战》

- https://www.bilibili.com/video/BV1Hy4y1B78T （里面关于redis的内容）

#### Spring源码

《剑指Java自研框架，决胜Spring源码》这个是从基础开始讲解的，从最基础的反射，设计模式。
