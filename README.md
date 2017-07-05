# Python那些事儿

`
大家可以提话题，如果合适我会录入到书里.
`

## 临时列表:

* Python数据结构实现原理:
  * ...
  * tuple
  * list
  * dict
  * set


* Python gil


* Python的内存管理
  * 基本分层
  * 内存缓冲池
  * 对象缓冲池
  * gc
    * 引用计数
    * 标记清除
    * 分代回收


* 常见问题
  * 通过opcode字节码验证Python的线程安全
  * 为何出现Python多线程超跑TOP cpu100%的情况？
  * Python Queue的实现原理 ?
  * Python Multiprocessing Queue的实现原理 ?
  * 如何确认Python框架及模块是非阻塞的？
  * 如何调试代码及在线调试附带上下文的逻辑?
  * Python连接池的实现 ?


* Python多任务处理
  * Python 线程
  * Python 多进程
  * Python 协程
  * 较完美的解决方案


* Python Multiprocessing
  * Value实现原理
  * Manager实现原理
  * ...


* 锁
  * 锁机制
  * 读写锁
  * 分段锁
  * gcc __sync_x cas锁


* 网络编程中查找性能点
  * 压力源
  * 是否阻塞
  * content switch过高
  * metrics time cost监控
  * 大招systramp


* 网络编程中提高性能
  * io非阻塞
  * 长连接及连接池
  * io合并
  * prefork + event_loop
  * accept锁策略


* Python Redis 实战场景
  * 基于客户端的集群设计
  * 如何提高io效率及吞吐
  * 设计消息可靠的队列
  * 定时器的设计
  * 多维度分页设计
  * 分布式锁
    * 简单粗暴的分布式锁设计
    * 可重入的分布式锁设计
    * 顺序公平的分布式锁


* Python 并发任务管理
  * 信号
  * 安全退出
  * 僵尸进程
  * 规避OOM
  * 动态加减进程
  * 重载
  * fcntl 文件锁
  * 合理设置进程名
  * 线程池
  * 协程池
  * 进程文件描述表
  * copy on write


* Python Rocksdb实现redis数据结构
  * rocksdb原理
  * list
  * hash
  * zset
  * set
  * sharding
  * tcp server
  * match redis client

...
