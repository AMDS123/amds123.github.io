---
layout: post
title: "Rebalancing Dockless Bike Sharing Systems"
date: 2018-02-13 12:43:03
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Prediction
author: Ling Pan, Qingpeng Cai, Zhixuan Fang, Pingzhong Tang, Longbo Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Bike sharing provides an environment-friendly way for traveling and is booming all over the world. Yet, due to the high similarity of user travel patterns, the bike imbalance problem constantly occurs, especially for dockless bike sharing systems, causing significant impact on service quality and company revenue. Thus, it has become a critical task for bike sharing systems to resolve such imbalance efficiently. We model this problem as a Markov decision process (MDP), which takes both temporal and spatial features into consideration. We propose a novel deep reinforcement learning algorithm called Loss-Reduced Reinforcement Pricing (LRP), which builds upon the deterministic policy gradient algorithm. Different from existing methods that often ignore spatial information and rely heavily on accurate prediction, LRP is embedded with a novel network architecture to incorporate the dependence of neighboring regions, for reducing the training loss in Q-function learning. We conduct extensive experiments to evaluate the performance of the LRP algorithm, based on trajectory data from Mobike, a major Chinese dockless bike sharing company. Results show that LRP performs close to the 24-timeslot look-ahead optimization, and outperforms state-of-the-art methods in both service level and bike distribution. It also transfers well when applied to unseen areas, and can even make additional profit with the given budget. We further propose the first hybrid rebalancing system, which take advantages of both the truck-based and user-based approaches, and outperforms each individual approach.

##### Abstract (translated by Google)
自行车共享为旅行提供了一种环保的方式，并在全世界蓬勃发展。然而，由于用户出行模式的高度相似性，自行车不平衡问题不断出现，特别是对于无码头自行车共享系统，对服务质量和公司收入造成重大影响。因此，自行车共享系统有效解决这种不平衡问题已成为一项关键任务。我们将此问题建模为马尔可夫决策过程（MDP），该过程考虑了时间和空间特征。我们提出了一种新的深度强化学习算法，称为减少损失的增强定价（LRP），它建立在确定性策略梯度算法的基础上。与经常忽略空间信息并且严重依赖准确预测的现有方法不同，LRP嵌入了新颖的网络结构，以结合相邻区域的依赖性，减少Q函数学习中的训练损失。我们根据来自中国主要无船自行车共享公司Mobike的轨迹数据，进行了广泛的实验来评估LRP算法的性能。结果表明，LRP执行接近24时隙预测优化，并且在服务级别和自行车分配中均优于最先进的方法。它适用于看不见的区域也可以很好地传输，甚至可以在给定的预算下获得额外的利润。我们进一步提出了第一个混合再平衡系统，该系统利用卡车和基于用户的方法，并优于每种方法。

##### URL
[http://arxiv.org/abs/1802.04592](http://arxiv.org/abs/1802.04592)

##### PDF
[http://arxiv.org/pdf/1802.04592](http://arxiv.org/pdf/1802.04592)

