---
layout: post
title: "Recurrent-OctoMap: Learning State-based Map Refinement for Long-Term Semantic Mapping with 3D-Lidar Data"
date: 2018-07-02 23:28:37
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Li Sun, Zhi Yan, Anestis Zaganidis, Cheng Zhao, Tom Duckett
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel semantic mapping approach, Recurrent-OctoMap, learned from long-term 3D Lidar data. Most existing semantic mapping approaches focus on improving semantic understanding of single frames, rather than 3D refinement of semantic maps (i.e. fusing semantic observations). The most widely-used approach for 3D semantic map refinement is a Bayes update, which fuses the consecutive predictive probabilities following a Markov-Chain model. Instead, we propose a learning approach to fuse the semantic features, rather than simply fusing predictions from a classifier. In our approach, we represent and maintain our 3D map as an OctoMap, and model each cell as a recurrent neural network (RNN), to obtain a Recurrent-OctoMap. In this case, the semantic mapping process can be formulated as a sequence-to-sequence encoding-decoding problem. Moreover, in order to extend the duration of observations in our Recurrent-OctoMap, we developed a robust 3D localization and mapping system for successively mapping a dynamic environment using more than two weeks of data, and the system can be trained and deployed with arbitrary memory length. We validate our approach on the ETH long-term 3D Lidar dataset [1]. The experimental results show that our proposed approach outperforms the conventional "Bayes update" approach.

##### Abstract (translated by Google)
本文提出了一种新的语义映射方法，Recurrent-OctoMap，从长期的3D激光雷达数据中学习。大多数现有的语义映射方法侧重于改进单帧的语义理解，而不是语义映射的3D细化（即融合语义观察）。用于3D语义地图细化的最广泛使用的方法是贝叶斯更新，其融合了马尔可夫链模型之后的连续预测概率。相反，我们提出了一种融合语义特征的学习方法，而不是简单地融合分类器的预测。在我们的方法中，我们将我们的3D地图表示和维护为OctoMap，并将每个细胞建模为递归神经网络（RNN），以获得Recurrent-OctoMap。在这种情况下，语义映射过程可以表示为序列到序列的编码 - 解码问题。此外，为了延长Recurrent-OctoMap中观测的持续时间，我们开发了一个强大的3D定位和绘图系统，用于使用两周以上的数据连续映射动态环境，并且系统可以使用任意内存进行训练和部署长度。我们验证了我们对ETH长期3D激光雷达数据集的方法[1]。实验结果表明，我们提出的方法优于传统的“贝叶斯更新”方法。

##### URL
[https://arxiv.org/abs/1807.00925](https://arxiv.org/abs/1807.00925)

##### PDF
[https://arxiv.org/pdf/1807.00925](https://arxiv.org/pdf/1807.00925)

