[![QQ群](https://img.shields.io/badge/公众号-小猿刷题-red.svg)](//shang.qq.com/wpa/qunwpa?idkey=bc73f12268da5c5eafcfc91f0dd05eb7fed033420921ef7bf4eca316deb7e12)

<p align="center">
   <img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1567072905503&di=058dd45bf8de45b81703b703d915acfc&imgtype=0&src=http%3A%2F%2Fn.sinaimg.cn%2Fsinacn%2Fw462h336%2F20180301%2F3f38-fwnpcns6226738.jpg" height="120">
</p>

<p align="center">
   <strong>Java生态</strong>
</p>

<p align="center">
   <strong>感谢: 微信、CSDN、开源中国、博客园、简书、头条号、头条IO等 媒体平台提供内容资源</strong>
</p>

<p align="center">
   <a target="_blank" href="https://github.com/P-P-X/awesome-collector">
       <img src="https://img.shields.io/github/stars/P-P-X/awesome-collector.svg?style=social&label=Stars"></img>
   </a>
</p>	
 
<p align="center">
   <img src="https://i.loli.net/2019/12/18/ARJloEjadv7pDiH.jpg" height="100">
</p>  

### Java理论

#### Java JVM

- [Java高频面试基础](https://www.jianshu.com/p/06ff2ea9b2c3)

- [JVM核心知识体系](https://mp.weixin.qq.com/s/clMdl6eW9hz9jiB5oDSawA)

- [理解Java虚拟机](https://www.cnblogs.com/williamjie/p/9511108.html)

- [Java类加载机制](https://www.cnblogs.com/paddix/p/5268559.html)

- [虚拟机创建对象的两种方式](https://blog.csdn.net/sunny_aaadolly/article/details/78924799)

- [JVM内存模型: 线程私有(程序计数器、本地方法栈、虚拟机栈)、线程共享(堆、方法区)](http://tech.huntswork.com/2016/08/01/%E5%BA%94%E7%94%A8%E5%AE%9E%E8%B7%B5/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/%E7%90%86%E8%A7%A3Java-%E8%99%9A%E6%8B%9F%E6%9C%BA/)

- [被GC判断为”垃圾”的对象一定会回收吗](https://blog.csdn.net/mine_song/article/details/63251367)

<!-- more -->

- [Java对象引用类型: 强、软、弱、虚](http://tech.huntswork.com/2016/08/01/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/%E7%90%86%E8%A7%A3Java-%E8%99%9A%E6%8B%9F%E6%9C%BA/)

- [对象判死方法: 引用计数法、可达性分析法(GC Roots)](http://tech.huntswork.com/2016/08/01/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/%E7%90%86%E8%A7%A3Java-%E8%99%9A%E6%8B%9F%E6%9C%BA/)

- [垃圾收集算法: 标记-清除、复制、标记-整理、分代收集](http://tech.huntswork.com/2016/08/01/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/%E7%90%86%E8%A7%A3Java-%E8%99%9A%E6%8B%9F%E6%9C%BA/)

- [Java垃圾收集器: Serial、ParNew、Parallel Scavenge、Serial Old、Parallel Old、CMS、G1](http://tech.huntswork.com/2016/08/01/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/%E7%90%86%E8%A7%A3Java-%E8%99%9A%E6%8B%9F%E6%9C%BA/)

- [GC回收总结: 4种垃圾收集算法和7中垃圾收集器](https://blog.csdn.net/clover_lily/article/details/80160726)

- [MinorGC、MajorGC和FullGC区别](http://www.importnew.com/15820.html)

- [MinorGC和FullGC的触发时机, 什么是HandlerPromotionFailure](https://www.cnblogs.com/williamjie/p/9516367.html)

- [深入CMS垃圾收集器](http://www.importnew.com/27822.html)

- [为什么CMS两次标记时要](https://blog.csdn.net/fhy569039351/article/details/83960709)

- [CmsGC问题排查](https://iamzhongyong.iteye.com/blog/1989829)

- [JavaG1学习笔记](https://www.cnblogs.com/williamjie/p/10191142.html)

- [深入G1垃圾收集器](https://liuzhengyang.github.io/2017/06/07/garbage-first-collector/)

- [Cms和G1比较](https://www.cnblogs.com/rgever/p/9534857.html)

- [深入ZGC垃圾收集器](https://mp.weixin.qq.com/s/DBYMqAyMOvSFiCDtYerqxw)

- [一文读懂Java 11的ZGC为何如此高效](https://mp.weixin.qq.com/s/nAjPKSj6rqB_eaqWtoJsgw)

- [Java堆和栈的区别,JVM堆和栈的介绍](https://blog.csdn.net/qq_41675686/article/details/80400775)

- [JDK1.7的永久代(PermGen)和JDK1.8的元空间(Metaspace)](https://www.cnblogs.com/williamjie/p/9563766.html)

- [Java内存溢出和栈溢出](https://blog.csdn.net/z69183787/article/details/75530650)

- [Java溢出解决](https://blog.csdn.net/qq_38306026/article/details/79290367)

- [CmsGC问题排查](https://iamzhongyong.iteye.com/blog/1989829)

- [Jstack查询死锁线程](https://www.cnblogs.com/aspirant/p/9670212.html)

- [Java程序初始化顺序:静态代码块、代码块、方法](http://tech.huntswork.com/2016/03/27/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/%E7%90%86%E8%A7%A3Java-%E7%B1%BB%E4%B8%8E%E5%8F%98%E9%87%8F/)

- [JVM进阶系列](https://blog.csdn.net/wwwtotoro/article/details/72763014)

- [CMS收集器和G1收集器优缺点](http://www.cnblogs.com/aspirant/p/8663897.html)

- [Java堆外内存回收原理](https://mp.weixin.qq.com/s/lOA-6j0SeTjjHz1gYPFNQA)

- [性能优化系列三：JVM优化](https://www.cnblogs.com/leeSmall/p/9325164.html)

- [一个Java对象到底占用多大内存](https://www.jianshu.com/p/194b745884a5)

- Hashcode相等两个类一定相等? equals呢？相反呢？
#### Java Collection&JUC

- [JDK1.7和1.8的区别](https://www.cnblogs.com/aspirant/p/8617201.html)

- [Java面向对象特征: 封装、继承、多态](http://tech.huntswork.com/2016/03/27/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/%E7%90%86%E8%A7%A3Java-%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1/)

- [Java变量访问权限: public、protected、default、private](http://tech.huntswork.com/2016/03/27/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/%E7%90%86%E8%A7%A3Java-%E7%B1%BB%E4%B8%8E%E5%8F%98%E9%87%8F/)

- [Java位运算对比说明](http://tech.huntswork.com/2014/01/11/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/%E7%90%86%E8%A7%A3Java-%E4%BD%8D%E8%BF%90%E7%AE%97/)

- [Java对象深拷贝和浅拷贝](https://blog.csdn.net/wangxueming/article/details/52034841)

- [Java关键字.final、static、this、super对比](https://github.com/Snailclimb/JavaGuide/blob/master/Java%E7%9B%B8%E5%85%B3/final%E3%80%81static%E3%80%81this%E3%80%81super.md)

- [Java序列化transient关键字使用小记](https://www.cnblogs.com/aspirant/p/8905783.html)


- [Java字符串.String、StringBuffer、StringBuilder对比](http://www.cnblogs.com/su-feng/p/6659064.html)

#### 容器集合

- [Java集合.List、Set、Map区别概述](https://blog.csdn.net/u010775025/article/details/79315361)

- [Java集合.List接口及其实现](https://www.cnblogs.com/chanshuyi/p/4468467.html)

- [Java集合.Set接口及其实现](https://www.cnblogs.com/chanshuyi/p/4468470.html)

- [Java集合.Map接口及其实现](https://www.cnblogs.com/chanshuyi/p/4468471.html)

- [Java集合.Vector、ArrayList、LinkedList区别](https://blog.csdn.net/u010775025/article/details/79315361)

- [Java集合.HashMap和HashTable的区别](https://blog.csdn.net/varyall/article/details/81988978)

- Hashmap和Treemap有什么区别? 底层数据结构是什么?

- [Java集合.HashMap的长度为什么是2的幂次方](https://blog.csdn.net/varyall/article/details/81988978)

- [HashMap 多线程下死循环分析及JDK8修复](https://cloud.tencent.com/developer/article/1120823)

- [Java集合.ConcurrentHashMap和HashTable的区别](https://blog.csdn.net/varyall/article/details/81988978)

- [Java集合.ArrayList源码分析](http://www.tianxiaobo.com/2018/01/28/ArrayList%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90/)

- [Java集合.LinkedList源码分析(JDK 1.8)](http://www.tianxiaobo.com/2018/01/31/LinkedList-%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90-JDK-1-8/)

- [Java集合.HashMap源码分析(JDK1.8)](http://www.tianxiaobo.com/2018/01/18/HashMap-%E6%BA%90%E7%A0%81%E8%AF%A6%E7%BB%86%E5%88%86%E6%9E%90-JDK1-8/)

- [Java集合.LinkedHashMap 源码详细分析（JDK1.8）](http://www.tianxiaobo.com/2018/01/24/LinkedHashMap-%E6%BA%90%E7%A0%81%E8%AF%A6%E7%BB%86%E5%88%86%E6%9E%90%EF%BC%88JDK1-8%EF%BC%89/)

- [Java集合.HashMap底层实现(JDK1.8之前/后)](https://github.com/Snailclimb/JavaGuide/blob/master/Java%E7%9B%B8%E5%85%B3/%E8%BF%99%E5%87%A0%E9%81%93Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6%E9%9D%A2%E8%AF%95%E9%A2%98%E5%87%A0%E4%B9%8E%E5%BF%85%E9%97%AE.md#hashmap%E7%9A%84%E5%BA%95%E5%B1%82%E5%AE%9E%E7%8E%B0)

- [Java集合.ConcurrentHashMap底层实现(JDK1.8之前、之后)](https://github.com/Snailclimb/JavaGuide/blob/master/Java%E7%9B%B8%E5%85%B3/%E8%BF%99%E5%87%A0%E9%81%93Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6%E9%9D%A2%E8%AF%95%E9%A2%98%E5%87%A0%E4%B9%8E%E5%BF%85%E9%97%AE.md#concurrenthashmap%E7%BA%BF%E7%A8%8B%E5%AE%89%E5%85%A8%E7%9A%84%E5%85%B7%E4%BD%93%E5%AE%9E%E7%8E%B0%E6%96%B9%E5%BC%8F%E5%BA%95%E5%B1%82%E5%85%B7%E4%BD%93%E5%AE%9E%E7%8E%B0)

- [ConcurrentHashMap的实现原理(JDK1.7和JDK1.8)](http://youzhixueyuan.com/concurrenthashmap.html)

- [Java集合.TreeMap源码分析](http://www.tianxiaobo.com/2018/01/11/TreeMap%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90/)

- [Java集合.集合容器对比](https://github.com/Snailclimb/JavaGuide/blob/master/Java%E7%9B%B8%E5%85%B3/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6%E5%B8%B8%E8%A7%81%E9%9D%A2%E8%AF%95%E9%A2%98%E6%80%BB%E7%BB%93.md)

#### 线程与锁

- [Java并发编程.进程和线程](https://www.cnblogs.com/dolphin0520/p/3910667.html)

- [认识协程](https://www.liaoxuefeng.com/wiki/001374738125095c955c1e6d8bb493182103fac9270762a000/0013868328689835ecd883d910145dfa8227b539725e5ed000)

- [Java线程与内核线程的关系](https://www.cnblogs.com/zhangfengshi/p/9953476.html)

- [线程的实现与调度](https://blog.csdn.net/ns_code/article/details/17371269)

- [进程、线程与协程](https://www.cnblogs.com/zhang-can/p/7215506.html)

- [Java线程与操作系统线程调度映射](https://www.jianshu.com/p/3f6b26ee51ce)
	
- [Java多线程和操作系统多线程关系](https://blog.csdn.net/faker_wang/article/details/80714772)

- [Java线程与操作系统线程](https://blog.csdn.net/nalanmingdian/article/details/77748326)

- [Java并发编程.线程基本状态](https://www.cnblogs.com/chanshuyi/p/4445621.html)

- [Java并发编程.线程状态控制](https://www.cnblogs.com/chanshuyi/p/4446992.html)

- [Java并发编程.线程间的协作(wait/notify/sleep/yield/join)](http://www.cnblogs.com/paddix/p/5381958.html)

- [Java并发编程.Thread类的使用](https://www.cnblogs.com/dolphin0520/p/3920357.html)

- [Java并发编程.Callable、Future和FutureTask](https://www.cnblogs.com/dolphin0520/p/3949310.html)

- [4种常用Java线程锁](http://youzhixueyuan.com/4-kinds-of-java-thread-locks.html)

- [Java并发编程.同步锁、读写锁](https://www.cnblogs.com/chanshuyi/p/4456913.html)

- [Java并发编程.Synchronized关键字](https://www.cnblogs.com/dolphin0520/p/3923737.html)

- [Java并发编程.Synchronized及其原理实现](https://www.cnblogs.com/paddix/p/5367116.html)

- [Java并发编程.Synchronized底层优化(偏向锁、轻量级锁)](http://www.cnblogs.com/paddix/p/5405678.html)

- [Java并发编程.Lock(ReentrantLock、ReadWriteLock、ReentrantReadWriteLock)](https://www.cnblogs.com/dolphin0520/p/3923167.html)

- [Java并发编程.公平锁和非公平锁](https://www.cnblogs.com/dolphin0520/p/3923167.html)

- [Java并发编程.volatile关键字](https://www.cnblogs.com/dolphin0520/p/3920373.html)

- [Java并发编程.volatile的使用及其原理](http://www.cnblogs.com/paddix/p/5428507.html)

- [Java并发编程.ThreadLocal原理](https://www.cnblogs.com/dolphin0520/p/3920407.html)

- [Java并发编程.同步容器](https://www.cnblogs.com/dolphin0520/p/3933404.html)

- [Java并发编程.ConcurrentModificationException异常](https://www.cnblogs.com/dolphin0520/p/3933551.html)

- [Java并发编程.ConcurrentHashMap](https://www.cnblogs.com/dolphin0520/p/3932905.html)

- [Java并发编程.CopyOnWriteArrayList](https://www.cnblogs.com/dolphin0520/p/3938914.html)

- [Java并发编程.线程池原理分析,都有什么参数? 底层如何实现?](http://www.tianxiaobo.com/2018/04/17/Java-%E7%BA%BF%E7%A8%8B%E6%B1%A0%E5%8E%9F%E7%90%86%E5%88%86%E6%9E%90/)

- [Java并发编程.线程池的使用](https://www.cnblogs.com/dolphin0520/p/3932921.html) 

- [Java并发编程.ThreadGroup](https://www.cnblogs.com/barrywxx/p/9976417.html)

- [Java并发编程.CountDownLatch、CyclicBarrier和Semaphore](https://www.cnblogs.com/dolphin0520/p/3920397.html)

- [Java并发编程.Timer和TimerTask](https://www.cnblogs.com/dolphin0520/p/3938991.html)

- [Java并发编程.Fork-Join](https://www.cnblogs.com/aspirant/p/8622584.html)

- [Java并发编程.认识AQS](https://www.jianshu.com/p/da9d051dcc3d)

- [Java并发编程.AQS原理及AQS同步组件总结](https://mp.weixin.qq.com/s/joa-yOiTrYF67bElj8xqvg)

- [Java并发编程.AQS原理和学习](https://juejin.im/post/5c739c5cf265da2dd8689b46)

- [Java并发编程.CAS原子操作及其Java中的应用](https://juejin.im/post/5c7281365188252a160f148b)

- [Java并发编程.CAS中的ABA问题以及如何解决](https://www.cnblogs.com/barrywxx/p/8687653.html)

- [Java并发编程.Java中的锁原理、锁优化、CAS、AQS](https://www.cnblogs.com/barrywxx/p/8678698.html)

- [Java并发编程.面试题](https://www.cnblogs.com/dolphin0520/p/3932934.html)

- [Java并发编程.面试题](https://www.cnblogs.com/dolphin0520/p/3958019.html)

- [如何实现一个延时队列](https://liuzhengyang.github.io/2017/01/03/delay-queue/)

- [线程数究竟设多少合理](https://mp.weixin.qq.com/s/CBGMRsk6aFYAGiYQucqF_w)

- [Java中如何让线程按照自己指定的顺序执行](https://blog.csdn.net/u010185035/article/details/81172767)

- [让线程按顺序执行8种方法](https://www.cnblogs.com/wenjunwei/p/10573289.html)

#### JAVA IO

- [JavaIO.认识NIO](https://www.cnblogs.com/duanxz/p/6759689.html)

- [JavaIO流: IO、NIO、AIO](https://github.com/Snailclimb/JavaGuide/blob/master/Java%E7%9B%B8%E5%85%B3/Java%20IO%E4%B8%8ENIO.md)

- [JavaIO.图解BIO、NIO、AIP](https://www.cnblogs.com/barrywxx/p/8430790.html)

- [JavaIO模型(IO、NIO、AIO)和Linux的IO模型(阻塞IO、非阻塞IO、信号驱动IO、IO复用、异步IO)](http://tech.huntswork.com/2016/03/27/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/%E7%90%86%E8%A7%A3Java-IO%E6%A8%A1%E5%9E%8B/)

- [JavaIO应用BIO、NIO、AIP示例](https://www.cnblogs.com/barrywxx/p/8570807.html)

