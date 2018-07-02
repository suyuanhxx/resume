## 个人信息
- 黄小旭/男/1993.05.01  
- 中国地质大学（武汉）- 软件工程 &emsp; 本科 &emsp; 2011.09 - 2015.07
- 工作年限：3年 &emsp; 现居住地：上海&emsp;  
- 技术博客：[https://suyuanhxx.github.io](https://suyuanhxx.github.io)
- Github: [https://github.com/suyuanhxx](https://github.com/suyuanhxx)
- 期望职位：Java开发工程师
- 期望薪资：22K
- 爱好：小说《三体》，《择天记》，美剧，动漫
---

## 联系方式
- Email：1498319046@qq.com
- Tel: 13007133406
- QQ/微信号：suyuanhxx
- LinkIn: [黄小旭](https://linkedin.com/in/小旭-黄-7b0b19b4)

---------
## 技能清单
- Java，熟练度：![CWDxPK.png](https://s1.ax1x.com/2018/05/24/CWDxPK.png)![CWDxPK.png](https://s1.ax1x.com/2018/05/24/CWDxPK.png)![CWDxPK.png](https://s1.ax1x.com/2018/05/24/CWDxPK.png)![CWDxPK.png](https://s1.ax1x.com/2018/05/24/CWDxPK.png)
- Golang，熟练度：![CWDxPK.png](https://s1.ax1x.com/2018/05/24/CWDxPK.png)![CWDxPK.png](https://s1.ax1x.com/2018/05/24/CWDxPK.png)![CWDxPK.png](https://s1.ax1x.com/2018/05/24/CWDxPK.png) 
- Spring FrameWork(SpringMVC，Spring Boot，Spring Cloud)
- 并发多线程，设计模式，事务，Nginx负载均衡，Zookeeper，RabbitMq
- 微服务（服务注册发现eureka，RPC，GRPC），分布式一致性
- 区块链（比特币，以太坊）
- MySQL，MyBatis，Redis，MongoDB，Oracle，Solr
- Nodejs(Express，mongoose), 对于docker, Kubernetes有一定了解
- Git，SVN，Maven，IntelliJ IDEA, Tomcat，JBoss

---

## 工作经历
### 上海凯石财富基金销售有限公司（2017.05 ~ 至今）
- 公司背景：凯石总部屹立于外滩，旗下凯石投资是国内最为优秀的私募基金管理公司之一，因其稳健的投资风格、专业的研究实力以及长期出色的投资业绩受到国内投资者的一致肯定，并成为国际顶级投资机构在中国的投资伙伴。基于透明、规范的公募基金产品，提供专业、科学的资产配置方案，帮助“品智家庭”享受资本市场发展的红利。
- 职责：“飞鱼”项目
- 技术：JDK8 + Spring Cloud + Oracle + MyBatis + Redis + RabbitMQ + Hystrix + MongoDB（spring cloud全套解决方案）
- 主要负责基金销售平台业务的开发和公司架构优化，包括：
    1. 主要负责“飞鱼”项目功能（微信版），完成产品的迭代
    2. 负责App业务功能接口
    3. 完成Pc版本需求和功能
    4. 负责公司基金数据的处理，用户交易，用户持仓，收益计算
    5. 服务升级优化
- 主要成就：
    1. 完成基金基础信息的迁移重构（SOA迁移至微服务），大幅度减少代码维护成本，提升代码质量。
    2. 对基金基础信息进行分类，基金基础数据结构优化。数据结构优化，提升代码效率。
    3. 基金推荐，根据投资者风格推荐不同类型的基金
    4. 搜索，基金搜索服务（使用solr改善搜索速度）
    5. 基金数据源采集处理
    6. 恒生交易系统接口优化，解决分布式一致性等问题。
    7. 根据基金研究员自定义组合数据，计算组合收益，组合调仓。
    8. 计算用户基金持仓，收益率相关数据。


---

### 银科控股（上海）（2016.03 ~ 2017.05）
- 公司背景：互联网现货交易平台。主要是为个人投资者在国内三大贵金属交易所(包括上海黄金交易所、天津贵金属交易所和广东贵金属交易中心)进行白银、黄金和其他贵金属或大宗商品现货投资提供交易服务。
- 职责：公司相关app的功能实现，系统维护，代码优化，技术预研。
- 技术：Java + SpringMVC + MyBatis + MySQL + Hessian + Redis + RabbitMQ + Hystrix + Nodejs + MongoDB，采用集群分布式部署。
- 主要负责期货交易平台开发，包括：
    1. 用户交易行情模块。用户，账号，业务管理；注册开户激活。获取交易行情。
    2. APP平仓抽奖功能。用户抽奖领奖，用户收货地址，奖品管理。
    3. 用户交易积分卡券。将用户的交易平仓记录转化积分。
    4. 大量用户消息推送。APP消息通知，微信消息推送（图文消息，模板消息推送）。
    5. 直播室管理。
- 主要成就：
    1. 主导设计用户积分系统的数据字典和积分卡券数据结构。
    2. 完成微盘宝APP用户大规模消息通知推送，解决了推送慢，重复推送的问题。解决在高并发平仓过程中Redis队列压力过大的问题。
    3. 自动化测试环境搭建优化。SVN迁移到Git， 对公司现有配置文件方式进行优化，自动化构建环境的搭建，解决多个环境下构建复杂的问题。对maven配置优化，解决版本依赖冲突，对Jar包版本集中式管理。
    4. 对公司原有用户账号体系进行优化，代码重构。将新的技术框架引入项目中，并顺利上线。
    5. 对目前项目中Redis使用方式进行优化，并给出了一套比较合理的解决方案
    6. 优化HttpClient，使用Hystrix服务降级，增加功能容错率。
---
### 烽火通信（武汉）（2015.07 ~ 2016.03）
- 公司背景：国内优秀的信息通信领域设备与网络解决方案提供商。
- 职责:增值产品的维护，新功能的开发，部分功能优化改进文档撰写，针对 部分需求编写软件详细设计文档。
- 技术:Java + SpringMVC + Mysql + Mybatis + C# + Html5 + Angularjs  
- 主要功能点:
    1. Web增值网管平台。 
    2. 网络数据链路分析。
-----
## 证书及开源项目作品

### 开源项目
- [blockchain](https://github.com/suyuanhxx/blockchain.git): 使用Go语言编写的简易区块链项目
- [crawler](https://github.com/suyuanhxx/crawler): Go语言编写的爬虫项目，爬取tumblr关注博主图片，视频
- [zrxlaw](https://github.com/suyuanhxx/zrxlaw): Nodejs 编写的简单增删改查项目

---
### 证书
- 软件设计师（中级）
---
## 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。

