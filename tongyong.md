# 自我介绍


# 面试来临时的准备

随着下面列举的问题思考下你可能会遇到的 20 个面试问题，每个问题准备 2-3 种回答。
准备点故事，不要只是摆一些你完成的事情的数据，相信我，人人都喜欢听故事。

- 你为什么想得到这份工作？
- 你解决过的最有难度的问题是什么？
- 面对过的最大挑战是什么?
- 见过的最好或者最坏的设计是怎么样的?
- 对某个产品提出改进建议。
- 你作为一个个体同时也是团队的一员，如何达到最好的工作状态?
- 你的什么技能或者经验是你的角色中不可或缺的，为什么？
- 你在某份工作或某个项目中最享受的是什么?
- 你在某份工作或某个项目中面临过的最大挑战是什么?
- 你在某份工作或某个项目中遇到过的最硬的 Bug 是什么样的？
- 你在某份工作或某个项目中学到了什么？
- 你在某份工作或某个项目中哪些地方还可以做的更好？

# 问面试官的问题
我会问的一些：(可能我已经知道了答案但我想听听面试官的看法或者了解团队的前景):

- 团队多大规模?
- 开发周期是怎样的? 会使用瀑布流/极限编程/敏捷开发么?
- 经常会为截止日期（deadlines）加班么? 或者是有弹性的?
- 团队里怎么做技术选型?
- 每周平均开多少次会?
- 你觉得工作环境有助于员工集中精力吗?
- 目前正在做什么工作?
- 喜欢这些事情吗?
- 工作期限是怎么样的?
- 工作生活怎么平衡? 


# 通用答题思路

这是我总结的一些答题思路。这种思路跟具体的知识点没有关系，只是一种组织答案的手段。

其实，本质上来说，这些答题思路，实际上也就是我日常分析问题的思路

## 为什么使用A？ or 为什么不使用 A

这是一个最常见的模式，一般是面试官问你，你为什么使用了某项技术。举例来说，消息队列属于百家争鸣，于是很可能面试官就是要问你“为什么你用`Kafka`？”。

有些同学要懵逼了，我咋知道，我进来就是用`Kafka`。

这显然是陷入误区了。这个问题，面试官其实不是想问你为什么选择了`Kafka`，而是你是否了解`Kafka`的特性。所以，你的回答就应该是，`Kafka`有什么特性，别的消息中间件有什么特性，你的业务有什么特性，所以你选择`Kafka`。

回答类似于这种“你为什么不用A”或者“你为什么用A”，答题的思路都是：
1. A 有什么特点
2. 类似产品 B C D 有什么特点
3. 我的业务，或者我的场景是什么特点
4. 所以我选择 A

这个思路其实也就是一般做技术调研的思路。

这里有一个小技巧，如果你清楚知道你面试那家公司用的是哪个产品，那么你就要深入学习这个产品，而后用来和你的选择做对比。举例来说，你们用的是`Kafka`，然后你了解到面试官公司用的是`ActiveMQ`，那么你在回答“为什么使用`Kafka`”的时候，就重点和`ActiveMQ`作为对比。


## 你是如何解决X问题的？

这个问题也很常见。一般是为了考察你在解决问题的时候，有没有权衡和思考。很多同学会说，这个方案是大佬设计的，我哪里知道？

不好意思，面试官就是想让你说出来，大佬是如何决策的。

其实这个问题和 `为什么使用A` 是类似的，或者说差不多的。不过就是话术上要转变一下。

一般的思路是：
1. 业界的一般做法，有 A B C，它们都有啥特点
2. 我的场景是怎样的
3. 所以选择 A

这里面比较能刷出亮点的是，横向比较某两个候选方案。注意的是，这个候选方案是你排除了明显不合理之后，看起来都行的方案，然后你要着重描述你选择某个方案的理由。