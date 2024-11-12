[TOC]



# reference-books

## 书籍（books）

### 计算机基础

- [《Lex与Yacc》中文版.pdf](books/compiler-principles/lex-and-yacc_ZH_CN/Lex-and-Yacc-Chinese.pdf)
- [《Lex与Yacc》中文原书代码](books/compiler-principles/lex-and-yacc_ZH_CN/source-code)



### 版本控制（version control）

- [git官方中文用户手册.pdf](books/version-control/git中文用户手册.pdf)

### 编程语言

- Bash/Shell
  - [Bash在线简易中文教程](books/programming-language/bash/bash-tutorial)
- C语言
  - [《C Primer Plus》第六版中文版原书代码和习题答案](book-code/programming-language/cpp-primer-plus-6th)
- Golang
  - [《The Go Programming Language》](books/programming-language/golang/gopl)：《Go语言圣经》英文原版，[下载及在线阅读地址]([https://www.gopl.io/)
  - [《Go语言圣经》中文版 - 柴树杉翻译](books/programming-language/golang/gopl-zh) ：Go语言圣经 [《The Go Programming Language》](http://gopl.io/) 中文版本，仅供学习交流之用。对于希望学习CGO、Go汇编语言等高级用法的同学，我们推荐[《Go语言高级编程》](https://github.com/chai2010/advanced-go-programming-book)开源图书。如果希望深入学习Go语言语法树结构，可以参考[《Go语法树入门——开启自制编程语言和编译器之旅》](https://github.com/chai2010/go-ast-book)。
  - [《Go语言高级编程》中文书 - 柴树杉](books/programming-language/golang/advanced-go-programming)
  - [《Go语言定制指南》中文书 - 柴树杉](books/programming-language/golang/go-ast) ：原名《Go语法树入门》。Go语法树是Go语言源文件的另一种语义等价的表现形式。而Go语言自带的`go fmt`和`go doc`等命令都是在Go语法树的基础之上分析工具。因此将Go语言程序作为输入数据，让我们语法树这个维度重新审视Go语言程序，我们将得到创建Go语言本身的技术。Go语法树由标准库的`go/ast`包定义，它是在`go/token`包定义的词法基础之上抽象的语法树结构。本书简单介绍语法树相关包的使用。如果想从头实现一个玩具Go语言可以参考[《从头实现µGo语言》](https://github.com/chai2010/ugo-compiler-book)。
  - [《Go 入门指南》](books/programming-language/golang/the-way-to-go_ZH_CN)：《The Way to Go》的中文翻译版本。

- Rust
  - [《Rust Primer》中文版](books/programming-language/rust/RustPrimer-CN)：[在线阅读地址](https://rustcc.gitbooks.io/rustprimer/content/)
  - [《Learn Rust by writing Entirely Too Many Linked Lists》](books/programming-language/rust/too-many-lists)

### 数据库

- [《设计数据密集型应用》DDIA中文版](books/databases/ddia-cn)

- [《设计数据密集型应用》DDIA中文版 - 逐章精读](books/databases/ddia-cn-notes)
- [《ClickHouse原理解析与应用实践》原书代码](book-code/databases/clickhouse/clickhouse-principle-analysis-and-practice)



### AI

#### 1）零基础入门

- 《Easy RL：强化学习教程》，作者：王琦，杨毅远，江季

  > 源自3门百万播放量的经典公开课！GitHub Star 3.3k+！多位强化学习领域大咖亲笔推荐！这本《Easy RL：强化学习教程》的主要内容源自B站3门累计播放量破百万的强化学习课程：李宏毅“深度强化学习”、周博磊“强化学习纲要”、李科浇“世界冠军带你从零实践强化学习”，由来自中科院、清华、北大的Datawhale成员合著而成。此外，这本书还结合编著者自身学习体验中的难点和重点加以强调、阐释和引申，让其他学习者“学得快、少踩坑”!Easy RL，让你像采蘑菇一样轻松入门强化学习！

- 《深度学习》，作者：[美]伊恩·古德费洛，[加] 约书亚·本吉奥，[加]亚伦·库维尔

  > 2018年图灵奖得获奖者Yoshua Bengio创作了一本深度学习领域奠基性图书——《深度学习》，昵称“花书”。
  > “花书”长期位居美亚AI和机器学习类图书榜，涵盖了深度学习的基础与应用、理论与实践等各个方面的主要技术。
  > 书籍的编排方式非常适合自学，划分为“应用数学与机器学习基础”“深度网络: 现代实践”“深度学习研究” 三大板块，提供了完整的学习路线。

- 《动手学深度学习》，作者：阿斯顿·张(Aston zhang)，李沐(Mu Li)，[美] 扎卡里·C.立顿(Zachary C. Lipton)，[德] 亚历山大·J.斯莫拉(Alexander J. smola)

  > 《动手深度学习》远不只是一本书，全面概述深度学习背后的数学原理；更是一个编程工作台与记事本，提供了详细算法代码，能让读者一边动手学习，一边进行交流，同时获得反馈。
  > 加州大学伯克利分校、北京大学、清华大学等全球140余所高校将这本书用于教学，实现原理与实战完美结合的全新教学模式。
  > 如果你想钻研深度学习，请研读这本书！

- 《零基础学习机器学习》，作者：黄佳

  > 很难想象，作者竟然能把入门难度高的机器学习讲解得如此有趣，他在输出技术知识点的同时插播了轻松笑点，不仅有梗还有料。这本《零基础学机器学习》以AI菜鸟“小冰”拜师程序员“咖哥”为背景，精心设计了一条贴合零基础读者的入门路线。故事+对话+插图，让读者轻松到达机器学习的殿堂。

- 《PyTorch深度学习实战》，作者：[美]伊莱·史蒂文斯(Eli Stevens)，[意]卢卡·安蒂加(Luca Antiga)，[德]托马斯·菲曼(Thomas Viehmann)

  > 虽然很多深度学习工具都使用Python，但PyTorch 库是真正具备Python 风格的。对于任何了解NumPy 和scikit-learn 等工具的人来说，上手PyTorch 轻而易举。

#### 2）数学算法

- 《机器学习的数学》，作者：雷明

  > 想要透彻地理解机器学习算法，就需要从数学层面搞懂这些核心算法原理的逻辑，培养推导和证明算法的能力。机器学习资深专家、SIGAI创始人雷明全新创作的这门“数学公开课”《机器学习的数学》，就能帮助你吃透机器学习。这本书从机器学习应用的角度讲授数学，精准覆盖人工智能领域中机器学习、深度学习、强化学习相关的数学知识，让数学在机器学习中的应用无缝衔接。

- 《机器学习公式详解》，作者：谢文睿，秦州

  > 以前学习机器学习的时候，你可能只知道有“西瓜书”，但如今，我们还拥有了“南瓜书”！这是一本小白也能畅读“西瓜书”《机器学习》的好“伴侣”，能帮你一站式解决机器学习中的数学难题。“南瓜书”《机器学习公式详解》是Datawhale的开源协作学习笔记，在发布之初即登GitHub Trending第2名，受到了俞勇、王斌、李沐、程明明、陈光(博主@爱可-爱生活)、徐亦达6位人工智能领域大咖亲笔推荐！

- 《人工智能算法 卷1 基础算法》，作者：[美]杰弗瑞·希顿(Jeffery Heaton)

  > 算法是人工智能技术的核心。如果你想要了解和应用人工智能相关算法，那么千万别错过由专注于数据科学和人工智能的计算机科学家Jeffery Heaton博士创作的人工智能算法系列图书。《人工智能算法 卷1 基础算法》介绍了人工智能的基础算法，涉及维度法、距离度量算法、K 均值聚类算法、误差计算、 爬山算法、模拟退火算法、Nelder-Mead 算法和线性回归算法等。

- 《人工智能算法 卷2 受大自然启发的算法》，作者：[美]杰弗瑞·希顿(Jeffery Heaton)

  > 大自然为人类的发明创造提供了源源不断的灵感。这本书介绍了基于基因、鸟类、蚂蚁、细胞和树的算法，这些算法可用于查找最佳路径、识别模式、查找数据背后的公式，甚至模拟简单的生命等虽然算法的灵感来源是大自然，但读者不必具备生物学知识也能读懂本书。

- 《人工智能算法 卷3 深度学习和神经网络》，作者：[美]杰弗瑞·希顿(Jeffery Heaton)

  - 原作者最初打算编写5部曲的，貌似没完成

  > 自人工智能领域兴起，深度学习和神经网络就一直是人工智能的支柱。现在，令人兴奋的新技术（例如深度学习和卷积）正在将神经网络带入一个全新的方向。在这本书中，作者将演示各种现实世界任务中的神经网络，例如图像识别和数据科学。我们研究了当前的神经网络技术，包括ReLU 激活、随机梯度下降、交叉熵、正则化、Dropout 及可视化等。

- 《Python神经网络编程》，作者：[英塔里克·拉希德(Tariq Rashid)

  > 如果只读一本神经网络入门图书，请选择这本基于Python3.5对神经网络精彩解读的美亚五星畅销书《Python神经网络编程》。在这本书中，作者用轻松的笔触，一步一步揭示了神经网络的数学思想，并介绍如何使用Python编程语言开发神经网络。通过这本书，你将学习使用Python开发自己的神经网络，训练它识别手写数字，甚至可以与专业的神经网络相媲美！

- 《PyTorch生成对抗网络编程》，作者：[英]塔里克·拉希德

  > 机器学习领域近20年来最酷的想法生成对抗网络（GAN），是神经网络领域的新星，吸引了无数人学习。这本美亚全五星好评的《PyTorch生成对抗网络编程》适合想初步了解GAN以及其工作原理的读者，也适合想要学习如何构建GAN的机器学习从业人员。本书以直白、简短的方式向读者介绍了生成对抗网络，并且教读者如何使用PyTorch按部就班地编写生成对抗网络。

- 《GAN实战》，作者：[英]雅各布·朗格尔，[美]弗拉基米尔·博克

  > 《GAN实战》由英国创企孵化器Founders Factory计算机视觉领域的联合创始人Jakub Langr与美国纽约一家初创公司的高级产品经理Vladimir Bok合力写就。这本书主要介绍构建和训练生成对抗网络（GAN）的方法。书中给出了大量的示例，教读者学习针对不同的场景训练不同的GAN，进而完成生成高分辨率图像、实现图像到图像的转换、生成对抗样本以及目标数据等任务，让所构建的系统变得智能、有效和快速！

#### 3）应用实战

- 《百面机器学习》，作者：葫芦娃

  > “不积跬步，无以至千里”。这本书从特征工程、模型评估、降维等经典机器学习领域出发，构建一个算法工程师必备的知识体系；还收集了在近年算法工程师的笔试、面试中出现过的100多道机器学习的题目；讲述了很多算法背后的小故事，增加了读者对问题的理解。希望你能通过这本书为你铺设的道路，快速通往目标！

- 《百面深度学习》，作者：诸葛越，江云胜，葫芦娃

  > 这是一本人工智能时代程序员不可不读深度学习面试宝典！作为《百面机器学习：算法工程师带你去面试》的姐妹篇，这本书秉承了作者写作的一贯风格：技术上有深度，深入浅出讲得透彻；实践上有温度，言传身教讲得到位。这本书通过知识点问答为读者层层揭开深度学习的神秘面纱，其一大亮点是囊括了一系列前沿领域的新进展。如果你想抢在别人前面掌握它们，千万不要错过这本书。

- 《自然语言处理实战》，作者：[美]霍布森·莱恩，[美]科尔·霍华德，[美]汉纳斯·马克斯·哈克

  > 有这样一本书，它不仅是Python开发人员入门自然语言处理的必备书籍，还是现代自然语言处理领域从业者的实用参考指南。这本书便是由小米AI实验室NLP团队献译的《自然语言处理实战 ：利用Python理解、分析和生成文本》。该书扩展了传统的自然语言处理方法，包括神经网络、现代深度学习算法和生成技术，用于解决真实世界的问题，如提取日期和名称、合成文本和回答无固定格式的问题。如今，NLP已成为深度学习的核心应用领域，这本关于深度学习的书，特别值得你去深度学习！

- 《OpenCV 4详解：基于Python》，作者：冯振，陈亚萌

  > 零基础，想学习OpenCV 4 , 但畏难情绪严重？别怕，跟着《OpenCV 4详解：基于Python》走，让哈工大博士手把手带你入门!作者冯振擅于由浅入深，层层递进，以 Python 语言为基础，添加了部分新内容，不仅可帮助使用Python 语言的开发人员快速入门 OpenCV 4，还能帮助开发人员轻松提升应用程序开发水平和图像处理水平。

- 《Python深度学习与项目实战》，作者：周北

  > 多领域结合的深度学习经典教程！世界名校教师教授、国内外大咖鼎力推荐！AI与多领域融合的实战指南！《Python深度学习与项目实战》基于Python以及两个深度学习框架Keras与TensorFlow，讲述深度学习在实际项目中的应用。并且还结合计算机视觉、自然语言处理、金融领域等方面的项目，系统讲述深度学习技术，可操作性强。不得不说，这是一本非T人士也可以轻松读懂的专业书！

- 《机器学习算法评估实战》，作者：宋亚统

  > 在机器学习算法的实际应用中，我们不仅要知道算法的原理，也要了解如何评估算法上线服务的可靠性。这本美团高级算法工程师全新力作《机器学习算法评估实战》就能帮助你彻底解决：算法如何设计?算法如何评估?等问题。并且，这本书深入细节，对多种算法进行简洁明了的图解以及条理清晰的实例推导，让初入机器学习算法领域的读者更好容易理解各种经典模型的原理，是一本难得的佳作。



## 手册（reference manual）

### 数据库

- 关系型数据库
  - PostgreSQL：
    - [PostgreSQL中文手册](reference-manual/databases/postgresql/pgdoc-cn/)

  - Postgres-X2：
    - [Postgres-X2官方英文手册](reference-manual/databases/postgresql/postgres-x2)
    - [《Postgres-XC Concept, Implementation and Achievements》.pdf 英文原版手册，讲解架构及源码实现](reference-manual/databases/postgresql/pgx2-implementation/XCimplementation/pgxc.pdf)
    - [《Postgres-XC Concept, Implementation and Achievements》所用的架构、原理图合集](reference-manual/databases/postgresql/pgx2-implementation/XCimplementation/arch_doc)
    - [《Postgres-XC Concept, Implementation and Achievements》其他资料](reference-manual/databases/postgresql/pgx2-implementation/XCimplementation/)
- 搜索型数据库
  - [ElasticSearch官方手册中文翻译（第一个）](reference-manual/databases/elasticsearch/elasticsearch-reference-translation/)
  - [ElasticSearch官方手册中文翻译（第二个）](reference-manual/databases/elasticsearch/elasticsearch-doc-cn)
- 存储引擎：
  - [goleveldb非官方中文手册](reference-manual/databases/leveldb/goleveldb-handbook)
    - [在线地址](https://leveldb-handbook.readthedocs.io/zh/latest/index.html)


### 编程语言

- Golang：
  - [Golang标准库和部分第三方包的包文档中文翻译](reference-manual/programming-language/golang/golang-pkgdoc)

## 图片及其他素材

### 数据库

- MySQL
  - [jeremycole/innodb_diagrams](charts/databases/mysql/innodb_diagrams)
