---
layout: post
title: "Cell Selection with Deep Reinforcement Learning in Sparse Mobile Crowdsensing"
date: 2018-05-24 06:18:41
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Transfer_Learning Inference
author: Leye Wang, Wenbin Liu, Daqing Zhang, Yasha Wang, En Wang, Yongjian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Sparse Mobile CrowdSensing (MCS) is a novel MCS paradigm where data inference is incorporated into the MCS process for reducing sensing costs while its quality is guaranteed. Since the sensed data from different cells (sub-areas) of the target sensing area will probably lead to diverse levels of inference data quality, cell selection (i.e., choose which cells of the target area to collect sensed data from participants) is a critical issue that will impact the total amount of data that requires to be collected (i.e., data collection costs) for ensuring a certain level of quality. To address this issue, this paper proposes a Deep Reinforcement learning based Cell selection mechanism for Sparse MCS, called DR-Cell. First, we properly model the key concepts in reinforcement learning including state, action, and reward, and then propose to use a deep recurrent Q-network for learning the Q-function that can help decide which cell is a better choice under a certain state during cell selection. Furthermore, we leverage the transfer learning techniques to reduce the amount of data required for training the Q-function if there are multiple correlated MCS tasks that need to be conducted in the same target area. Experiments on various real-life sensing datasets verify the effectiveness of DR-Cell over the state-of-the-art cell selection mechanisms in Sparse MCS by reducing up to 15% of sensed cells with the same data inference quality guarantee.

##### Abstract (translated by Google)
稀疏移动CrowdSensing（MCS）是一种新颖的MCS范式，其中数据推理被纳入MCS过程中，以降低传感成本，同时保证其质量。由于来自目标感测区域的不同小区（子区域）的感测数据可能会导致不同程度的推理数据质量，因此小区选择（即选择目标区域的哪些小区从参与者收集感测数据）是关键问题会影响需要收集的数据总量（即数据收集成本），以确保达到一定的质量水平。为了解决这个问题，本文提出了一种基于Deep Reinforcement学习的稀疏MCS的小区选择机制，称为DR-Cell。首先，我们对包括状态，行动和奖励在内的强化学习中的关键概念进行了恰当的建模，然后建议使用深度循环的Q网络来学习Q函数，这可以帮助确定在特定状态下哪个细胞是更好的选择在细胞选择期间。此外，如果存在多个需要在同一目标区域进行的相关MCS任务，我们将利用传输学习技术来减少训练Q函数所需的数据量。对各种现实生活中的感应数据集进行的实验通过在相同的数据推理质量保证下将多达15％的感知细胞减少到最低，从而验证了DR-Cell相对于稀疏MCS中最先进的细胞选择机制的有效性。

##### URL
[http://arxiv.org/abs/1804.07047](http://arxiv.org/abs/1804.07047)

##### PDF
[http://arxiv.org/pdf/1804.07047](http://arxiv.org/pdf/1804.07047)

