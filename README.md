# 最受推荐的书籍和网站
收集最受推荐的书籍和网站，主要关注前端开发、计算机基础、机器学习的内容。

收录内容的主要来源是：知乎、StackOverflow上的高分回答，以及在GitHub上的其他收集类项目。

收录的依据主要是：在领域内的经典程度、作者权威性、推荐它的回答是否是高分回答、有多少答主推荐它、谷歌搜索排名、GitHub仓库的Star数量、豆瓣评分和评价、我听闻到它的次数和评价好坏等等。
不放心的同学可以在阅读之前在知乎或Google搜索相关的评价。

**如果可以，尽量选择英文版的材料来阅读！**

> 这个列表上的大部分内容我都没有读完，这个列表仅仅用于满足自己的收集癖好。


****
以下是收录的内容：

# 前端

## JavaScript开发进阶
* [Speaking JavaScript](http://speakingjs.com/es5/index.html) 相信很多js开发者都看过这个作者[Dr. Axel Rauschmayer](http://dr-axel.de/)的博客。这本书具有完整的ECMAScript知识体系，**它专注于[ECMAScript这门语言](https://github.com/tc39/ecma262)，并不涉及[Web API](https://developer.mozilla.org/en-US/docs/Web/API)**。ES6的内容被专门收集到另一本书Exploring ES6。
* [JavaScript高级程序设计](https://book.douban.com/subject/10546125/) 兼顾了语言和Web API。第三版有点老了，只涵盖ES5，不过依旧是经典，2018年9月会出第四版。
* [JavaScript 标准参考教程 - 阮一峰](https://javascript.ruanyifeng.com/) 兼顾了语言和Web API，内容很新，可以看作是高程的持续更新版。前端面试会问的**基础知识点**基本都可以在这里找到。不过有一些讲解得不是非常详尽，追求完美的读者，可以在阅读的过程中，去MDN或《JavaScript高级程序设计》找到相同的知识点来阅读。ES6的内容被专门收集到另一本书ECMAScript 6 入门。
* [JavaScript. The Core: 2nd Edition](http://dmitrysoshnikov.com/ecmascript/javascript-the-core-2nd-edition/) 详细讲解了Prototype、Execution context、lexical environment、Closure等高级概念。内容非常新，基于ES6。
* [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS#you-dont-know-js-book-series) 大部分js开发者应该都听说过，开源神书，进阶必读。
* [The Super Tiny Compiler](https://github.com/jamiebuilds/the-super-tiny-compiler)，或者[它的中文翻译版](https://github.com/starkwang/the-super-tiny-compiler-cn)。 Node、Typescript、Babel以及**大部分现代前端框架**都和编译器有着密切的关系，要成为一流的前端必须了解编译器的知识。更何况编译器的知识在各个语言都是基本通用的。
  > [原作者](https://github.com/jamiebuilds)、[翻译者](https://github.com/starkwang)、[推荐者](https://www.zhihu.com/question/49043143/answer/113970082)都是大牛。。。
* [Must-watch videos about javascript](https://github.com/bolshchikov/js-must-watch) JavaScript视频推荐列表，Star数量很多。不过内容太多，建议选择感兴趣/重要的来观看。太旧的视频也需要斟酌一下。
* [JSConf](https://www.youtube.com/channel/UCzoVCacndDCfGDf41P-z0iA) JavaScript技术会议。同样内容太多，建议选择感兴趣/重要的来观看。太旧的视频也需要斟酌一下。可以[按照热度排序](https://www.youtube.com/user/jsconfeu/videos?view=0&flow=grid&sort=p)。

## ES6
* [Exploring ES6](http://exploringjs.com/es6.html) 同样是[Dr. Axel Rauschmayer](http://dr-axel.de/)的书，可以看作是Speaking JavaScript的ES6增量更新包。
* [ECMAScript 6 入门 - 阮一峰](http://es6.ruanyifeng.com/) 通过例子来学习ES6，可以看作是JavaScript 标准参考教程的ES6增量更新包。中文看起来比较亲切。

## v8
* [How do I get started with V8 development?](https://medium.com/dailyjs/how-do-i-get-started-with-v8-development-17e976ebe4af) 作者大姐姐是V8的开发者，YouTube上有很多她的演讲。这篇文章提供了很多进入V8源码世界的资料。对于V8爱好者，她的博客、[讲座](https://medium.com/fhinkel/conference-talks-2017-3c0ed426406f)都值得关注。
  > [YouTube上有关V8的讲座](https://www.youtube.com/results?search_query=JSConf+v8)
* [Vyacheslav Egorov](https://mrale.ph/) 介绍了很多V8底层的原理。作者之前是V8开发者，现在似乎跳槽了。就算不打算学编译器，js开发者也应该读一读这两篇文章：[Explaining JavaScript VMs in JavaScript - Inline Caches](https://mrale.ph/blog/2012/06/03/explaining-js-vms-in-js-inline-caches.html)， [What's up with monomorphism?](https://mrale.ph/blog/2015/01/11/whats-up-with-monomorphism.html)。
* [How JavaScript works: inside the V8 engine + 5 tips on how to write optimized code](https://blog.sessionstack.com/how-javascript-works-inside-the-v8-engine-5-tips-on-how-to-write-optimized-code-ac089e62b12e) 讲解了V8优化执行速度的几种基本方式，了解它们有助于我们写出更加V8 friendly的代码。以Angular为例，Angular源码利用[Monomorphic](https://github.com/angular/angular/search?q=Monomorphic&unscoped_q=Monomorphic)来优化代码，Angular编译出的JavaScript也是[VM-friendly](https://blog.mgechev.com/2016/08/14/ahead-of-time-compilation-angular-offline-precompilation/)的。
  > 他的[专栏](https://blog.sessionstack.com/tagged/tutorial)有更多关于JavaScript原理的文章。

## 前端实践指南
* [Learning JavaScript Design Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/) 比较新的JavaScript设计模式书，而且是开源的。它总结了JavaScript在实践中常用的设计模式。作者[Addy Osmani](https://addyosmani.com/)在Google Chrome做工程管理。
* [awesome-webpack-cn](https://github.com/webpack-china/awesome-webpack-cn) webpack学习资料。不过如果可以的话还是直接阅读官方文档吧。
* 前端性能优化：知识点比较零散，可以看看清单类的博客，比如[2018 前端性能优化清单](https://juejin.im/post/5a966bd16fb9a0635172a50a)，或者[Google Web Fundamentals](https://developers.google.com/web/fundamentals/)的"Performance"章节。
* [冴羽写博客的地方](https://github.com/mqyqingfeng/Blog) 教你一些JavaScript的实战常用技巧，比如节流、防抖、类型判断、深浅拷贝、柯里化等等。JavaScript理论书不会告诉你的使用技巧，这个博客为你总结了很多。这种实战技巧也是频繁的面试考点。虽然作者似乎不是很有名，但是这个博客确实能让读者学会很多，Star数量也挺高的。
* [Alloy周刊](http://www.alloyteam.com/alloyshare/weekly/p/latest) 腾讯AlloyTeam的周刊，每周推几篇前端好文，有微信公众号可以关注。
* [前端小密圈](https://github.com/jawil/blog) 前端文章推荐列表。很多干货，Star数量也挺高的。

## Angular
官方文档就不需要提了，这里只列举用于进阶的资料。
* [Angular In Depth](https://blog.angularindepth.com/) 应该是最深入、访问量最大的Angular专栏了。经常对Angular进行源码级别的剖析。
* [Trotyl Yu](https://www.zhihu.com/people/trotyl/answers) 知乎里最活跃的Angular答主之一（还有[雪狼](https://www.zhihu.com/people/alpha-gde/answers)和[VTHINKXIE](https://www.zhihu.com/people/vthinkxie/posts)），它的专栏[Angular News](https://zhuanlan.zhihu.com/angular-news) [禅与摩托车轮子维修艺术](https://zhuanlan.zhihu.com/trotyl)都是Angular干货。
  > 大佬们都在[为什么前端讨论的都是各种react，vue源码解析，渲染机制等，没人讨论angular？ - 知乎](https://www.zhihu.com/question/274940977)发言了，哈哈有点意思。
* [Angular资料获取不完全指南](https://zhuanlan.zhihu.com/p/36385830) 列举了一些有名的博客，经常查找Angular资料的同学应该很熟悉这些博客了。
* [Angular Articles](https://zhuanlan.zhihu.com/p/32818978) 作者同上，Angular文章推荐。
* [Angular设计文档](https://drive.google.com/drive/folders/0BxgtL8yFJbacQmpCc1NMV3d5dnM) 官方设计文档，但是感觉有点缺乏维护，有一些东西很旧了。不过还是有很多优质的设计文档的，需要挖掘。
* 经常有Angular团队成员出席这些会议：
  * [ng-conf](https://www.youtube.com/channel/UCm9iiIfgmVODUJxINecHQkA)
  * [AngularConnect](https://www.youtube.com/channel/UCzrskTiT_ObAk3xBkVxMz5g)
  * [AngularMIX](https://www.youtube.com/channel/UCnUpEUN4V3iJxoUximdr6Nw)
* [awesome-angular](https://github.com/gdi2290/awesome-angular) 很全面的Angular学习资源列表。缺点是有点杂。建议先看[Angular Connect小节](https://github.com/gdi2290/awesome-angular#angular-connect)精选的会议视频。

* [Learn Angular from Top Articles for the Past Year (v.2018)](https://medium.mybridge.co/learn-angular-from-top-articles-for-the-past-year-v-2018-45d69437c016) 这个专栏专门收集最受欢迎的技术文章、公开课，每个月或每一年更新一次。他们还做了React、Node.js、python、machine learning等技术的排行。
* [RxJS Marbles](http://rxmarbles.com/) 通过交互式动画来学习Rx Observables。

# 算法
* [Introduction to Algorithms](https://book.douban.com/subject/3904676/) 推荐率最高的算法书。经典、全面、深入。不过对于入门者，它的难度和容量可能有点大。
* [Algorithms](https://book.douban.com/subject/19952400/) 也是经典教材，评价也很高。据反映，它的涵盖面没有Introduction to Algorithms广和深，但是工程中的常见的算法都能找到，讲解更加易懂。
* [Algorithms(算法概论)](https://book.douban.com/subject/1996256/) 相对于Introduction to Algorithms和Algorithms，这本书很薄，但是它的讲解简单优美有趣，适合初学者。
* [Top 10 algorithms in Interview Questions](https://www.geeksforgeeks.org/top-10-algorithms-in-interview-questions/) geeksforgeeks有很多常用数据结构、算法的文章。这篇文章以及geeksforgeeks适合短期复习的同学。

# 计算机基础
* [深入理解计算机系统(CSAPP)](https://book.douban.com/subject/26912767/) 神书，要被捧上天了（非贬义）。
* [计算机程序的构造和解释(SICP)](https://book.douban.com/subject/1148282/) [官网HTML版](https://mitpress.mit.edu/sicp/) [优化电子版](https://sicpebook.wordpress.com/) 神书，在豆瓣和知乎搜索一下。
* [编码 隐匿在计算机软硬件背后的语言](https://book.douban.com/subject/4822685/) 通俗易懂，面向入门者，近乎科普。评价很高，经常被推荐。
* [程序员的自我修养](https://book.douban.com/subject/3652388/) 讲解了一个程序在其生命周期里会碰到的种种事物。国人写的书。经常被推荐。
* 有关计算机组成原理的书待收录。
* 计算机体系结构：[计算机组成与设计 硬件/软件接口](https://book.douban.com/subject/26604008/)，[计算机体系结构 量化研究方法](https://book.douban.com/subject/7006537/)这两本书作者是一样的，但内容不一样。只要是推荐这方面的书的问题，少不了这两本。我上计算机组成原理课的时候用的就是前面那本书，虽然内容听起来很可怕，但是英文版读起来真的很好懂（只要你英语过关）。
  > 参考这两个知乎问题：[有哪些不错的介绍计算机体系结构的书籍？](https://www.zhihu.com/question/19897585)，[计算机体系结构这门课的主要内容是什么？ 如何自学？](https://www.zhihu.com/question/37330125)

# 操作系统理论
* [Operating Systems: Three Easy Pieces](https://book.douban.com/subject/19973015/) 评价很高的操作系统书。可以在[官网](http://pages.cs.wisc.edu/~remzi/OSTEP/)免费阅读。官网最下面也列举了一些操作系统学习资源。
* [Operating Systems: Principles and Practice](http://recursivebooks.com/) 多个知名大学将其作为教科书。
> 相关知乎回答：[有没有好的操作系统的书？ - 知乎](https://www.zhihu.com/question/31863104)
* [6.828](https://pdos.csail.mit.edu/6.828/2017/schedule.html) MIT的操作系统课程，经常被推荐。其中的Xv6项目可以让学习者动手实践，非常难得。

# 操作系统实践（Linux运维）
* [The Linux Command Line(TLCL)](https://book.douban.com/subject/6806862/)，[官网可下载PDF](http://linuxcommand.org/tlcl.php)，[中译本](http://billie66.github.io/TLCL/book/) 生动清晰的入门小册，教你通过命令行真正地掌控计算机。非常适合Linux入门。在知乎和豆瓣的评价都很高。
* [鸟哥的Linux私房菜 - 基础学习篇](https://book.douban.com/subject/4889838/)，[鳥哥的 Linux 私房菜 - 基礎學習篇目錄](http://linux.vbird.org/linux_basic/) 应该很多人听说过这本书了，知识点详尽。知乎上有人说鸟哥的书讲得“太详细”了，以至于阅读起来有点吃力。
* [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) 命令行的实用技巧。Start数量惊人。。。

# 编译原理
* [cs143](http://web.stanford.edu/class/cs143/) 斯坦福的编译器课程。
  这个课程曾经有Coursera的版本，但是后来下架了。在[最好的编译器课程 - 知乎](https://zhuanlan.zhihu.com/p/28823258)可以下载Coursera版本的视频。
* [编译原理](https://book.douban.com/subject/3296317/) 龙书，领域经典。

# GIT
[Pro Git](https://git-scm.com/book/en/v2)
[图解Git](http://marklodato.github.io/visual-git-guide/index-en.html)
[廖雪峰的Git教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

# 机器学习
[Artificial Intelligence: A Modern Approach](http://aima.cs.berkeley.edu/) 已有纸质书
[Pattern Recognition and Machine Learning](http://prml.github.io/)
[Deep Learning](https://github.com/exacity/deeplearningbook-chinese)
[Machine learning: a propability perspective](https://mitpress.mit.edu/books/machine-learning-0)
[机器学习（周志华）](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/MLbook2016.htm)
[The Elements of Statistical Learning : Data Mining, Inference, and Prediction](https://web.stanford.edu/~hastie/ElemStatLearn/)
[统计学习方法](https://book.douban.com/subject/10590856/)

[机器学习经典书籍](http://suanfazu.com/t/topic/15)
[人工智能入门书单（附PDF链接）](http://www.sohu.com/a/218561098_355140)

[吴恩达机器学习](https://study.163.com/course/courseMain.htm?courseId=1004570029) 这个翻译自Andrew Ng 2017-2018年在[coursera](https://www.coursera.org/learn/machine-learning)的公开课。在cs229的基础上降低了一些难度，适合入门。
[cs229](http://cs229.stanford.edu/syllabus.html) 上面这个课程的加强版。这是斯坦福的课程，通过看course notes来学习。
[UFLDL Tutorial](http://ufldl.stanford.edu/tutorial/) 斯坦福提供的Unsupervised Feature Learning and Deep Learning Tutorial，可以作为参考小册。
[cs231n](http://cs231n.github.io/) 来自斯坦福的精品课程，有course notes和视频。[CS231n官方笔记授权翻译](https://zhuanlan.zhihu.com/p/21930884)。
[台湾大学李宏毅的课程](http://speech.ee.ntu.edu.tw/~tlkagk/courses.html) 在知乎上很受欢迎。

[Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) 机器学习的Awesome List，Star数超高。README按照语言分类，列举机器学习工具，这个列表是应该是为专业人员建立的。其他文档分别推荐了博客、书籍、公开课、会议。非常完备，但是更适合已经入门者。
[Machine learning Resources](https://github.com/allmachinelearning/MachineLearning) 收集机器学习资源的GitHub仓库，列举了很多入门资料。

> 相关知乎问题：[机器学习该怎么入门？ - 知乎](https://www.zhihu.com/question/20691338) [普通程序员如何正确学习人工智能方向的知识？ - 知乎](https://www.zhihu.com/question/51039416) [深度学习如何入门？ - 知乎](https://www.zhihu.com/question/26006703) [YouTube 上有哪些计算机方面的值得推荐的公开课？ - 知乎](https://www.zhihu.com/question/49071324)

# Optimization (优化理论)
I. Convex Optimization. Stephen Boyd, 2004, Cambridge university press.
II. Numerical Optimization. Nocedal, J. Wright, S. 2006, Springer.
链接：https://www.zhihu.com/question/28438145/answer/118858220

# 线性代数
[Introduction to Linear Algebra, Fifth Edition](http://math.mit.edu/~gs/linearalgebra/)
[Linear Algebra - MIT公开课](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/) 这个是[OCW Scholar(Open CourseWare Scholar)](https://ocw.mit.edu/courses/ocw-scholar/)版本，专门为自学者收编，除了课堂视频和课堂讲稿以外，还有习题讲解视频、作业和答案等资源，更加完备。
[Linear Algebra and Its Applications](https://book.douban.com/subject/1425950/) 已有纸质书

# 概率与统计
[All of Statistics](http://www.stat.cmu.edu/~larry/all-of-statistics/)
[概率论与数理统计](https://book.douban.com/subject/2201479/)
[概率论及其应用](https://book.douban.com/subject/1785817/)


# 书单
[What is the single most influential book every programmer should read?](https://stackoverflow.com/questions/1711/what-is-the-single-most-influential-book-every-programmer-should-read)

# C++
[The Definitive C++ Book Guide and List](https://stackoverflow.com/questions/388242/the-definitive-c-book-guide-and-list)

STL源码剖析 已有纸质书

# 计网
计算机网络 自顶向下方法 已有纸质书 [课外资料](https://wps.pearsoned.com/ecs_kurose_compnetw_6/216/55463/14198700.cw/index.html)

# 软件工程
## 现代软件工程讲义（邹欣）
http://www.cnblogs.com/xinz/archive/2011/11/27/2265425.html

## 代码大全2

## 敏捷软件开发
https://book.douban.com/subject/1140457/

## 人月神话

# 刘未鹏
http://mindhacks.cn/
暗时间

# 黑客与画家

# docker
[Docker — 从入门到实践](https://yeasy.gitbooks.io/docker_practice/)

# 公开课
[MIT公开课排行榜](https://ocw.mit.edu/courses/most-visited-courses/) 都是经典，第一个线性代数是经典中的经典。选择需要的学习吧。

# 快捷键
[快捷键大全](http://mykeys.sinaapp.com/index.php) 用好手上的工具也是很重要的。