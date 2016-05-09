# 目录

[1 Spark 是如何执行程序的]()
[2 选择正确的 Operator]()
[3 什么时候不发生 Shuffle]()
[4 什么情况下 Shuffle 越多越好]()
[5 二次排序]()
[6 调试资源分配]()
[7 调试并发]()
[8 压缩数据结构]()
[9 数据格式]()

<br></br>

>>当你开始编写`Apache Spark`代码或者浏览公开的`API`的时候，你会遇到诸如`transformation，action，RDD`等术语。了解到这些是编写`Spark`代码的基础。同样，当你任务开始失败或者你需要透过`web`界面去了解自己的应用为何如此费时的时候，你需要去了解一些新的名词:`job, stage, task`。对于这些新术语的理解有助于编写良好`Spark`代码。这里的良好主要指更快的`Spark`程序。对于`Spark`底层的执行模型的了解对于写出效率更高的`Spark`程序非常有帮助。
