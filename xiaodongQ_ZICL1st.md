---
timezone: Asia/Shanghai
---

# ZK 残酷共学第 1 期残酷指引

> ⚠️ 正式开始前请确保你在身体上和精神上都处于合适的状态，请刻意练习，残酷面对 🆒。为方便检索 The First ZK Intensive CoLearning 简写为 ZICL1st，第 2 期即为ZICL2nd，第 3 期即为 ZICL3rd，以此类推。

> ⚠️ 报名需要按要求认真填写下面 [ XXX ] 部分，方可通过报名审核，通过审核即可开始自主学习。

## 共学内容

第一期的重点是向大家介绍什么是 ZK、 ZKP 的基础知识，以及 Circom 代码入门，有一定难度，共学资料如下：

- 第一周：7 月 29 日 - 8 月 4 日：Introduction and History of ZKP
    - 20min 的视频：[初步理解 ZK 是什么](https://www.youtube.com/watch?v=fOGdb1CTu5c)
    - 70min 的播客：[零知识证明：一场”无知“的游戏](https://www.xiaoyuzhoufm.com/episode/6672a76bb6a8412729e0b103)
    - [（一）初识「零知识」与「证明」](https://learn.z2o-k7e.world/zkp-intro/1/zkp-back.html)
    - [（二）理解「模拟」](https://learn.z2o-k7e.world/zkp-intro/2/zkp-simu.html)
    - [（三）寻找「知识」](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html)
    - 100min 的视频：[ZKP Lecture 1: Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo)
- 第二周：8 月 5 日 - 8 月 11 日：Overview of Modern SNARK Constructions
    - 80min的视频： [ZKP Lecture 2: Overview of Modern SNARK Constructions](https://www.youtube.com/watch?v=bGEXYpt3sj0)
    - [1-Polynomial-Interaction-and-Proof](https://learn.z2o-k7e.world/zk-snarks/1-Polynomial-Interaction-and-Proof.html)
    - [2-Non-interactivity&Distributed-Setup](https://learn.z2o-k7e.world/zk-snarks/2-Non-interactivity&Distributed-Setup.html)
    - [3-General-Purpose-Computation](https://learn.z2o-k7e.world/zk-snarks/3-General-Purpose-Computation.html)
    - [4-Construction-Properties.md](https://learn.z2o-k7e.world/zk-snarks/4-Construction-Properties.html)
    - [5-Pinocchio-Protocol](https://learn.z2o-k7e.world/zk-snarks/5-Pinocchio-Protocol.html)
- 第三周：8 月 12 日 - 8 月 18 日：Write some Circom
    - 基础电路：
        - [ZK Shanghai 基础电路教学](https://www.youtube.com/watch?v=CTJ1JkYLiyw&ab_channel=SutuLabs)
        - 编辑器：[zkREPL](https://zkrepl.dev/)
        - [基础电路练习](https://github.com/wenjin1997/zkshanghai-workshop/blob/main/lecture2-homework.md) 这部分材料结合了Circom源码，可以多花时间来研究
    - 实用电路：
        - [ZK Shanghai 实用电路教学](https://www.youtube.com/watch?v=smJz5RdY0Nc)
        - 课程资源：[snarkjs resources (zkiap.com)](https://zkiap.com/snarkjs)、[What Is Semaphore? | Semaphore](https://docs.semaphore.pse.dev/)

本次共学资料前两周的 lecture 来自 [zk-learning](https://zk-learning.org/)，博客来自 [《探索零知识证明系列》](https://learn.z2o-k7e.world/zkp-intro/toc.html)和[《从零开始学习 zk-SNARK》](https://learn.z2o-k7e.world/zk-snarks/toc.html)，第三周的 Circom 部分来自 [0xparc](https://zkiap.com/)，视频讲解为 [ZK Shanghai](https://zkshanghai.xyz/) 的中文版本。郭宇老师还推荐了这篇文章[《Survey-SNARKs》](https://www.di.ens.fr/~nitulesc/files/Survey-SNARKs.pdf)，学有余力者可以依此找到更多的扩展内容。

### **最后，非常感谢安比实验室郭宇老师对于本次共学资料选择的指导！**

---

# {你的名字}
1. 自我介绍  
    CPP多年开发，学过Go、Rust，尝试搞Web3副业
2. 你认为你会完成本次残酷学习吗？  
    应该能
3. 目前阶段对于 ZK 的了解？  
    了解不多，仅限部分概念

## Notes

<!-- Content_START -->

### 2024.07.29

- 学习主题：了解ZKP（零知识证明，Zero-Knowledge Proof），以及共学提供的资料
- 学习内容小结：

1. Amit Sahai教授针对不同年龄和知识水平的人讲解ZKP的几个示例（Amit Sahai是UCLA的计算机方面的一位杰出教授，研究兴趣集中在密码学和安全等领域），初步了解零知识证明的作用。视频：[初步理解 ZK 是什么](https://www.youtube.com/watch?v=fOGdb1CTu5c)
2. 简单听了下介绍ZKP的中文播客，听得有点累，还是先看看文档吧
3. [z2o-k7e社区](https://learn.z2o-k7e.world/)整理的学习ZKP资料，看起来质量很不错

目前学习了：[1. 初识「零知识」与「证明」](https://learn.z2o-k7e.world/zkp-intro/1/zkp-back.html)

番外：  
找郭宇老师推特（[1dot2](https://twitter.com/1dot2)）过程中，看到已退推的[kurtpan.eth](https://twitter.com/kurtpan666)（复旦密码学博士，也是上面z2o-k7e项目的主要贡献者之一）博客上截取自《过河卒》的这篇文章：[过河卒·日出江花红胜火](https://zkfold.ing/guohezu-wd)。  
周六去杭州的web3 summer线下，正好嘉宾也谈到比特币白皮书和国人的渊源，引用文献的第一篇就是一个华人的文章。也就是上面文章中的[Wei Dai](https://en.wikipedia.org/wiki/Wei_Dai)。

这里简单记录每日学习小结，具体内容放在[zk_learn_note笔记](https://github.com/xiaodongQ/devNoteBackup/blob/master/%E5%90%84%E5%88%86%E7%B1%BB%E8%AE%B0%E5%BD%95/blockchain/zk_learn_note.md)。

### 2024.07.30

- 学习主题：学习 [2. 理解「模拟」](https://learn.z2o-k7e.world/zkp-intro/2/zkp-simu.html)
- 学习内容小结：主要讲述怎么证明系统是零知识的。真实世界和理想世界，模拟器可区分这两个世界，但是世界里的个体不可区分。这个模拟器可理解为计算机系统的快照。

概念还有点晦涩，似懂非懂，还需继续往下学习。

### 2024.07.31

- 学习主题：学习 [3. 寻找「知识」](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html)
- 学习内容小结：
    - 描述了可靠性和零知识，里面用数学知识来描述和证明加密算法，有点抽象，先放一放。
    - 通过里面的`单向映射`举例，对椭圆曲线加密算法（ECC）理解更直观了一点

### 2024.08.01

- 学习主题：密码学相关概念学习
- 学习内容小结：
    - 对称/非对称加密算法有哪些；
    - 数字签名、数字证书、数字信封、PKI、PMI等概念；
    - 国密标准
    - 相关笔记：[密码学相关学习笔记](https://github.com/xiaodongQ/devNoteBackup/blob/master/%E5%90%84%E5%88%86%E7%B1%BB%E8%AE%B0%E5%BD%95/blockchain/%E5%AF%86%E7%A0%81%E5%AD%A6_%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0.md)

<!-- Content_END -->
