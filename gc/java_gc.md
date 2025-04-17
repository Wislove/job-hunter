# Java的垃圾回收

## JVM内存的划分

Java编译器将类编译成字节码

JVM钟内存模型： 类加载器(加载字节码)，执行引擎，运行时数据区


类加载器4类：
- Bootstrap ClassLoader,
- Extension ClassLoader,
- App ClassLoader,
- User ClassLoader（自定义）
  
双亲委派模型: 父类加载器加载失败，子类加载器加载，如果子类加载器加载失败，则向上递归，直到Bootstrap ClassLoader

运行时数据区（线程共享和私有）
程序计数器(PC), 本地方法栈(native方法栈)，Java虚拟机栈(程序执行栈帧), 堆(包含字符串常量区)，元空间(包含运行时常量区)

Java虚拟机栈：
OutOfMemoryError: 栈允许扩展，栈扩展时无法申请到足够的内存，则抛出OutOfMemoryError
StackOverflowError：栈调用深度过深，超过jvm配置的栈深度（默认1M）


堆又分为：

- 新生代: Eden, Survior(From区，TO区)
- 老年代: Full GC
 

## 对象的创建

new关键字创建对象

Object obj = new Object();

1. 类加载过程
2. 内存分配（内存分配方法：指针碰撞，空闲列表。分配原则：有先Eden，大对象old）。obj进行入java虚拟机栈，指向堆里面new的Object的地址，按照方法调用顺序依次入栈


## GC垃圾回收

### 垃圾标记算法
- 引用计数（循环引用问题）
- 可达性分析（GC Root）

### 垃圾清理算法
- 标记-清除算法（会有内存碎片）
- 标记-整理算法
- 复制算法（会浪费内存）



