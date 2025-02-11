**微服务架构设计的首要任务就是合理划分微服务，即围绕业务功能创建微服务项目。在划分微服务时，有关微服务粗细粒度的考量，建议在平台创建的初始阶段使用粗粒度的方法，按业务功能进行划分。随着业务的发展及其运营的情况，再依据发展规模考虑是否继续细分。下面，我们将使用水平划分法和垂直划分法两种方法相结合的方式创建微服务**

**一方面在水平方向上**：

**根据业务功能划分微服务，并把这次划分所创建的微服务称为REST API微服务。REST API微服务负责业务功能的行为设计，主要完成数据管理方面的工作，并通过使用REST协议，对外提供接口服务。**

**另一方面在垂直方向上**：

**再以REST API微服务为基础，实现前后端分离设计，创建Web UI微服务。Web UI微服务不直接访问数据，它只专注于人机交互界面的设计，它的数据存取将通过调用REST API微服务来完成。这样，经过两次微服务划分，我们就可以创建出REST API和Web UI两种类型的微服务。也就是说，我们只要使用两种类型的微服务，就可以构建一个复杂的业务系统。**

**使用REST API和Web UI微服务，结合高性能和高并发的设计，再通过微服务的多副本发布，就可以构建一个能适应任何规模访问的、多维的、稳定牢固的网格结构，并且这个网格结构还具有自由伸缩的特性，可以根据业务的发展规模进行扩充或者缩编，这样就可以快速地搭建一个可持续扩展的系统平台**


# Software-Architecture-Design
软件架构设计的流程，从项目立项--》项目需求--》项目设计--》项目开发

# [软件系统架构面试](https://github.com/stevenli91748/Software-Architecture-Design/tree/master/Interview)

# [最好的软件架构设计书籍](https://segmentfault.com/a/1190000011881339?utm_source=sf-related)



---
<a href="https://ibb.co/X20SnLf"><img src="https://i.ibb.co/4mvPbtw/2.png" alt="2" border="0"></a>


<a href="https://ibb.co/rxLQHkx"><img src="https://i.ibb.co/fkKXHMk/2.png" alt="2" border="0"></a>

# 架构分层

<a href="https://ibb.co/zZTMn0x"><img src="https://i.ibb.co/Wf4hxY5/image.png" alt="image" border="0"></a>

<a href="https://ibb.co/vB8JPmv"><img src="https://i.ibb.co/fS7CptG/1-2.png" alt="1-2" border="0"></a>

<a href="https://ibb.co/NSXBMgD"><img src="https://i.ibb.co/74HmqxM/2.png" alt="2" border="0"></a>


[火龙果软件架构设计---softwear archietcure good](http://wenku.uml.com.cn/index.asp)|[架构设计的本质](https://www.kubernetes.org.cn/8510.html)|[为什么这么设计---程序设计决策](https://draveness.me/tags/%E7%B3%BB%E7%BB%9F%E8%AE%BE%E8%AE%A1)|
 ---|---|---|

[解道](https://www.jdon.com/designpatterns/)|[凤凰架构---构建可靠的大型分布式系统 ”](https://github.com/stevenli91748/System-Design/blob/master/%E5%87%A4%E5%87%B0%E6%9E%B6%E6%9E%84---%E6%9E%84%E5%BB%BA%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%A4%A7%E5%9E%8B%E5%88%86%E5%B8%83%E5%BC%8F%E7%B3%BB%E7%BB%9F%20%E5%91%A8%E5%BF%97%E6%98%8E.md)|
---|---|

[UMLchina---潘加宇](http://www.umlchina.com/index.html)|[软件需求设计方法学全程实例剖析幻灯片---潘加宇](http://www.umlchina.com/training/slide.html)|[《软件方法》书中自测题-题目全文+分卷自测（1-8章）16套111题---潘加宇](https://mp.weixin.qq.com/s/Xj9YoZzuR-4loMXwBubEag)|
---|---|---|

[[2020.01加一套题]UMLChina建模竞赛题大全-题目全文+分卷自测（11套110题）---潘加宇](https://mp.weixin.qq.com/s/GDfIMgdZ8VWWmrNF-axmsw)|[UMLChina建模竞赛题答案及解析------潘加宇](http://www.umlchina.com/training/quizanswer.html)|
---|---|


# 在线书籍

## 设计模式
* [设计模式就该这样学：基于经典框架源码和真实业务场景---2020](https://weread.qq.com/web/reader/8aa3282071f94a868aa8f52)
* [重学JAVA设计模式](https://weread.qq.com/web/reader/bcf32900724708cbbcf08c1)

## 软件架构设计
* [软件需求最佳实践](https://weread.qq.com/web/reader/b7a32c705a0369b7a68c833)
* [架构真意：企业级应用架构设计方法论与实践](https://weread.qq.com/web/reader/1c8329d072599d741c81d96)
* [高性能JAVA架构： 核心原理与案例实战](https://weread.qq.com/web/reader/6ba32c40726e7c066bad7ed)
* [软件架构设计：大型网站技术架构与业务架构融合之道](https://weread.qq.com/web/reader/ac4325c071848780ac4f8d8kc81322c012c81e728d9d180)
* [一线架构师实践指南---温立](https://weread.qq.com/web/reader/db3328605a078edb31ea6ac)
* [软件架构设计（第2版---温立）](https://weread.qq.com/web/reader/5f232ac05a60095f2080a26)
* [实用软件架构： 从系统环境到软件部署---IBM 工程师所写](https://weread.qq.com/web/reader/b9232490718f6371b9291ff)
* [架构整洁之道---2018](https://weread.qq.com/web/reader/480322f072021a3248038c8)
* [大型网站技术架构--李智慧](https://weread.qq.com/web/reader/cc1326e05bcc52cc1669fc0)
* [系统架构设计---2017](https://weread.qq.com/web/reader/86832620717d308a868f221)
* [企业互联网架构原理---2021](https://weread.qq.com/web/reader/95c324307264001095c6f30kc81322c012c81e728d9d180)
* [软件方法： 业务建模和需求---重点讲业务建模 系统建模 业务用例 业务时序图 需求用例等知识---](https://weread.qq.com/web/reader/4be329b07198d7344beb216)
* [架构解密： 从分布式到微服务（第2版）---2020 不论你是有十几年研发经验及架构经验的IT老手，还是刚入门系统架构的IT新手，本书都能对你理解分布式架构和微服务架构大有助益，对分布式、微服务、云原生、K8s、Service Mesh等发展脉络和原理进行深度解密 ](https://weread.qq.com/web/reader/26a3299071eeef0026a40f1kc81322c012c81e728d9d180)
* [超大流量分布式系统架构解决方案： 人人都是架构师2.0---2020](https://weread.qq.com/web/reader/068328c071e072b10685247)
* [架构真意：企业级应用架构设计方法论与实践---2021](https://weread.qq.com/web/reader/1c8329d072599d741c81d96kc81322c012c81e728d9d180)
* [软件架构设计： 大型网站技术架构与业务架构融合之道---2018](https://weread.qq.com/web/reader/ac4325c071848780ac4f8d8kc81322c012c81e728d9d180)
* [可伸缩架构（第2版）： 云环境下的高可用与风险管理---2021](https://weread.qq.com/web/reader/cca3268071fd5a81ccac95b)
* [分布式系统设计实践](https://weread.qq.com/web/reader/df832b00719db449df881a6)


### 邻域驱动设计(DDD)
* [复杂软件设计之道： 邻域驱动设计全面解析与实战---2020](https://weread.qq.com/web/reader/95932e2072052ac7959169d)
* [实现邻域驱动设计](https://weread.qq.com/web/reader/f5032ce071fd5a64f50b0f6)
* [深入实践DDD: 以DSL驱动复杂软件开发---2021](https://weread.qq.com/web/reader/3f232740723b60233f23504)
* [邻域驱动设计---2020](https://weread.qq.com/web/reader/44f32bb071e1265344f0481)


### 微服务架构设计
* [Spring微服务架构设计---2020](https://weread.qq.com/web/reader/9de32c5071db56e39decfc8)
* [Spring 微服务架构设计---2020 如何用SpringBoot 和 Spring Cloud 开发微服务系统，如何演进微服务，微服务的日志管理和监控，如何用Docker, Mesos 和 Marathon管理互联网级微服务架构](https://weread.qq.com/web/reader/9de32c5071db56e39decfc8kc81322c012c81e728d9d180)
* [微服务设计： 企业架构转型之道---2019 如何规划企业架构 ，包括业务架构 因用架构 数据架构 和技术架构， 企业架构的服务化过程 以及其完成后的企业服务架构的微服务过程 企业微服务架构的治理和管理](https://weread.qq.com/web/reader/61d32d70719c260961d4b33kc81322c012c81e728d9d180)
* [Kubernetes微服务实战](https://weread.qq.com/web/reader/f1c32df071eeef5bf1cc214)
* [SOA架构： 服务和微服务分析及设计---2017](https://weread.qq.com/web/reader/9ec32e50720bfc6d9eceb32)
* [微服务分布式架构开发实战](https://weread.qq.com/web/reader/d19329f0715a41a7d19438bkc81322c012c81e728d9d180)



## API设计
* [现代API: 通往架构师之门---2018  作者20年为北美18个行业50多家大型企业进行系统集成及API设计的实践经验](https://weread.qq.com/web/reader/b3f321407170d865b3f0e45)

### Serverless
* [Serverless架构---2020](https://weread.qq.com/web/reader/c8a32e205e2f83c8a87fa85)
* [Serverless工程实践---2021](https://weread.qq.com/web/reader/89c322e0725d0bbd89cac6a)
* [Serverless架构： 从原理，设计到项目实战 ](https://weread.qq.com/web/reader/4383249071a74c67438c595)
* [Serverless架构：无服务应用与AWS Lambda](https://weread.qq.com/web/reader/acb32da071dbdd99acb7f9b)

### istio
* [Istio服务网络技术解析与实践](https://weread.qq.com/web/reader/20c3266071c94f5b20c1306kc81322c012c81e728d9d180)
* [Service Mesh实战：基于Linkerd和kubernetes的微服务实践](https://weread.qq.com/web/reader/743329b0716983fb7437b63)
* [Service Mesh 微服务架构设计](https://weread.qq.com/web/reader/4de32f7071ef4cea4dee0b6)
* [Istio服务网洛计术解析与实践](https://weread.qq.com/web/reader/20c3266071c94f5b20c1306)
* [istio实战指南](https://weread.qq.com/web/reader/2c2325007193f2442c2e695)
* [Service Mesh实战：用Istio软负载实现服务网格](https://weread.qq.com/web/reader/f57324607188b37df57c39e)
* [深入浅出Istio: Service Mesh快速入门与实践](https://weread.qq.com/web/reader/e2c32bb071848778e2cf1c7)
* [istio入门与实战](https://weread.qq.com/web/reader/af532c40718247c3af53d89)
* [云原生服务网格Istio: 原理 实践 架构与源码解析](https://weread.qq.com/web/reader/ed4321c0811e3db9cg014f7c)

### 架构设计实践
* [智能风控平台： 架构 设计与实践](https://weread.qq.com/web/reader/265324307260a55926555abkc81322c012c81e728d9d180)
* [产品设计思维：电商产品设计全功略](https://weread.qq.com/web/reader/3d532fe05de4da3d52176ea)
* [代码精进之路，从码农到工匠 2019](https://weread.qq.com/web/reader/81132f5071cc7f7a81151c9)

---

# 设计工具
* [ProcessOn---专业强大的作图工具，支持多人实时在线协作，可用于原型图、UML、BPMN、网络拓扑图等多种图形绘制](https://www.processon.com/)

# 领域驱动设计架构(DDD)

* [领域驱动设计架构DDD落地案例](https://github.com/stevenli91748/Design-Patterns/blob/master/%E9%A2%86%E5%9F%9F%E9%A9%B1%E5%8A%A8%E8%AE%BE%E8%AE%A1%E6%9E%B6%E6%9E%84DDD/README.md)

# 多租户技术或称多重租赁技术，简称SaaS
* [多租户技术或称多重租赁技术，简称SaaS架构](https://www.kancloud.cn/zlt2000/microservices-platform/1224729)

# 架构设计案例

 [大型电商平台微服务设计入门案例](https://weread.qq.com/web/reader/ca932ea071d7c798ca9a714k33e3289021c33e75ff09694) |
 ---|

[张传波 软件设计是怎样炼成的---实际操作的步骤](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/%E8%BD%AF%E4%BB%B6%E8%AE%BE%E8%AE%A1%E6%98%AF%E6%80%8E%E6%A0%B7%E7%82%BC%E6%88%90%E7%9A%84/README.md)|[凤凰架构---构建可靠的大型分布式系统 周志明](https://github.com/stevenli91748/System-Design/blob/master/%E5%87%A4%E5%87%B0%E6%9E%B6%E6%9E%84---%E6%9E%84%E5%BB%BA%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%A4%A7%E5%9E%8B%E5%88%86%E5%B8%83%E5%BC%8F%E7%B3%BB%E7%BB%9F%20%E5%91%A8%E5%BF%97%E6%98%8E.md)|
---|---|

[高并发架构的整体思路](https://www.jianshu.com/p/f0ac1e7eee72)|
---|


[企业总体架构要如何做？小白也能快速领悟的设计思想](https://www.jianshu.com/p/12770c880775)|[架构师是怎样炼成的](https://www.jianshu.com/p/b94ac2e051b6)|
---|---|

[MVC设计架构落地案例---看完这篇，别人的开源项目结构应该能看懂了](https://www.bilibili.com/read/cv5236887?from=articleDetail)|[MVC架构杂谈](https://www.kancloud.cn/kancloud/mac)|
---|---|
 
[阿里巴巴公司中优秀的代码都是如何分层的？](https://developer.51cto.com/art/202103/652080.htm)|[java web开发中的各种层](https://zhuanlan.zhihu.com/p/95059739)|[一文教会你如何写复杂业务代码](https://www.kubernetes.org.cn/8577.html)|
---|---|---|
 
[面对零售通如此复杂的业务场景，如何在架构和代码层面进行应对,结合实际的业务场景，我沉淀了一套“如何写复杂业务代码”的方法论,一文教会你如何写复杂业务代码](https://www.kubernetes.org.cn/8577.html)|
---|
 
[应用架构之道：分离业务逻辑和技术细节](https://www.kubernetes.org.cn/8549.html)|[用架构方法实现业务架构与应用架构对准](https://www.jianshu.com/p/bf6aee11e51b)|
---|---|

[业务-应用-数据-技术架构的正向设计方法](https://www.jianshu.com/p/464737435fab)|[解剖实体框架](https://www.kancloud.cn/digest/frame)|
---|---|

[我是怎么画架构图的](https://mp.weixin.qq.com/s/0jOIU605OD1UYZrnUcPzng)|
---|

[架构设计实践五部曲（一）：架构与架构图](https://www.infoq.cn/article/b1fCLl8Mk9L9qe45Zxp6)|[架构设计实践五部曲（二）：业务架构与产品架构设计实践](https://www.infoq.cn/article/5A8LiWThDdHpkjeKgWLk?utm_source=related_read_bottom&utm_medium=article)|[架构设计实践五部曲（三）：从领域模型提取数据架构](https://www.infoq.cn/article/gecWdtRC85LD3kfXlWNU)|
---|---|---|

[架构设计实践五部曲（四）：单体式与分布式的应用架构](https://www.infoq.cn/article/ZzI05OBgks2kspUWa5y7)|[架构设计实践五部曲（五）：技术架构的战略和战术原则](https://www.infoq.cn/article/RQDwWxDcwbxtwU8LBFSG)|
---|---|

[国内主流在用的10大后台UI框架，私活必备](https://www.toutiao.com/a6822120255800738318/?log_from=1d7c99a84127f_1630175917915)|
---|

[都说软件架构要分层、分模块，具体应该怎么做之一](https://developer.51cto.com/art/202103/648661.htm)|[都说软件架构要分层、分模块，具体应该怎么做之二](https://developer.51cto.com/art/202103/649542.htm)|[业务架构实践：一步一步画出业务架构图](https://www.coollf.com/archives/%E4%B8%9A%E5%8A%A1%E6%9E%B6%E6%9E%84%E5%AE%9E%E8%B7%B5%E4%B8%80%E6%AD%A5%E4%B8%80%E6%AD%A5%E7%94%BB%E5%87%BA%E4%B8%9A%E5%8A%A1%E6%9E%B6%E6%9E%84%E5%9B%BE)|
---|---|---|

[需求分析挑战之旅——疯狂的订餐系统](https://www.cnblogs.com/umlonline/archive/2011/08/01/2123656.html)|
---|

# 架构设计的六大原则
[架构收藏必备：架构设计的六大原则](https://www.toutiao.com/a6822896880591045127/?log_from=0a8549e2c3c68_1630179494880)|[架构设计：微服务架构如何划分？这6个标准原则让你一目了然](https://www.toutiao.com/a6872625876522140171/?log_from=6172a5f6ba78f_1630179740431)|
---|---|



# 软件架构模式分类
[软件架构入门](http://www.ruanyifeng.com/blog/2016/09/software-architecture.html)|[程序员必知的几种软件架构模式](https://www.infoq.cn/article/6rx047oohjlrdipd1bc2)|
---|---|

[软件开发模型的演化](https://insights.thoughtworks.cn/evolution-of-development-model/)|[十种软件架构设计模式(Architectural Pattern](https://www.cnblogs.com/IcanFixIt/p/7518146.html)|[四种软件架构演进史，程序员会一种就很牛了](https://juejin.im/post/6844903831659085832)|
---|---|---|


[项目经理小姐姐非要给我讲一讲，项目开发规范和流程！---项目开发的工具](https://developer.51cto.com/art/202009/626353.htm)|
---|

[耦合到底意味着什么呢](https://zhuanlan.zhihu.com/p/105463736?utm_source=wechat_session&utm_medium=social&utm_oi=991812777480134656&utm_content=first)|[Software Design Tutorial #1 ](https://www.youtube.com/watch?v=FLtqAi7WNBY&t=170s)|[Software Design Tutorial #2 ](https://www.youtube.com/watch?v=6thjSbJcoUc)|
---|---|---|

[软件架构设计模式(Architectural Pattern)不同于设计模式(Design Pattern)](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/%E8%BD%AF%E4%BB%B6%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F/README.md)|[Java架构：一文读懂微服务架构的重构策略](https://developer.51cto.com/art/201905/597080.htm)|
---|---|

[程序员转型架构师，推荐你读这几本书](https://segmentfault.com/a/1190000020720430)|
---|


# 软件测试

* [2020 软件测试教程](https://www.kancloud.cn/apachecn/guru99-zh/1953496)

# 架构常用的设计图

* [架构师常用的设计图工具和设计图分类](https://cloud.tencent.com/developer/article/1073501)
* [架构制图：工具与方法论](https://www.kubernetes.org.cn/8479.html)
* [如何画出一张合格的技术架构图？](https://my.oschina.net/yunqi/blog/3035875)
* [整不明白架构图都画啥](https://bugstack.cn/framework/2021/02/28/%E5%B7%A5%E4%BD%9C%E4%B8%A4%E4%B8%89%E5%B9%B4-%E6%95%B4%E4%B8%8D%E6%98%8E%E7%99%BD%E6%9E%B6%E6%9E%84%E5%9B%BE%E9%83%BD%E7%94%BB%E5%95%A5.html)|

# [UML工具](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/UML/README.md)

[UML学习入门就这一篇文章](https://zhuanlan.zhihu.com/p/63147410)|[活用类图——分析业务概念模型（图文）](http://www.douya2.com/goods/show/61?targetId=65&preview=0)|
---|---|

---
# 目录

* [架构设计的目的](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/%E8%BD%AF%E4%BB%B6%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1%E7%B3%BB%E5%88%97%E6%96%87%E7%AB%A0/%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1%E7%9A%84%E7%9B%AE%E7%9A%84.md)
  * [软件架构设计思想路线](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2k8e232ec02198e296a067180) 
    * 系统分析与设计的三个发展阶段 
      * [第一阶段：面向数据驱动分析与设计](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2)
      * 第二阶段：面向对象和服务分析与设计，不管是在面向对象分析与设计中还是在面向服务分析与设计中，都带来了一个致命的缺点：分析阶段和设计阶段都是分开的、割裂的，不能很好地衔接
        * [面向对象分析与设计思想---面向对象分析与设计可以说是一种自底向顶的设计方式，面向对象分析与设计主要关注微观层次的抽象，比如类和对象实例等；对每个问题域通常都需要创建单独的用例分析模型，项目或产品的大方向在许多情况下变得很模糊，很难全局把控系统的总目标，所以这样的系统分析与设计方式存在很大的风险](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2k8e232ec02198e296a067180)
        * [面向服务分析与设计思想---在做面向服务分析与设计时会采用自顶向底的设计方法，首先要分离出业务流程和服务，然后细化对象，在面对复杂的市场需求时，面向对象分析与设计就显得捉襟见肘了，此时就需要从更高的层次分解市场需求，面向服务分析与设计应运而生](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2k8e232ec02198e296a067180)
          * Web Service模式
          * ESB模式
          * 微服务架构 
      * [第三阶段：领域驱动设计，使用统一的模型来满足分析与设计的需求](https://github.com/stevenli91748/Design-Patterns/blob/master/%E9%A2%86%E5%9F%9F%E9%A9%B1%E5%8A%A8%E8%AE%BE%E8%AE%A1%E6%9E%B6%E6%9E%84DDD/README.md)
        * [领域驱动设计（DDD）---打破了分析和设计割裂的状态，并给出了领域模型的概念，抛弃了将分析与设计分开的做法，使用统一的模型来满足分析与设计的需求，使系统开发能够更加灵活、快速地响应需求的变化,领域建模的过程把分析阶段和设计阶段变成了单个循环阶段，把分析与设计紧密联系起来，使领域建模专家不再只关注需求概念的收集，也关注程序代码的设计与实现](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2k8e232ec02198e296a067180)
* [架构设计分类](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2k17e328b022b17e62166fad4)
  * 业务架构---业务架构是决定一个软件项目能否顺利开展的总纲，软件架构是业务架构在技术层面的映射，合理的开发分工也应该基于业务架构去做。如果没有业务架构，进行软件开发就会很盲目。业务架构是需求和开发的汇聚点，需求分析是否做到位，功能开发是否达到预期目标，都以此为依托
  * 应用架构
  * 数据架构
    * 静态部分的内容---静态部分的内容的重点是数据元模型、数据模型，包括主数据、共享动态数据和所有业务相关的业务对象数据的分析和建模
    * 动态部分的内容---动态部分的内容的重点则是对数据全生命周期的管控和治理 
  * 技术架构
* 软件架构设计8步骤---从需求到架构验证
  * 架构设计的流程
    * [经典的架构设计过程模型 ](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2kf7132c6022cf7177163c01c)
    * [架构设计方法之四层驱动模型 ](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2kf7132c6022cf7177163c01c)
  * [1. 需求工程](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/%E8%BD%AF%E4%BB%B6%E9%9C%80%E6%B1%82%E8%A7%84%E5%88%92/%E9%9C%80%E6%B1%82%E5%B7%A5%E7%A8%8B.md)
  * [2. 邻域建模](https://github.com/stevenli91748/Design-Patterns/blob/master/%E9%A2%86%E5%9F%9F%E9%A9%B1%E5%8A%A8%E8%AE%BE%E8%AE%A1%E6%9E%B6%E6%9E%84DDD/README.md)
  * [3. 确定关键需求](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/确定关键需求/README.md)
  * [4. 概念架构设计==分层架构设计和API设计](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/概念架构设计/README.md)
  * [5. 细化架构设计==模块设计](https://github.com/stevenli91748/Software-Architecture-Design/tree/master/细化架构设计)
  * 6 数据库架构设计
  * 7 用户体验架构设计
  * [8. 架构验证](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/架构验证/README.md)
* [软件架构风格的演进](https://github.com/stevenli91748/System-Design/blob/master/%E8%BD%AF%E4%BB%B6%E6%9E%B6%E6%9E%84%E9%A3%8E%E6%A0%BC%E7%9A%84%E6%BC%94%E8%BF%9B.md)
  * 大型机架构风格（Mainframe）
  * [原始分布式架构风格（Distributed）](https://icyfenix.cn/architecture/architect-history/primitive-distribution.html)
  * [Spring Boot 实现单体架构（Monolithic）](https://icyfenix.cn/architecture/architect-history/monolithic.html)---单体”只是表明系统中主要的过程调用都是进程内调用，不会发生进程间通信，仅此而已
  * [Spring Cloud 实现微服务架构](https://icyfenix.cn/exploration/projects/microservice_arch_springcloud.html)
  * [Kubernetes 为基础设施的微服务架构](https://icyfenix.cn/exploration/projects/microservice_arch_kubernetes.html)
  * 后微服务架构风格：云原生时代（Cloud Native）
    * [后微服务时代: Istio 为基础设施的服务网格架构（Service Mesh）](https://icyfenix.cn/exploration/projects/servicemesh_arch_istio.html)
  * [AWS Lambda 为基础的无服务架构（Serverless）](https://icyfenix.cn/exploration/projects/serverless_arch.html)
  * CQRS模式架构
    * [SpringBoot+CQRS微服务设计模式教程](https://www.jdon.com/55380) 
    * [DDD框架中的CQRS设计原理解析](https://weread.qq.com/web/reader/71d32370716443e271df020kb3e32dc0299b3e3e393ce03)
      *  
* [设计架构的套路](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/%E8%BD%AF%E4%BB%B6%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1%E7%B3%BB%E5%88%97%E6%96%87%E7%AB%A0/%E8%AE%BE%E8%AE%A1%E6%9E%B6%E6%9E%84%E7%9A%84%E5%A5%97%E8%B7%AF.md)
* [架构设计6个原则](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/%E8%BD%AF%E4%BB%B6%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1%E7%B3%BB%E5%88%97%E6%96%87%E7%AB%A0/%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A16%E4%B8%AA%E5%8E%9F%E5%88%99.md)
* [决定如何划分顶级子系统](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/%E8%BD%AF%E4%BB%B6%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1%E7%B3%BB%E5%88%97%E6%96%87%E7%AB%A0/%E5%86%B3%E5%AE%9A%E5%A6%82%E4%BD%95%E5%88%92%E5%88%86%E9%A1%B6%E7%BA%A7%E5%AD%90%E7%B3%BB%E7%BB%9F.md)
* [设计模式](https://github.com/stevenli91748/Design-Patterns)


**我做的项目中通常每个项目至少需要1份架构设计文档、1份数据库设计文档、0到多份模块设计文档和1份用户体验设计文档**

软件架构设计为什麽难？因为它是跨越现实世界（问题领域）到计算机领域（解决方案）之间的一座桥，需求分析是明确“问题领域”，将要解决的问题以
"功能 + 质量 + 约束"的形式定义下来，但需求不管做得再细，也没有打破“系统是黑盒子”这一点，软件架构设计就是完成从面向问题领域到面向解决方案的转换
（进入系统黑盒子）

---

# 软件架构视频
  
  * [大型高并发与高可用缓存架构实战 (上)](https://www.bilibili.com/video/av48758838/?spm_id_from=333.788.videocard.7)
  * [软件设计是怎样炼成的](https://edu.51cto.com/course/5568.html)
# 参考的资料
  * [架结构分层：三层结构，DDD，MVC，MVVM，MVP](http://www.360doc.com/content/20/1114/16/37113458_945826321.shtml)
  * [关于低代码编程的可持续性交付设计和分析](https://bugstack.cn/framework/2021/02/21/%E5%85%B3%E4%BA%8E%E4%BD%8E%E4%BB%A3%E7%A0%81%E7%BC%96%E7%A8%8B%E7%9A%84%E5%8F%AF%E6%8C%81%E7%BB%AD%E6%80%A7%E4%BA%A4%E4%BB%98%E8%AE%BE%E8%AE%A1%E5%92%8C%E5%88%86%E6%9E%90.html)
  * [软件架构编年史：MVC及其变种](https://developer.51cto.com/art/202104/656839.htm)
  * [MPP大规模并行处理架构详解](https://developer.51cto.com/art/202103/652932.htm)
  * [程序员转型架构师，推荐你读这几本书](https://segmentfault.com/a/1190000020720430)
  * [需求分析说明书和需求规格说明书](https://www.jianshu.com/p/26645058db08)
  * [烟囱式到SOA再到微服务](https://www.jianshu.com/p/a095c59baf31)
  * [没项目经历的安酱，连低耦合高内聚都不懂](https://developer.51cto.com/art/202009/625555.htm)
  * [学会了这些技术，你离BAT大厂不远了---技术架构路径图](https://blog.csdn.net/z694644032/article/details/100084287)
  * [学完这100多技术，能当架构师么？](http://www.imooc.com/article/details/id/291107)
  * 系统架构设计-从程序员向架构师转型之路.pdf
  * 软件是这样“炼”成的  从软件需求分析到软件架构设计.pdf
  * software-architecture-patterns.pdf
  * 软件需求十步走  新一代软件需求工程实践指南.pdf
  * 软件架构设计(第二版)：程序员向架构师转型必备.pdf  温昱  
  * [UML](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/UML/README)
  * [真实软件项目开发流程--从需求到开发的每一步骤](http://www.youmeek.com/java-sofaware-engineer/)
  * [软件架构入门](http://www.ruanyifeng.com/blog/2016/09/software-architecture.html)
  * [10个通用软件架构模式](https://www.jdon.com/artichect/architectural-patterns.html)
  * [针对架构设计的几个痛点，我总结出的架构原则和模式](https://www.infoq.cn/article/several-pain-points-architecture-design)
  * [从 MVC 到前后端分离 ](https://my.oschina.net/huangyong/blog/521891)
 
  * [事件追踪系统设计系列1-事件追踪系统设计需求分析&设计埋点方案](https://www.jianshu.com/p/250001a9e57b)
  * [事件追踪系统设计系列2-输出事件追踪系统设计需求文档](https://www.jianshu.com/p/063d8107d18a)
  * [事件追踪系统设计系列3-事件追踪系统设计的框架设计及其准确性](https://www.jianshu.com/p/553ab7bb42c4)
  * [事件追踪系统设计系列4-从事件追踪系统的系统设计搭建到数据可视化落地](https://www.jianshu.com/p/2b43c823d059)
