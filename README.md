# libevent
The personal process of learning C++ an open source project libevent.

1.libevent是什么
libevent是一个轻量级的提供异步事件通知的软件库。libevent提供了一组API，这些API提供的机制允许开发者为事件注册回调函式，例如文件描述符上的发生了特定事件或者等待特定事件超时，接收到信号的事件，常规的定时器超时事件。当事件发生时，libevent实例会执行回调函数。
libevent在设计上是用来取代网络服务器所使用的事件循环检查框架。

2. 学习的好处
提升程序设计功力，libevent中有很多有用的设计技巧和基础数据结构，比如信息隐藏、函数指针、c语言的多态支持、链表和堆等，有助于提升自身的程序功力。
libevent是使用的Reactor模式，所以学习过程应该分为了解reactor模式->了解libevent
