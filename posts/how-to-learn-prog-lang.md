# 如何学习编程语言


> 前言：这篇文章要讨论的并不是编程新手所关注的问题，比如 “如何选一门入门编程语言”，“如何开始从零开始学习一门编程语言”这类问题，在我看来还有比这更让我感到担忧的问题，因为有很多有工作经验的工程师👨‍💻‍，在学习新语言时也会遇到各种学习方法和认知上的问题（当然也包括我自己），比如，学习时并没有具体目标、为了学而学、官方文档和语法都看了好几遍但是感觉了解的还是很浅、一上来就是抱着一本书闷着头扎进去、什么也不去了解直接就上手做项目结果到处碰壁、学了用不上很快就忘了、不知道怎样才算是学会了一门语言。所以，在这篇文章中我们主要围绕以下几个问题展开讨论：
- 为什么要学习多种编程语言？除了找工作时多一些资本之外，还有什么其他理由吗？
- 当我们选择新学一门编程语言时，为什么选了这门语言？是因为跟风？还是因为感觉挺有用的所以就学了？
- 当我们在学习一门编程语言的时候，我们究竟在学习什么？怎样才算是真正学会了这门语言？学会了语法，能写出项目就是学会了吗？
- 如果新学一门语言，在工作中却用不上，还有必要学吗？学了之后又如何能让它不荒废呢？

## 目录

- 我的自学经历
- 当我们在学习一门编程语言的时候，我们究竟在学习什么？
- 怎样才算是真正掌握了一门语言？
- 作为一个程序员需要掌握哪些语言？
- 为什么要学习多门语言？
- 学习编程语言的一些建议
- 总结

### 我的自学经历

从进入大学到现在为止，我先后学习过 C、C++、Objective-C、Swift、JavaScript、Python。


我最近花了大约 1 个月的时间在学习 Python，起源是因为看到项目中有些脚本工具使用 Python 写的，所以我一开始学习 Python 的主要目的，就是为了工具箱中多一个工具，后来又想知道 web 开发到底是怎么回事，就顺便学了下 web 开发。一句话概括，就是为了多掌握一门技能，开阔视野。

在学习 Python 的过程中，我也顺便记录下了我的[学习路线和笔记](https://github.com/ShannonChenCHN/APythonTour)。


### 当我们在学习一门编程语言的时候，我们究竟在学习什么？

- 程序语言本身
  - 语法
  - 语言特性
  - 使用技巧
  - 最佳实践
  - 内存管理
  - 设计哲学
  - 编程范式
  - 常用类库
  - 编译/解释机制和运行环境
- 计算机科学
  - 程序语言如何控制计算机
  - 计算机是如何工作的
  - 网络是怎样通信的
- 编程思想
  - 编程语言发展史，各门语言的起源和历史
  - 人类如何利用计算机解决问题
  - 编程和计算的关系
  - 抽象思维
  - 逻辑思维


最终目的：解决实际问题。


### 怎样才算是真正掌握了一门语言？

首先这取决于这门语言在你的日常开发工作中的角色，如果是主力开发语言（比如 ObjC），那就必须得精通，如果是辅助开发语言（比如 JavaScript），至少也要达到熟悉的程度，如果是很少用到的语言（比如 Ruby），能看懂别人的代码、能写简单的应用程序就行，还有最后一种就是纯粹兴趣使然的（比如 scheme、Lisp），了解即可。




级别           |  需求      |    要求      | 举例 
------------- | ------------- | ------------- | -------------
知道  | 工作中基本上用不到 | 知道该语言是用来干嘛的，跟自己工作的关系是怎样的 | Lisp、smalltalk
了解  | 在实践中接触过，但是工作中基本上不用自己去写 | 只需要能看懂别人写的，自己也会写一点简单的程序即可 | Ruby
会用/入门 | 工作中会用到，但是频次不高 | 会使用该语言的一些基本特性实现需求，知道该语言的特点和优势 | Swift、Python
熟练 | 工作用的比较多，仅次于第一语言 | 对于该语言的基本语法、高级特性以及常用 api、类库的使用非常熟练 | JavaScript
精通 | 工作中每天都要用到的，可以称之为“母语” | 除了熟练之外，还知道该语言的最佳实践、优缺点，底层实现 | Objective-C、C

### 作为一个程序员需要掌握哪些语言？
- 底层语言
  - C：学了 C 就会知道了地址和指针、字节这些概念，对计算机的数据存储和指令执行有更深的理解
  - 汇编：最接近机器语言的就是它了
- OOP
  - C++：跨平台，性能优越，一般用来开发游戏引擎、浏览器引擎这些底层库，以及 windows 桌面应用
  - Java：跨平台，可以写服务端，也可以写 Android 客户端 
  - Objective-C：专门用来开发 iOS 和 Mac 应用的语言，虽然是编译型语言，但它具备动态特性
- 动态语言
  - Python：语法简单、轮子多、开发效率高，一般应用于 web 开发、爬虫、数据分析、机器学习等领域
  - JavaScript：因为 web 时代的王者，动态性，依托于浏览器引擎的“跨平台”能力
- 脚本语言：自动化，提升开发效率
  - Python
  - Shell
- 函数式编程
  - Lisp
  
  关于各种语言的比较，推荐阅读一下 [『优秀的程序员应该掌握多少门编程语言？ - 李路的回答 - 知乎』](https://www.zhihu.com/question/22339358/answer/25488851) 和 [『作为一个程序员，至少需要掌握哪几种编程语言？ - find goo的回答 - 知乎』](https://www.zhihu.com/question/21994170/answer/282022844) 这两个回答。


### 为什么要学习多门语言？

学习语言最基本的目的是解决问题，所以学习一门语言的目的主要一般有两类，一是工作需要，用来开发产品的主力语言，比如 Java、ObjC 等，另一种就是用来开发一些辅助工具的语言，为了提升工作效率、自动化的语言，比如 Shell、Python 等。

从现实角度上来讲，往往一门语言的“价值”是由市场决定的，比如，之前移动开发比较火，ObjC 的程序员暴增，导致后来供远远大于求，招聘的要求也越来越高，那些只会 ObjC 的程序员的竞争力自然就比不过会多门语言的竞争者了。另外，很多公司在招人时还会要求除主力语言外同时会好几种语言，所以如果只学一门语言的话，会很容易让自己限于困境。


学一门语言很难了解语言的本质是什么，学了三门四门语言后，就会发现大部分编程语言的基本特性都差不多，语法也是大同小异。通过学习多门语言，可以抓住本质，总结共性，触类旁通，这样在学习新语言时很容易上手。

开阔思维，只会一门语言的话，很容易限制自己的思维。不同的语言有不同的特点和优势，盲目地争执哪种更好没有意义，掌握多种语言后，就相当于工具箱里有很多种工具，在面对实际问题时根据具体情况选择合适的语言。

### 学习编程语言的一些建议
- **精通：** 至少要精通一到两门语言，除非你是业务选手
- **时刻提醒自己的目的是什么：** 每一门语言都是入门容易精通难，学习新语言时一定要知道自己的目的是什么，不要一股脑扎进去，否则很容易把劲用错地方，陷入“只见树木，不见森林”的境地，白白耗费精力。这一点其实跟读书一样，有些书需要仔细阅读，有些书浅尝辄止即可。其实，很多时候，我们只需要了解一门新知识的 20% 就可以用它来解决大多数问题了，另外需要深入了解的细节可以等到用的时候再去**查漏补缺**，再去深挖，不要盲目为了深入而深入。
- **广度：** 在静态语言、动态语言、OOP、函数式、脚本、底层这几个大方向上，至少各掌握一门有代表性的语言
- **纸上得来终觉浅：** 学习编程语言一定要动手，需求驱动开发，而不是抱着一本手册从头看到尾，reference 是用来查阅的，而不是用来学习的，我在学习 Swift 时就犯过这样的错误
- **吸取营养：** 在实践中使用新学的语言的同时，还要从优秀的开源代码和经典书籍中吸取营养，不然很有可能你仅仅是在重复原来的经验，我在学习 Swift 时，就遇到过这种问题，用 Swift 写程序时依然还是 ObjC 的思维方式
- **找导师：** 如果在学习过程中能得到有经验的开发者指点，能少走很多弯路。
- **一鼓作气：** 学习过程要连贯，一鼓作气，最好是集中精力花一两个星期专注于搞定这门语言，因为如果你只是每天学 2 个小时，这样会把战线拉得很长，而且很有可能因为中间有其他事情给耽误了，后面再回过头来学习的时候，都已经忘得差不多了，这就跟 CPU 切换线程需要做切换上下文和环境初始化这些有消耗的事情一样。
- **能学到多少就是多少，不要死磕：** 如果中间遇到实在搞不明白的知识点或者解决不了的问题，可以先放下，保证学习过程的流畅性。其实很多时候，这个问题并不阻碍整个大方向，另外，有可能后面就能很快把这个问题解决。通常，我留给一个问题的解决时间的上限是 2 个小时。另一方面，因为很多时候，我们所能理解到的程度取决于当前的理解能力和知识面，所以，能学到多少就是多少，不要去浪费精力死磕，就像 bs 说的那样，“进一步有一步的欢喜”。

### 总结

学习一门语言之前，要明确自己的目标，也就是为什么要学这门语言。   

正式开始学习语言时，先了解全貌，然后根据二八法则，在学习了占 20% （这是一个大概的数字）的基础知识之后，就可以自己放开手写项目了，学编程，动手比什么都重要。

如何进阶？掌握语言的高级特性，了解语言的实现机制，不断总结，向高手学习。

### 参考
- [王垠：如何掌握所有的程序语言](http://www.yinwang.org/blog-cn/2017/07/06/master-pl)
- [如何评价王垠新博文《如何掌握所有的程序语言》？ - 知乎](https://www.zhihu.com/question/62097662)
- [如何快速学习一门编程语言？ - 知乎](https://www.zhihu.com/question/23882796)
- [作为一个程序员，至少需要掌握哪几种编程语言？ - 知乎](https://www.zhihu.com/question/21994170)
- [优秀的程序员应该掌握多少门编程语言？ - 知乎](https://www.zhihu.com/question/22339358)
- [当我们在学习一门编程语言的时候，我们究竟在学习什么？ - 知乎](https://www.zhihu.com/question/55510202)
- [ 孟岩：快速掌握一个语言最常用的50%](https://blog.csdn.net/myan/article/details/3144661)
- [应该如何学编程？](https://blog.xiadong.info/2017/07/16/%E5%BA%94%E8%AF%A5%E5%A6%82%E4%BD%95%E5%AD%A6%E7%BC%96%E7%A8%8B%EF%BC%9F/)
- [《七周七语言》](https://book.douban.com/subject/10555435/)
- [How to Learn a New Programming Language or Framework - Medium](https://hackernoon.com/how-to-learn-a-new-programming-language-faster-dc31ec8367cb)
- [John Sonmez: How To Learn A NEW Programming Language FAST!](https://simpleprogrammer.com/learn-new-programming-language-fast/)
- [John Sonmez: How to Learn Programming Languages Faster](https://www.sitepoint.com/how-to-learn-programming-languages-faster/)
- 《软技能：代码之外的生存指南》
- 《暗时间》
- [程序员如何在技术浪潮的更迭中保持较高的成长速度 ？](https://github.com/halfrost/Halfrost-Field/blob/master/contents/TimeElapse/2017.md)
- [梁杰：我如何用二十天刷完 SICP](http://numbbbbb.com/2016/03/28/20160328_%E6%88%91%E5%A6%82%E4%BD%95%E7%94%A8%E4%B8%A4%E5%91%A8%E6%97%B6%E9%97%B4%E5%88%B7%E5%AE%8C%20SICP/)
- [程序员练级攻略：编程语言 - 极客时间的左耳听风专栏](https://time.geekbang.org/column/article/85a9f0807a039f72731a579f84ce8941/share?from=singlemessage&isappinstalled=0)