# 最优质的学习资料

本项目的目的是帮助开发者**更快地**找到**最优质的**学习资料。主要关注前端开发、计算机基础、机器学习的内容。

收录内容的主要来源是：知乎、StackOverflow 上的高分回答，以及在 GitHub 上的其他收集类项目。

收录的依据主要是：在领域内的经典程度、作者权威性、推荐者的数量、推荐者的权威性、谷歌搜索排名、GitHub 仓库的 Star 数量、豆瓣评分和评价、我听闻到它的次数和评价好坏等等。不放心的同学可以在阅读之前在知乎或 Google 搜索相关的评价。

**如果可以，尽量选择英文版的材料来阅读！**

本项目将持续更新，如果你发现了其它优质的学习资料，欢迎提 issue 或 pull request！如果这个项目有幸帮助到了你，欢迎推荐给朋友、加 Star！

> 这个列表上的大部分内容我都没有读完，这个列表仅仅用于满足自己的收集癖好。

# 目录

<!--ts-->

- [最优质的学习资料](#最优质的学习资料)
- [目录](#目录)
- [算法](#算法)
- [计算机基础](#计算机基础)
- [软件设计思想和编程语言](#软件设计思想和编程语言)
- [编译原理](#编译原理)
- [计算机网络](#计算机网络)
- [数据库](#数据库)
- [操作系统理论](#操作系统理论)
- [操作系统实践（Linux 运维）](#操作系统实践linux运维)
- [UNIX 编程](#unix编程)
- [工程化](#工程化)
  - [GIT](#git)
  - [软件工程](#软件工程)
- [程序员的自我修养](#程序员的自我修养)
- [C/C++](#cc)
- [Python](#python)
- [前端](#前端)
  - [JavaScript 开发进阶](#javascript开发进阶)
  - [ES6](#es6)
  - [v8](#v8)
  - [前端杂项](#前端杂项)
  - [Angular](#angular)
  - [Vue](#vue)
- [机器学习](#机器学习)
  - [TensorFlow](#tensorflow)
  - [PyTorch](#pytorch)
- [数学基础](#数学基础)
  - [Optimization (优化理论)](#optimization-优化理论)
  - [线性代数](#线性代数)
  - [概率与统计](#概率与统计)
- [杂项](#杂项)
  - [清单](#清单)
  - [公开课](#公开课)

<!--te-->

# 算法

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

- [Introduction to Algorithms](https://book.douban.com/subject/3904676/) 推荐率最高的算法书。经典、全面、深入。不过对于入门者，它的难度和容量可能有点大。
- [Algorithms](https://book.douban.com/subject/19952400/) 每个开发者必知必会的数据结构和算法。也是经典教材，评价很高。相比于 Introduction to Algorithms，这本书是从开发者的需要出发，介绍那些实用的算法，相对易懂；而 Introduction to Algorithms 是更加系统、深入地研究算法理论。[配套网站](https://algs4.cs.princeton.edu/home/)中包含了算法精讲以及习题答案。
- [Algorithms(算法概论)](https://book.douban.com/subject/1996256/) 相对于 Introduction to Algorithms 和 Algorithms，这本书很薄，但是它的讲解简单优美有趣，适合初学者。
- [编程珠玑](https://book.douban.com/subject/3227098/)。相对较薄的一本书。本书并没有系统地归纳各种算法，而是通过一些精心设计的有趣而又颇具指导意义的程序实例，引导读者理解问题、选择和实现算法。
- [算法竞赛入门经典](https://book.douban.com/subject/25902102/) 与前面的算法书相比，它的实用性非常强，是一本“解题”的教材，适合算法学习（刷题）的入门。真希望自己在高中阶段就了解到这本书，开启编程（竞赛）的大门。。。
- [编程之美](https://book.douban.com/subject/3004255/) 面试的经典问题，引发读者思考，领略算法的乐趣。
- [Top 10 algorithms in Interview Questions](https://www.geeksforgeeks.org/top-10-algorithms-in-interview-questions/) geeksforgeeks 有很多常用数据结构、算法的文章。这篇文章以及 geeksforgeeks 适合短期复习的同学。

# 计算机基础

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

- [深入理解计算机系统(CSAPP)](https://book.douban.com/subject/26912767/) 神书，要被捧上天了（非贬义）。 [勘误表](http://yiligong.org/csapp3e/)
- [编码 隐匿在计算机软硬件背后的语言](https://book.douban.com/subject/4822685/) 通俗易懂，面向入门者，近乎科普。评价很高，经常被推荐。
- [程序员的自我修养](https://book.douban.com/subject/3652388/) 讲解了一个程序在其生命周期里会碰到的种种事物。国人写的书。经常被推荐。
- 计算机体系结构：[计算机组成与设计 硬件/软件接口](https://book.douban.com/subject/26604008/)，[计算机体系结构 量化研究方法](https://book.douban.com/subject/7006537/)这两本书作者是一样的，但内容不一样。只要是推荐这方面的书的问题，少不了这两本。我上计算机组成原理课的时候用的就是前面那本书，虽然内容听起来很可怕，但是英文版读起来真的很好懂（只要你英语过关）。
  - [伯克利 cs61c 课程](http://www-inst.eecs.berkeley.edu/~cs61c/su18/)是以这本书为教材的，在课程官网可以找到学习资源。
    > 参考这两个知乎问题：[有哪些不错的介绍计算机体系结构的书籍？](https://www.zhihu.com/question/19897585)，[计算机体系结构这门课的主要内容是什么？ 如何自学？](https://www.zhihu.com/question/37330125)

# 软件设计思想和编程语言

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

- [计算机程序的构造和解释(SICP)](https://book.douban.com/subject/1148282/) 神书，Scheme 三剑客之一。修炼编程内功，理解程序的本质。务必完成书中的练习。
  - [官方 HTML 版](https://mitpress.mit.edu/sicp/)、[精校版](https://sicpebook.wordpress.com/)、[习题答案](http://community.schemewiki.org/?sicp-solutions)
  - [SICP 公开课中文化项目](https://github.com/DeathKing/Learning-SICP)有 SICP 课程的中英文资源。
  - 语言&编辑器：做练习的时候推荐使用[Racket](https://racket-lang.org/)并安装[SICP 扩展包](https://docs.racket-lang.org/sicp-manual/)。Racket 的 IDE 使用体验比 MIT-Scheme 好很多，并且 Racket 本身也是一门非常年轻优秀的 Scheme 方言。
  - [伯克利 cs61a 课程](https://cs61a.org/)用**Python**来教 SICP，在课程官网可以找到很多有用的资源。[composingprograms](http://composingprograms.com/)是一位伯克利教授做的教学网站，用**Python**来教 SICP，作为 cs61a 的教科书使用。
  - 学习 Lisp 之前可以看看这两篇经典的博文：[Lisp 的本质(The Nature of Lisp)](https://www.cnblogs.com/Leap-abead/articles/762180.html)、[Lisp 的永恒之道](https://www.cnblogs.com/weidagang2046/archive/2012/06/03/tao_of_lisp.html)。让你提前对 Lisp 的魔法有所了解。
- [How to Design Programs(HTDP)](https://book.douban.com/subject/1787103/) 正如它的名字所说，它教你如何有条理地设计计算机程序。这本书使用函数式编程语言 Racket （一门非常年轻优秀的编程语言）来讲解，但是它不是一本教你编程语言的书，它所包含的知识是普适的。[官网免费阅读](https://www.htdp.org/)。
  - 这本书是面向编程入门者的角度来讲解的，所以对于有编程基础的人来说有一些啰嗦，建议跳读。
- [Essentials of Programming Languages(EOPL)](https://book.douban.com/subject/3136252/) Scheme 三剑客之一，助你看透编程语言的本质。
- [Programming Language: Application and Interpretation(PLAI)](https://book.douban.com/subject/11628134/) Scheme 三剑客之一，助你看透编程语言的本质。
- [Concepts, Techniques, and Models of Computer Programming](https://en.wikipedia.org/wiki/Concepts,_Techniques,_and_Models_of_Computer_Programming) 被认为是 SICP 近代继任者，覆盖面稍广于 SICP，但知名度远不及 SICP。带读者领略变成背后的概念和思想。[官方网站](https://www.info.ucl.ac.be/~pvr/book.html)
- [Software Foundations](https://book.douban.com/subject/25712292/) 编程语言理论中的圣经。

下面的资源可能更适合拥有一定编程经验以后再阅读，结合自己的编程经验才能有深刻的理解。

- [设计模式 可复用面向对象软件的基础](https://book.douban.com/subject/1099305/) 设计模式，无人不知吧。
- [冒号课堂 编程范式与 OOP 思想](https://book.douban.com/subject/4031906/) 虽然书名起得不好，但是不妨碍它是一本好书，对编程范式和软件设计思想的阐述非常深刻。相对容易理解。
- [Stanford CS107 Programming Paradigms(编程范式)](http://open.163.com/special/opencourse/paradigms.html)
- [Clean Architecture：软件架构与设计匠艺](https://book.douban.com/subject/26915970/)
- [领域驱动设计:软件核心复杂性应对之道](https://book.douban.com/subject/5344973/) （业务）编程的本质是对真实世界的抽象和建模，本书帮助读者理解业务与代码之间的联系，以及如何设计业务代码。

# 编译原理

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

- [cs143](http://web.stanford.edu/class/cs143/) 斯坦福的编译器课程。
  这个课程曾经有 Coursera 的版本，但是后来下架了。在[最好的编译器课程 - 知乎](https://zhuanlan.zhihu.com/p/28823258)可以下载 Coursera 版本的视频。
- [编译原理](https://book.douban.com/subject/3296317/) 龙书，领域经典。[习题答案](https://github.com/fool2fish/dragon-book-exercise-answers)。
- [Parsing Techniques](https://book.douban.com/subject/4291903/)。编译器前端。
- [Engineering a Compiler](https://book.douban.com/subject/5288601/)。偏向编译器后端。
- [高级编译器设计与实现](https://book.douban.com/subject/1400374/)。鲸书。偏向编译器后端。

# 计算机网络

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

- [计算机网络 自顶向下方法](https://book.douban.com/subject/26176870/) 经典教材，计网入门推荐基本都是这个。官网有[补充资料](https://wps.pearsoned.com/ecs_kurose_compnetw_6/216/55463/14198700.cw/index.html)。
- [TCP/IP 详解 卷 1：协议](https://book.douban.com/subject/1088054/) 深入讲解 TCP/IP 的内容。不适合入门。如果是相关专业或者岗位的话，需要通过这套书籍来进阶。

# 数据库

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

- [Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems](https://book.douban.com/subject/26197294/) 严格来说这本书讲的不是数据库，而是设计数据依赖型应用（data-intensive applications，比如通过网络传输、存储、处理数据的应用）的原则和权衡，它能加深你对数据存储、处理系统的理解，让你更好地选择不同的数据库产品、设计自己的应用架构。这本书在豆瓣和[美国亚马逊](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321)上都有很高的评价。
  - [DDIA 中文翻译](https://github.com/Vonng/ddia)可作为中文参考。
- [高性能 MySQL](https://book.douban.com/subject/23008813/) 最具代表性的 MySQL 进阶书籍，没有之一。对于要深入学习 MySQL、对其进行调优的同学来说，这本书是必读的。

# 操作系统理论

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

- [Operating Systems: Three Easy Pieces](https://book.douban.com/subject/19973015/) 评价很高的操作系统书。可以在[官网](http://pages.cs.wisc.edu/~remzi/OSTEP/)免费阅读。官网最下面也列举了一些操作系统学习资源。[中文版](https://book.douban.com/subject/33463930/)。
- [Operating Systems: Principles and Practice](http://recursivebooks.com/) 多个知名大学将其作为教科书。
  > 相关知乎回答：[有没有好的操作系统的书？ - 知乎](https://www.zhihu.com/question/31863104)
- [6.828](https://pdos.csail.mit.edu/6.828/2017/schedule.html) MIT 的操作系统课程，经常被推荐。其中的 Xv6 项目可以让学习者动手实践，非常难得。

# 操作系统实践（Linux 运维）

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

- [The Linux Command Line(TLCL)](https://book.douban.com/subject/6806862/)，[官网可下载 PDF](http://linuxcommand.org/tlcl.php)，[中译本](http://billie66.github.io/TLCL/book/) 生动清晰的入门小册，教你通过命令行真正地掌控计算机。非常适合 Linux 入门。在知乎和豆瓣的评价都很高。
- [鸟哥的 Linux 私房菜 - 基础学习篇](https://book.douban.com/subject/4889838/)，[鳥哥的 Linux 私房菜 - 基礎學習篇目錄](http://linux.vbird.org/linux_basic/) 应该很多人听说过这本书了，知识点详尽。知乎上有人说鸟哥的书讲得“太详细”了，以至于阅读起来有点吃力。
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) 命令行的实用技巧。Start 数量惊人。。。

- [Google SRE](https://book.douban.com/subject/26875239/) 来自 Google 的运维书，它讨论如何运维大型软件系统，同时提高可靠性。

- [Docker — 从入门到实践](https://yeasy.gitbooks.io/docker_practice/) 中文入门 docker 的不二之选。不过入门以后最好看官方文档，更加详细。

# UNIX 编程

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

- [UNIX 环境高级编程](https://book.douban.com/subject/1788421/)
- [UNIX 编程艺术](https://book.douban.com/subject/5387401/)

# 工程化

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

## GIT

- [Pro Git](https://git-scm.com/book/en/v2) Git 官网推荐的书。也可以边用边查[Reference](https://git-scm.com/docs)。
- [图解 Git](http://marklodato.github.io/visual-git-guide/index-en.html) 用图片讲解了 Git 的基本操作，适合初学者。
- [廖雪峰的 Git 教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000) 比较靠谱的中文教程。

## 软件工程

- [代码大全](https://book.douban.com/subject/1477390/)
- [敏捷软件开发 原则、模式与实践](https://book.douban.com/subject/1140457/)
- [程序员修炼之道 从小工到专家](https://book.douban.com/subject/5387402/)
- [人月神话](https://book.douban.com/subject/1102259/)
- [现代软件工程讲义（邹欣）](http://www.cnblogs.com/xinz/archive/2011/11/27/2265425.html)
- [代码整洁之道](https://book.douban.com/subject/4199741/)

# 程序员的自我修养

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

- [黑客与画家](https://book.douban.com/subject/6021440/) 被无数人推荐。
- [哥德尔、艾舍尔、巴赫: 集异璧之大成](https://book.douban.com/subject/1291204/) 视角跨越多个领域的奇书。
- [人类简史](https://book.douban.com/subject/25985021/)
- [暗时间](https://book.douban.com/subject/6709809/) 作者刘未鹏，他的[博客](http://mindhacks.cn/)也值得一读。从文章都能感觉到作者是一个善于思考的人，文章经常能给人醍醐灌顶的感觉。
- [经济学原理](https://book.douban.com/subject/1028842/) 权威的经济学科普书籍。不要成为一个只会埋头干活的码农。

# C/C++

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

- [C 程序设计语言](https://book.douban.com/subject/1882483/)
- [C++ Primer](https://book.douban.com/subject/25708312/)
- [Effective C++](https://book.douban.com/subject/1842426/)
- STL: [Effective STL](https://book.douban.com/subject/24534868/) + [STL 源码剖析](https://book.douban.com/subject/1110934/)

更多的资料直接看下面的链接或者上知乎搜索。

- [The Definitive C++ Book Guide and List](https://stackoverflow.com/questions/388242/the-definitive-c-book-guide-and-list)

# Python

- [The Hitchhiker’s Guide to Python!](http://docs.python-guide.org/en/latest/) google 搜索 Python guide，前四位都是它或它的中文翻译。GitHub 仓库的 Star 数量很多。定位是"Python best practices guidebook"。
- [Fluent Python](https://book.douban.com/subject/26278021/) 豆瓣评分最高的 Python 书籍。比较适合进阶。

# Rust

- [The Rust Programming Language](https://doc.rust-lang.org/book/index.html) Rust 官方推荐教材。详尽涵盖了 Rust 的理论基础。最好结合下面实践资料一起学习。
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/index.html) Rust 官方出品的在线练习网站，通过练习来巩固这门语言的知识点。
- [rustlings](https://github.com/rust-lang/rustlings) Rust 官方出品的小练习，帮助你熟悉 Rust 编程，包括代码读、写，以及 Rust 编译器的使用，实践性教程。

# 前端

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

## JavaScript 开发进阶

- [JavaScript for impatient programmers](https://exploringjs.com/impatient-js/toc.html) **它专注于[ECMAScript 这门语言](https://github.com/tc39/ecma262)，并不涉及[Web API](https://developer.mozilla.org/en-US/docs/Web/API)**。它用非常精炼的语言构建了现代 JavaScript 的知识体系（涵盖到 ES2019）。作者[Dr. Axel Rauschmayer](http://dr-axel.de/)的博客也值得关注。
- [JavaScript 高级程序设计](https://book.douban.com/subject/10546125/) 兼顾了语言和 Web API。第三版有点老了，只涵盖 ES5，不过依旧是经典。[2019 年 6 月会出第四版](http://www.wrox.com/WileyCDA/WroxTitle/Professional-JavaScript-for-Web-Developers-4th-Edition.productCd-1119366445.html)。
- [The Modern JavaScript Tutorial](https://javascript.info/) 现代 JavaScript 开发教程。包含了 ECMAScript 语言和重要的 Web API。个人认为它的主要价值在于对重要 Web API 的分类整理与阐释。
- [JavaScript. The Core: 2nd Edition](http://dmitrysoshnikov.com/ecmascript/javascript-the-core-2nd-edition/) 从语言标准的角度讲解了 Prototype、Execution context、lexical environment、Closure 等高级概念，适合编程语言理论爱好者。内容基于 ES6。
- [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS#you-dont-know-js-book-series) 大部分 js 开发者应该都听说过，开源神书，进阶必读。
- [Functional-Light JavaScript](https://github.com/getify/Functional-Light-JS)。将函数式编程思想应用在 JavaScript 开发中。虽然 JavaScript 很难做到“最纯正”的函数式编程，但是本着实用主义的心态，学习多一种编程范式，对于开发者来说是十分有益的，更何况很多前端框架都借鉴了函数式编程思想。
- [Professor Frisby's Mostly Adequate Guide to Functional Programming](https://github.com/MostlyAdequate/mostly-adequate-guide)。同上一本，这两本书应该是 JavaScript 函数式编程书里的首选了。
- [Must-watch videos about javascript](https://github.com/bolshchikov/js-must-watch) JavaScript 视频推荐列表，Star 数量很多。不过内容太多，建议选择感兴趣/重要的来观看。太旧的视频也需要斟酌一下。
- [JSConf](https://www.youtube.com/channel/UCzoVCacndDCfGDf41P-z0iA) JavaScript 技术会议。同样内容太多，建议选择感兴趣/重要的来观看。太旧的视频也需要斟酌一下。可以[按照热度排序](https://www.youtube.com/user/jsconfeu/videos?view=0&flow=grid&sort=p)。

## v8

- [How do I get started with V8 development?](https://medium.com/dailyjs/how-do-i-get-started-with-v8-development-17e976ebe4af) 作者大姐姐是 V8 的开发者，YouTube 上有很多她的演讲。这篇文章提供了很多进入 V8 源码世界的资料。对于 V8 爱好者，她的博客、[讲座](https://medium.com/fhinkel/conference-talks-2017-3c0ed426406f)都值得关注。
  > [YouTube 上有关 V8 的讲座](https://www.youtube.com/results?search_query=JSConf+v8)
- [Vyacheslav Egorov](https://mrale.ph/) 介绍了很多 V8 底层的原理。作者之前是 V8 开发者，现在已经跳槽了。就算不打算学编译器，js 开发者也应该读一读这两篇文章：[Explaining JavaScript VMs in JavaScript - Inline Caches](https://mrale.ph/blog/2012/06/03/explaining-js-vms-in-js-inline-caches.html)， [What's up with monomorphism?](https://mrale.ph/blog/2015/01/11/whats-up-with-monomorphism.html)。
- [Benedikt Meurer's blog](http://benediktmeurer.de/) Benedikt Meurer 是 V8 的开发者之一。
- [How JavaScript works: inside the V8 engine + 5 tips on how to write optimized code](https://blog.sessionstack.com/how-javascript-works-inside-the-v8-engine-5-tips-on-how-to-write-optimized-code-ac089e62b12e) 讲解了 V8 优化执行速度的几种基本方式，了解它们有助于我们理解前端框架内部的优化、写出更加 VM-friendly 的代码。以 Angular 为例，Angular 源码利用[Monomorphic](https://github.com/angular/angular/search?q=Monomorphic&unscoped_q=Monomorphic)来优化代码，Angular 编译出的 JavaScript 也是[VM-friendly](https://blog.mgechev.com/2016/08/14/ahead-of-time-compilation-angular-offline-precompilation/)的。
  > [该专栏](https://blog.sessionstack.com/tagged/tutorial)有更多关于 JavaScript 原理的文章。
- [v8-perf](https://github.com/thlorenz/v8-perf) 收集了关于 v8 的笔记和资源。
- [v8 专题 - 阿里妈妈前端技术周刊](https://segmentfault.com/a/1190000016429026#articleHeader3) 收录了几篇优秀的 v8 文章（**中文**）。

## 前端杂项

- [Learning JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/) 比较新的 JavaScript 设计模式书，而且是开源的。它总结了 JavaScript 在实践中常用的设计模式。作者[Addy Osmani](https://addyosmani.com/)在 Google Chrome 做工程管理。
- [awesome-webpack-cn](https://github.com/webpack-china/awesome-webpack-cn) webpack 学习资料。不过如果可以的话还是直接阅读官方文档吧。
- [冴羽写博客的地方](https://github.com/mqyqingfeng/Blog) 教你一些 JavaScript 的实战常用技巧，比如节流、防抖、类型判断、深浅拷贝、柯里化等等。JavaScript 理论书不会告诉你的使用技巧，这个博客为你总结了很多。这种实战技巧也是频繁的面试考点。虽然作者似乎不是很有名，但是这个博客确实能让读者学会很多，Star 数量也挺高的。
  <!--* [Alloy周刊](http://www.alloyteam.com/alloyshare/weekly/p/latest) 腾讯AlloyTeam的周刊，每周推几篇前端好文，有微信公众号可以关注。-->
- [奇舞周刊](https://weekly.75team.com/) 每周推荐几篇前端精华文章。
- [前端小密圈](https://github.com/jawil/blog) 前端文章推荐列表。很多干货，Star 数量也挺高的。
- [InterviewMap](https://github.com/InterviewMap/InterviewMap) 针对前端的知识点清单，对于查漏补缺非常有用。
- [当你在浏览器中输入 google.com 并且按下回车之后发生了什么？](https://github.com/skyline75489/what-happens-when-zh_CN) 经典面试题的完整回答。下次面试被问到这个问题，你能把面试官答到崩溃。[英文原版仓库](https://github.com/alex/what-happens-when)star 数量很高。
- [How browsers work](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/) 浏览器工作原理。弄懂它是理解前端性能优化的基础。相关中文文章：[中文翻译](https://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/)、[浏览器的渲染原理简介](https://coolshell.cn/articles/9666.html)、[浅析前端页面渲染机制](http://blog.codingplayboy.com/2017/03/29/webpage_render/)。
- [Inside look at modern web browser | Google Developers](https://developers.google.com/web/updates/2018/09/inside-browser-part1)。[中文解析](https://zhuanlan.zhihu.com/p/47407398)。
- 前端性能优化清单：
  - [PageSpeed Insights Rules - Google](https://developers.google.com/speed/docs/insights/rules)
  - [Performance - Google Web Fundamentals](https://developers.google.com/web/fundamentals/performance/why-performance-matters/)
  - [Best Practices for Speeding Up Your Web Site - yahoo](https://developer.yahoo.com/performance/rules.html)
  - [14 Rules for Faster-Loading Web Sites](http://stevesouders.com/hpws/rules.php)
  - [2020 前端性能优化清单](https://www.smashingmagazine.com/2020/01/front-end-performance-checklist-2020-pdf-pages/)
  - [CSS Animation 性能优化](https://www.w3cplus.com/animation/animation-performance.html)
- [Front End Interview Handbook](https://github.com/yangshun/front-end-interview-handbook) 提供了前端常见面试问题的答案。它只是面试题的集合，而不是系统化的知识总结，因此只适用于准备面试和查漏补缺。
- [Front-end development handbook](https://github.com/FrontendMasters/front-end-handbook-2018) 对于前端的基础知识点，提供了很多优质的资源链接。
- [The Super Tiny Compiler](https://github.com/jamiebuilds/the-super-tiny-compiler)，或者[它的中文翻译版](https://github.com/starkwang/the-super-tiny-compiler-cn)。 Node、Typescript、Babel 以及**大部分现代前端框架**都和编译器有着密切的关系，要成为一流的前端必须了解编译器的知识。更何况编译器的知识在各个语言都是基本通用的。
  > [原作者](https://github.com/jamiebuilds)、[翻译者](https://github.com/starkwang)、[推荐者](https://www.zhihu.com/question/49043143/answer/113970082)都是大牛。。。
- [freeCodeCamp](https://learn.freecodecamp.org/) 开源、非盈利的在线学习网站。它的主要内容是前端基础知识。这个网站的最大特点是在线评测，这种即时反馈对于学习者来说是非常有帮助的。该仓库的 Star 数量在 github 上[排名第一](https://gitstar-ranking.com/repositories)。
- [Web 安全](https://web.stanford.edu/class/cs253/) 斯坦福大学的公开课。内容非常贴近实际的 Web 应用。

## Angular

官方文档就不需要提了，这里只列举用于进阶的资料。

- [Angular In Depth](https://blog.angularindepth.com/) 应该是最深入、访问量最大的 Angular 专栏了。经常对 Angular 进行源码级别的剖析。
- [Trotyl Yu](https://www.zhihu.com/people/trotyl/answers) 知乎里最活跃的 Angular 答主之一（还有[雪狼](https://www.zhihu.com/people/alpha-gde/answers)和[VTHINKXIE](https://www.zhihu.com/people/vthinkxie/posts)），他的专栏[Angular News](https://zhuanlan.zhihu.com/angular-news) [禅与摩托车轮子维修艺术](https://zhuanlan.zhihu.com/trotyl)都是 Angular 干货。
  > 大佬们都在[为什么前端讨论的都是各种 react，vue 源码解析，渲染机制等，没人讨论 angular？ - 知乎](https://www.zhihu.com/question/274940977)回答了。
- [Angular 资料获取不完全指南](https://zhuanlan.zhihu.com/p/36385830) 列举了一些有名的博客，经常查找 Angular 资料的同学应该很熟悉这些博客了。
- [Angular Articles](https://zhuanlan.zhihu.com/p/32818978) 作者同上，Angular 文章推荐。
- [Angular 设计文档](https://drive.google.com/drive/folders/0BxgtL8yFJbacQmpCc1NMV3d5dnM) 官方设计文档，但是感觉有点缺乏维护，有一些东西很旧了。不过还是有很多优质的设计文档的，需要挖掘。
- 经常有 Angular 团队成员出席这些会议：
  - [ng-conf](https://www.youtube.com/channel/UCm9iiIfgmVODUJxINecHQkA)
  - [AngularConnect](https://www.youtube.com/channel/UCzrskTiT_ObAk3xBkVxMz5g)
  - [AngularMIX](https://www.youtube.com/channel/UCnUpEUN4V3iJxoUximdr6Nw)
- [awesome-angular](https://github.com/gdi2290/awesome-angular) 很全面的 Angular 学习资源列表。缺点是有点杂。建议先看[Angular Connect 小节](https://github.com/gdi2290/awesome-angular#angular-connect)精选的会议视频。
- [Learn Angular from Top Articles for the Past Year (v.2018)](https://medium.mybridge.co/learn-angular-from-top-articles-for-the-past-year-v-2018-45d69437c016) 这个专栏专门收集最受欢迎的技术文章、公开课，每个月或每一年更新一次。他们还做了 React、Node.js、python、machine learning 等技术的排行。
- [RxJS Marbles](http://rxmarbles.com/) 通过交互式动画来学习 Rx Observables。

## Vue

入门直接看官方文档就好，这里只列举用于进阶的资料。

- [Vue 技术内幕](https://github.com/HcySunYang/vue-design) 逐行级别的源码分析，并且会一直跟进 Vue 的更新。该作者在去年写的一篇文章也推荐阅读：[Vue2.1.7 源码学习](http://hcysun.me/2017/03/03/Vue%E6%BA%90%E7%A0%81%E5%AD%A6%E4%B9%A0/)。
- [Vue.js 源码分析](https://github.com/answershuto/learnVue)
- [Vue.js 技术揭秘](https://github.com/ustbhuangyi/vue-analysis)

# 机器学习

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

书籍：

- [Artificial Intelligence: A Modern Approach](https://book.douban.com/subject/6730363/) 经典教科书。它的[官网](http://aima.cs.berkeley.edu/)有补充资料。
- [Pattern Recognition and Machine Learning](https://book.douban.com/subject/2061116/) 领域经典。这是其中的[算法实现(matlab)](http://prml.github.io/)。
- [Deep Learning](https://github.com/exacity/deeplearningbook-chinese) 被誉为“深度学习圣经”。[中文版](https://github.com/exacity/deeplearningbook-chinese)已经出版并且开源。
- [Machine learning: a propability perspective](https://book.douban.com/subject/10758624/) 领域经典。
- [机器学习（周志华）](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/MLbook2016.htm) 国内首屈一指的机器学习教科书。即使我的老师没有指定过教课书，但是同学们还是不约而同地买了这本书，可见其受欢迎程度。
- [The Elements of Statistical Learning : Data Mining, Inference, and Prediction](https://web.stanford.edu/~hastie/ElemStatLearn/) 领域经典。
- [统计学习方法](https://book.douban.com/subject/10590856/) 国内非常有名的机器学习书。虽然内容没有《机器学习（周志华）》那么全面，但是它的算法讲得更深入一些。

> 其他机器学习书单：[机器学习经典书籍](http://suanfazu.com/t/topic/15) [人工智能入门书单（附 PDF 链接）](http://www.sohu.com/a/218561098_355140)

课程：

- [吴恩达机器学习](https://study.163.com/course/courseMain.htm?courseId=1004570029) 它翻译自 Andrew Ng 2017-2018 年在[coursera](https://www.coursera.org/learn/machine-learning)的公开课。在 cs229 的基础上降低了一些难度，适合入门。
  - [中文笔记](https://github.com/fengdu78/Coursera-ML-AndrewNg-Notes) 文字比视频更加适合复习和查阅。
- [cs229](http://cs229.stanford.edu/syllabus.html) 上面这个课程的加强版。这是斯坦福的课程，通过看 course notes 来学习。
  - [UFLDL Tutorial](http://ufldl.stanford.edu/tutorial/) 斯坦福提供的 Unsupervised Feature Learning and Deep Learning Tutorial，可以作为参考小册。
- [cs231n](http://cs231n.github.io/) 来自斯坦福的精品课程，先讲解深度学习（卷积神经网络），然后将它应用于计算机视觉。有 course notes 和视频。[CS231n 官方笔记授权翻译](https://zhuanlan.zhihu.com/p/21930884)。
- [CS230](https://web.stanford.edu/class/cs230/) 吴恩达的深度学习课程，课程内容由[coursera](https://www.deeplearning.ai/)上的 5 门课组成：神经网络与深度学习、提升深度神经网络、机器学习项目的策略、卷积神经网络、序列模型。
  - [网易云课堂翻译](https://mooc.study.163.com/smartSpec/detail/1001319001.htm)
  - [视频资源以及中文笔记](https://github.com/fengdu78/deeplearning_ai_books)
- [台湾大学李宏毅的课程](http://speech.ee.ntu.edu.tw/~tlkagk/courses.html) 在知乎上很受欢迎。中文授课。
- [台大林轩田《机器学习基石》和《机器学习技法》课程](https://github.com/RedstoneWill/NTU-HsuanTienLin-MachineLearning)

其他机器学习资源合集：

- [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) 机器学习的 Awesome List，Star 数超高。README 按照语言分类，列举各个语言下的机器学习工具（这个列表是应该是为专业人员建立的），非常完备，但是更适合已经入门者。其他文档分别推荐了博客、书籍、公开课、会议。
- [Machine learning Resources](https://github.com/allmachinelearning/MachineLearning) 收集机器学习资源的 GitHub 仓库，列举了很多入门资料。
- [Deep Learning Papers Reading Roadmap](https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap) 这个 repository 收集了深度学习各个领域中最基础、重要的研究论文，进阶者可以从这里入手。star 数量很高。
- [Distill](https://distill.pub/) Distill 是一个期刊平台，使用了交互式、视觉化的用户界面，注重对机器学习研究成果的理解与诠释。
- [deeplearning.net](http://deeplearning.net/reading-list/) 给出了很多基础性的论文。

> 相关知乎问题：[机器学习该怎么入门？ - 知乎](https://www.zhihu.com/question/20691338) [普通程序员如何正确学习人工智能方向的知识？ - 知乎](https://www.zhihu.com/question/51039416) [深度学习如何入门？ - 知乎](https://www.zhihu.com/question/26006703) [YouTube 上有哪些计算机方面的值得推荐的公开课？ - 知乎](https://www.zhihu.com/question/49071324)

- [deepo](https://github.com/ufoym/deepo) 轻松在 Docker 上搭建开发环境。
- [Convolution arithmetic](https://github.com/vdumoulin/conv_arithmetic) 用 动图+论文 详细解释了卷积和逆卷积的过程。

## TensorFlow

- [TensorFlow Examples](https://github.com/aymericdamien/TensorFlow-Examples)
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow)

## PyTorch

- [PyTorch Examples](https://github.com/pytorch/examples)
- [Pytorch Tutorial](https://github.com/yunjey/pytorch-tutorial)

# 数学基础

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

## Optimization (优化理论)

[相关推荐](https://www.zhihu.com/question/25120338)里少不了这两本：

- Convex Optimization. Stephen Boyd, 2004, Cambridge university press.
- Numerical Optimization. Nocedal, J. Wright, S. 2006, Springer.

## 线性代数

- [Introduction to Linear Algebra, Fifth Edition](http://math.mit.edu/~gs/linearalgebra/)
- [Linear Algebra - MIT 公开课](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/) 这个是[OCW Scholar(Open CourseWare Scholar)](https://ocw.mit.edu/courses/ocw-scholar/)版本，专门为自学者收编，除了课堂视频和课堂讲稿以外，还提供了习题讲解视频、作业和答案等资源，更加完备。
- [Linear Algebra and Its Applications](https://book.douban.com/subject/1425950/)

## 概率与统计

- [All of Statistics](https://book.douban.com/subject/2285151/) 备受推荐。内容很好地涵盖了机器学习所需，又不至于太臃肿。在[官网](http://www.stat.cmu.edu/~larry/all-of-statistics/)可以下载 pdf 版本。
- [概率论与数理统计](https://book.douban.com/subject/2201479/) 陈希孺院士的书在豆瓣和知乎都好评如潮。
- [概率论及其应用](https://book.douban.com/subject/1785817/)

# 杂项

<font size="2" style="margin-left:10px;">[回到目录 ↑](#目录)</font>

- [RegExr](https://regexr.com/) 学习、测试正则表达式的神器。
- [快捷键大全](http://mykeys.sinaapp.com/index.php) 用好手上的工具也是很重要的。

## 清单

- [What is the single most influential book every programmer should read?](http://bestprogrammingbooks.com/updated-100-influential-stackoverflow-programming-books/) [StackOverflow 上一个很火的问题](https://stackoverflow.com/questions/1711/what-is-the-single-most-influential-book-every-programmer-should-read)的更新版，里面都是经典书籍。
- [掘金翻译计划](https://github.com/xitu/gold-miner) 翻译了很多优质文章，涉及到各个编程领域。
- [awesome lists](https://github.com/sindresorhus/awesome) 非常全面资源清单，不仅包括学习资源，而且涵盖了工具资源。
- [System Design Primer](https://github.com/donnemartin/system-design-primer) 系统设计入门。这是后端系统、架构通识的清单，不局限于任何后端语言。并且提供了帮助记忆的工具[Anki flashcard decks](https://github.com/donnemartin/system-design-primer#anki-flashcards)。
- [Computer Science Knowledge Study Plan](https://github.com/jwasham/coding-interview-university) **计算机科学**的知识，是底层码农通往软件工程师的阶梯。这个清单详尽列举了**计算机科学**的知识点以及学习资源。
- [技术面试必备基础知识](https://github.com/CyC2018/CS-Notes) 涵盖算法、操作系统、计算机网络、数据库、系统设计、Java。作者应该是站在 Java 后端开发的角度来梳理的。

## 公开课

- [MIT 公开课排行榜](https://ocw.mit.edu/courses/most-visited-courses/) 选择需要的来学习吧。
- [Stanford Engineering Everywhere](https://see.stanford.edu/Course) 斯坦福公开课项目。
