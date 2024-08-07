---
timezone: Asia/Shanghai
---

> 请在上边的 timezone 添加你的当地时区，这会有助于你的打卡状态的自动化更新，如果没有添加，默认为北京时间 UTC+8 时区
> 时区请参考以下列表，请移除 # 以后的内容

timezone: Pacific/Honolulu # 夏威夷-阿留申标准时间 (UTC-10)

timezone: America/Anchorage # 阿拉斯加标准时间 (UTC-9)

timezone: America/Los_Angeles # 太平洋标准时间 (UTC-8)

timezone: America/Denver # 山地标准时间 (UTC-7)

timezone: America/Chicago # 中部标准时间 (UTC-6)

timezone: America/New_York # 东部标准时间 (UTC-5)

timezone: America/Halifax # 大西洋标准时间 (UTC-4)

timezone: America/St_Johns # 纽芬兰标准时间 (UTC-3:30)

timezone: America/Sao_Paulo # 巴西利亚时间 (UTC-3)

timezone: Atlantic/Azores # 亚速尔群岛时间 (UTC-1)

timezone: Europe/London # 格林威治标准时间 (UTC+0)

timezone: Europe/Berlin # 中欧标准时间 (UTC+1)

timezone: Europe/Helsinki # 东欧标准时间 (UTC+2)

timezone: Europe/Moscow # 莫斯科标准时间 (UTC+3)

timezone: Asia/Dubai # 海湾标准时间 (UTC+4)

timezone: Asia/Kolkata # 印度标准时间 (UTC+5:30)

timezone: Asia/Dhaka # 孟加拉国标准时间 (UTC+6)

timezone: Asia/Bangkok # 中南半岛时间 (UTC+7)

timezone: Asia/Shanghai # 中国标准时间 (UTC+8)

timezone: Asia/Tokyo # 日本标准时间 (UTC+9)

timezone: Australia/Sydney # 澳大利亚东部标准时间 (UTC+10)

timezone: Pacific/Auckland # 新西兰标准时间 (UTC+12)

# ZK 残酷共学第 1 期残酷指引

> ⚠️ 正式开始前请确保你在身体上和精神上都处于合适的状态，请刻意练习，残酷面对 🆒。为方便检索 The First ZK Intensive CoLearning 简写为 ZICL1st，第 2 期即为ZICL2nd，第 3 期即为 ZICL3rd，以此类推。

> ⚠️ 报名需要按要求认真填写下面 [ XXX ] 部分，方可通过报名审核，通过审核即可开始自主学习。

## 共学内容

第一期的重点是向大家介绍什么是 ZK、 ZKP 的基础知识，以及 Circom 代码入门，有一定难度，共学资料如下：

- 课前学习：
    - 20min 的视频：[初步理解 ZK 是什么](https://www.youtube.com/watch?v=fOGdb1CTu5c)
    - 70min 的播客：[零知识证明：一场”无知“的游戏](https://www.xiaoyuzhoufm.com/episode/6672a76bb6a8412729e0b103)
- 第一周：7 月 29 日 - 8 月 4 日：Introduction and History of ZKP
    - 100min 的视频：[ZKP Lecture 1: Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo)
    - [（一）初识「零知识」与「证明」](https://learn.z2o-k7e.world/zkp-intro/1/zkp-back.html)
    - [（二）理解「模拟」](https://learn.z2o-k7e.world/zkp-intro/2/zkp-simu.html)
    - [（三）寻找「知识」](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html)
    - [（四）随机「挑战」](https://learn.z2o-k7e.world/zkp-intro/4/zkp-rom.html)
    - [（五）埋藏「秘密」](https://learn.z2o-k7e.world/zkp-intro/5/zkp-crs.html)
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

本次共学资料前两周的 lecture 来自 [zk-learning](https://zk-learning.org/)，博客来自 [《探索零知识证明系列》](https://learn.z2o-k7e.world/zkp-intro/toc.html)和[《从零开始学习 zk-SNARK》](https://learn.z2o-k7e.world/zk-snarks/toc.html)，第三周的 Circom 部分来自 [0xparc](https://zkiap.com/)，视频讲解为 [ZK Shanghai](https://zkshanghai.xyz/) 的中文版本。学有余力者可以依此找到更多的扩展内容。

### **最后，非常感谢安比实验室郭宇老师对于本次共学资料选择的指导！**

---

# Hazel Gong
1. 自我介绍
   数学和物理专业毕业。之前在做 AI 产品。最近在学习 web3 的技术。
3. 你认为你会完成本次残酷学习吗？
   会。
5. 目前阶段对于 ZK 的了解？
   了解概念。之前学过一些数论、看过 interactive proofs 相关的论文。看完了本次 colearning week1 前几篇文章。

## Notes

<!-- Content_START -->

### 2024.07.29

学习主题：[Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo)
学习内容小结：

Basic concepts: 

Interactive proofs:
- There is a prover and a verifier. Both are algorithms. The prover sends a string to the verifier. The verifier decides whether to accept or reject it. 

Efficiently verifiable proofs (NP proofs):
- Proof is short. Verifier has polynomial time to verify. 
- claim x
- short proof w: length |w| is polynomial in |x| (so |w|=|x|^a, a is a number? )
- verifier V is a function. accepts x if V(x, w)=1, else reject. V takes time polynomial in |x|.

Polynomial time: 
- a class of problems whose running time grows polynomially with the size of the input. (用来形容算法复杂度，更加复杂的算法可能会是 exponential time，更简单的算法可能会是 linear time)

NP-Language:
L is an NP-language (or NP-decision problem) if there is a poly(|x|)-time verifier V with completeness (true claims with short proofs evaluates to 1) and soundness (false claims have no proof). 

ZKP: prove that I have the knowledge without giving away the knowledge, using interactive probabilistic proof. 
- through polynomial interactions
- randomness: V is randomized, can err in accept/reject with small probability. 

Interactive proof model
- P, V know the claim x
- V is probabilistic polynomial time
- V takes in x, and all interactions between them to decide whether to accept or reject.


### 2024.07.30

学习主题：[Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo)

学习内容小结：

Example of an interactive proof: Claim QR = {(N,y): there exists x such that $y=x^2$ mod N}. 

P: choose random r such that $1 \leq r \leq N$ with $gcd(r,N)=1$. Send $s=r^2$ mod N. 

- If P sends square root of both s and sy mod N, then V will know the claim is true but get $\sqrt{y} = x$ mod N. 
- So P instead sends either s or sy mod N, but V chooses which one to send based on  a coin flip.
- If heads, send z=r; if tails, send z=r$\sqrt{y}$ mod N. Here, the random r masks $\sqrt{y}$.
- Then V accepts only if $z^2 = sy^b$ mod N. Since P has sent s.

To show that a proof is a zero-knowledge interactive proof of knowledge, one must show:
- completeness: if the claim is true, V accepts with probability $\geq c$ (usually it's 1). 
- soundness: if the claim is false, V accepts with probability $\leq s$ (usually it's 1/2).
- c and s are polynomial apart $c-s\geq \frac{1}{poly(|x|)}$ (notice that $\frac{1}{poly(|x|)}$ is a measure of magnitude, it's much bigger than $\frac{1}{e^{|x|}}$ for example. )
- zero-knowledge: what the verifier V can compute after the proof = what V can compute before the proof. Prove that the verifier's view can be simulated by a zero-knowledge simulator (compuationally indistinguishable from a simulated view).
- proof of knowledge: we need to make sure P really has the knowledge $x=\sqrt{y}$ given his actions (proof using an extractor who can use a rewinding technique, record the randomness, and perform both actions, then recover the knowledge of P. )

Intuitions of the proof: 
- There are many possible proofs, depending on the random r chosen by P.
- Each proof has 2 parts, seeing either gives zero knowledge, seeing both implies 100% correctness.
- Verifier chooses at random which of the two parts he wants. Verifies over and over again. The ability of the P to give him either part of the answer convinces V that P has the knowledge. But the whole process is zero-knowledge.


### 2024.07.31
学习主题： 
1. Lecture 1 最后 40min 没有完全理解，也许看一些别的材料里面的例子，再回来理解。
2. 略读 Week 1 blog article #4: https://learn.z2o-k7e.world/zkp-intro/4/zkp-rom.html#%E9%87%8D%E5%BB%BA%E4%BF%A1%E4%BB%BB--%E9%9A%8F%E6%9C%BA%E9%A2%84%E8%A8%80%E7%B2%BE%E7%81%B5

学习内容小结：
1. Every NP-decision problem has a zero-knowledge interactive proof (I skipped the proof for this). Applications.
2. Interactive ZK 可以通过多轮交互来确保 prover 作弊成功的可能性可忽略不计。随机数挑战是交互式证明的信任根基。NIZK 是单轮交互的证明。在这里面，prover 通过单向函数 hash function 生成一个难以事先预测的随机数，来代替在 interactive ZK 中 verifier 提供的随机数。

<!-- Content_END -->
