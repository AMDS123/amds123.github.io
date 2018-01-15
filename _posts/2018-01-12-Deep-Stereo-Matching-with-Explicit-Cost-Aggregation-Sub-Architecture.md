---
layout: post
title: "Deep Stereo Matching with Explicit Cost Aggregation Sub-Architecture"
date: 2018-01-12 05:58:27
categories: arXiv_CV
tags: arXiv_CV Attention CNN
author: Lidong Yu, Yucheng Wang, Yuwei Wu, Yunde Jia
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have shown excellent performance for stereo matching. Many efforts focus on the feature extraction and similarity measurement of the matching cost computation step while less attention is paid on cost aggregation which is crucial for stereo matching. In this paper, we present a learning-based cost aggregation method for stereo matching by a novel sub-architecture in the end-to-end trainable pipeline. We reformulate the cost aggregation as a learning process of the generation and selection of cost aggregation proposals which indicate the possible cost aggregation results. The cost aggregation sub-architecture is realized by a two-stream network: one for the generation of cost aggregation proposals, the other for the selection of the proposals. The criterion for the selection is determined by the low-level structure information obtained from a light convolutional network. The two-stream network offers a global view guidance for the cost aggregation to rectify the mismatching value stemming from the limited view of the matching cost computation. The comprehensive experiments on challenge datasets such as KITTI and Scene Flow show that our method outperforms the state-of-the-art methods.

##### Abstract (translated by Google)
深度神经网络在立体匹配方面表现出色。对匹配成本计算步骤的特征提取和相似度测量方面进行了大量的工作，而对于立体匹配至关重要的成本聚合却不被重视。在本文中，我们提出了一种基于学习的成本聚合方法，通过在端到端可训练管道中的新型子体系结构进行立体匹配。我们将成本汇总重新形成为成本汇总提案的生成和选择的学习过程，其指示可能的成本汇总结果。成本汇聚子架构是通过双流网络来实现的，一个用于生成成本汇总提议，另一个用于选择提案。选择标准由从轻卷积网络获得的低级结构信息确定。双流网络提供了成本聚合的全局视图指导，以纠正由于匹配成本计算有限的观点而导致的不匹配值。 KITTI和Scene Flow等挑战数据集的综合实验表明，我们的方法胜过了最先进的方法。

##### URL
[http://arxiv.org/abs/1801.04065](http://arxiv.org/abs/1801.04065)

##### PDF
[http://arxiv.org/pdf/1801.04065](http://arxiv.org/pdf/1801.04065)

