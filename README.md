<h1>知识图谱</h1>

<hr/>

## C++基础

* [进程空间分配](https://www.cnblogs.com/ladawn/p/8449399.html)

* [c++从编译到生成可执行文件的流程](https://www.cnblogs.com/mrsandstorm/p/5701530.html)
    
* [c++内存各种变量存储区域](https://blog.csdn.net/jirryzhang/article/details/79518408)
    
* [c++强制类型转换](http://c.biancheng.net/view/410.html)
    
* [c++继承中的内在布局](https://www.oschina.net/question/565065_72355)

* [c++虚表的位置](https://blog.csdn.net/weixin_42187898/article/details/92615737)

* [RTTI的实现机制](https://blog.csdn.net/xiangbaohui/article/details/109231333)

## 算法

* [排序算法](https://www.cnblogs.com/itsharehome/p/11058010.html)

* [综合](https://blog.csdn.net/qiaoer2017/article/details/82715028)

## ZooKeeper

* [通知机制](https://www.cnblogs.com/shamo89/p/9787176.html)
    
* [集群管理](https://blog.csdn.net/leeyisong/article/details/80559505)
    
* [分布式锁](http://www.hollischuang.com/archives/1716)
    
* [如何选取主leader](https://www.jianshu.com/p/fb527a64deee)

## REDIS

* [redis的高可用](https://blog.csdn.net/qq_28410283/article/details/89197156)
    
* [主从复制如何实现](https://blog.csdn.net/sinat_32366329/article/details/81266568)
    
* [redis的集群模式](https://blog.csdn.net/chang384915878/article/details/86749209)
    
* [redis的持久化](http://doc.redisfans.com/topic/persistence.html)
    
* [redis的过期策略](https://blog.csdn.net/qq_29108585/article/details/63251491)
    
* [LRU算法实现(hashmap+双链表go版)] (https://github.com/v-hongwei/tinylru)
    
* [缓存穿透、击穿、雪崩](https://blog.csdn.net/zeb_perfect/article/details/54135506)
    
* [缓存与数据库不一致怎么办](https://blog.csdn.net/z50L2O08e2u4afToR9A/article/details/81024553)
    
* [主从数据库不一致如何解决](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=2651961330&idx=1&sn=4bdbada3b26d4fc2fc505f7a0f2ad7c4&chksm=bd2d022e8a5a8b38e59f0dfffba7ca407fe8711644b3794832572dd822c665205bb820cdddf7&scene=21#wechat_redirect)
    
* [先删缓存还是先删数据库](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=2651961341&idx=1&sn=e27916b8e96bd771c72c055f1f53e5be&chksm=bd2d02218a5a8b37ecffd78d20b65501645ac07c7ba2eb65b7e501a3eb9de023febe63bfdb36&scene=21#wechat_redirect)
    
* [Redis的常见性能问题和解决方案]
    
        (1) Master最好不要做任何持久化工作，如RDB内存快照和AOF日志文件
    
        (2) 如果数据比较重要，某个Slave开启AOF备份数据，策略设置为每秒同步一次
    
        (3) 为了主从复制的速度和连接的稳定性，Master和Slave最好在同一个局域网内

        (4) 尽量避免在压力很大的主库上增加从库
    
        (5) 主从复制不要用图状结构，用单向链表结构更为稳定，即：Master <- Slave1 <- Slave2 <- Slave3…
        这样的结构方便解决单点故障问题，实现Slave对Master的替换。如果Master挂了，可以立刻启用Slave1做Master，其他不变。

## MYSQL

* [SQL如何优化](https://vdisk.weibo.com/s/muWOT)
    
* [myisam和innodb的区别](https://blog.csdn.net/xifeijian/article/details/20316775)
    
* [索引原理](https://www.cnblogs.com/serendipity-fly/p/9300360.html)
    
* [varchar和char的区别](https://www.cnblogs.com/webph/p/6679815.html)
    
* [事务隔离性及区别](https://blog.csdn.net/qq_33290787/article/details/51924963)
    
* [InnoDB的行锁加在什么上？加在索引上](https://www.jianshu.com/p/c8e01a0c6d82)
    
* [联合索引的实现](https://blog.csdn.net/zgjdzwhy/article/details/84062105)
    
* [Mysql中控制内存分配的全局参数有哪些？](https://blog.csdn.net/miyatang/article/details/54881547)
    
* [explain是如何解析sql的](https://www.linuxidc.com/Linux/2018-08/153354.htm)
    
* [order by的原理](https://www.cnblogs.com/lamp01/p/10770172.html)
    
* [join实现原理](https://www.jianshu.com/p/16ad9669d8a9)
    
* [left join、inner join、right join](https://blog.csdn.net/lp_cq242/article/details/79942457)

## 网络

* [浏览器发起一次请求的过程](https://www.cnblogs.com/xuxinstyle/p/9382506.html)

* [TCP如何保证可靠性](https://www.jianshu.com/p/6aac4b2a9fd7)
    
* [select, poll, epoll](https://www.cnblogs.com/aspirant/p/9166944.html)
    
* [epoll的ET和LT](https://www.jianshu.com/p/d3442ff24ba6)
    
