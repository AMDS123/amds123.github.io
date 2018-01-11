---
layout: post
title: "Chameleon: A Hybrid Secure Computation Framework for Machine Learning Applications"
date: 2018-01-10 04:57:56
categories: arXiv_AI
tags: arXiv_AI CNN Classification
author: M. Sadegh Riazi, Christian Weinert, Oleksandr Tkachenko, Ebrahim M. Songhori, Thomas Schneider, Farinaz Koushanfar
mathjax: true
---

* content
{:toc}

##### Abstract
We present Chameleon, a novel hybrid (mixed-protocol) framework for secure function evaluation (SFE) which enables two parties to jointly compute a function without disclosing their private inputs. Chameleon combines the best aspects of generic SFE protocols with the ones that are based upon additive secret sharing. In particular, the framework performs linear operations in the ring $\mathbb{Z}_{2^l}$ using additively secret shared values and nonlinear operations using Yao's Garbled Circuits or the Goldreich-Micali-Wigderson protocol. Chameleon departs from the common assumption of additive or linear secret sharing models where three or more parties need to communicate in the online phase: the framework allows two parties with private inputs to communicate in the online phase under the assumption of a third node generating correlated randomness in an offline phase. Almost all of the heavy cryptographic operations are precomputed in an offline phase which substantially reduces the communication overhead. Chameleon is both scalable and significantly more efficient than the ABY framework (NDSS'15) it is based on. Our framework supports signed fixed-point numbers. In particular, Chameleon's vector dot product of signed fixed-point numbers improves the efficiency of mining and classification of encrypted data for algorithms based upon heavy matrix multiplications. Our evaluation of Chameleon on a 5 layer convolutional deep neural network shows 133x and 4.2x faster executions than Microsoft CryptoNets (ICML'16) and MiniONN (CCS'17), respectively.

##### Abstract (translated by Google)
我们提出变色龙，一个新的混合（混合协议）安全功能评估（SFE）框架，使双方能够联合计算一个功能，而不公开他们的私人投入。变色龙将通用SFE协议的最佳方面与基于加性秘密共享的协议结合在一起。具体来说，框架使用加性秘密共享值和使用Yao's Garbled Circuits或Goldreich-Micali-Wigderson协议的非线性运算在环$ \ mathbb {Z} _ {2 ^ l} $中执行线性运算。变色龙离开了加成或线性秘密共享模型的共同假设，三方或更多方需要在在线阶段进行通信：框架允许具有私人输入的双方在在线阶段进行通信，假定第三节点产生相关的随机性在离线阶段。几乎所有沉重的密码操作都是在离线阶段预先计算的，这大大减少了通信开销。变色龙既可以扩展，也可以比它基于的ABY框架（NDSS'15）高效得多。我们的框架支持带符号的定点数字。具体而言，变色龙的带符号定点数的向量点积提高了基于重矩阵乘法的算法的加密数据的挖掘和分类效率。我们对5层卷积深度神经网络上的变色龙的评估显示，分别比Microsoft CryptoNet（ICML'16）和MiniONN（CCS'17）快133倍和4.2倍的执行速度。

##### URL
[https://arxiv.org/abs/1801.03239](https://arxiv.org/abs/1801.03239)

##### PDF
[https://arxiv.org/pdf/1801.03239](https://arxiv.org/pdf/1801.03239)

