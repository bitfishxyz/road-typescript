# TS学习资源汇总

### 什么是typescript？为什么要学习TS?
TypeScript = JavaScript + 类型系统

所以为什么要学习ts，这个问题约等于类型系统给js带来了哪些提升

这个回答面向两种读者:
#### 之前没有学习过强类型编程语言的同学

- 编程语言的类型系统为何如此重要？ - rainoftime的回答 - 知乎 https://www.zhihu.com/question/23434097/answer/43057230

- 在大型项目上，JavaScript 是个烂语言吗？ - 深海的回答 - 知乎 https://www.zhihu.com/question/321765804/answer/667577613

- 类型系统如何提升js代码的质量？https://www.infoq.cn/article/Bmx*2UO9VRMTSbSWw4qX

- TypeScript 解决了什么痛点？ https://www.zhihu.com/question/308844713

- 别骗自己了，你不用 TypeScript 的理由站不住脚 https://www.infoq.cn/article/IUCNZKqF*ucRI92P8VDp

#### 之前已经学习过Java等强类型语言的同学

有人说：“TypeScript 让 JavaScript 又变成了 Java，而我们不需要另一个 Java，所以我们不需要 TypeScript“。

其实在学习ts之前，我也有这个疑虑，但是随着对ts的理解，我强烈建议你学习ts，毫无疑问，它是js未来的方向。

- 如果你是前端开发，那么js处于垄断地位，你没有办法使用其他编程语言，你只能使用js，而为了享受类型系统的好处，ts是你唯一的选择

- 对于node开发者来说，ts + node 它和Java 或者c++ 有很大不同，即使你学过Java，ts也能给你到来全新的体验


## 如何学习ts
- 搭建ts的开发环境
- 学习ts的类型系统
- ts在前端项目中的使用
- ts在node中的使用

#### 搭建环境：
ts的开发环境两种：
- 把ts代码编译成js代码，然后再浏览器或者node中执行
  这是比较常规的做法，但是比较麻烦，需要有中间代码的生成
- 直接使用ts-node,
  ts 它能包装的nodejs，它可以直接运行ts代码，原理就是动态的编译然后交给node来执行
  事情起来方便

  这里我毛遂自荐下自己的一个项目，https://github.com/fish-node/template-node-ts 它可以让你快速搭建一个ts开发环境。

#### ts的类型系统

这部分看看文档就行了，把官方文档的代码敲一遍，仔细体会下ts的类型系统是怎么样设计的就行了

- 这个是官方文档https://www.typescriptlang.org/docs/home.html 英文

- 这是中文翻译https://www.tslang.cn/docs/handbook/typescript-in-5-minutes.html

初学者的话看到前面的类型推论的章节就行了，后面的知识点可以以后慢慢看。

然后后面关于模块化的章节，我觉得官网说的很乱，什么命名空间的这块的知识点已经被淘汰了。
关于模块化，大家可以看我的这个项目https://github.com/fish-node/ts-module
