---
layout: post
title: "Decoupled Learning for Conditional Adversarial Networks"
date: 2018-01-21 08:48:23
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge
author: Zhifei Zhang, Yang Song, Hairong Qi
mathjax: true
---

* content
{:toc}

##### Abstract
Incorporating encoding-decoding nets with adversarial nets has been widely adopted in image generation tasks. We observe that the state-of-the-art achievements were obtained by carefully balancing the reconstruction loss and adversarial loss, and such balance shifts with different network structures, datasets, and training strategies. Empirical studies have demonstrated that an inappropriate weight between the two losses may cause instability, and it is tricky to search for the optimal setting, especially when lacking prior knowledge on the data and network. This paper gives the first attempt to relax the need of manual balancing by proposing the concept of \textit{decoupled learning}, where a novel network structure is designed that explicitly disentangles the backpropagation paths of the two losses. Experimental results demonstrate the effectiveness, robustness, and generality of the proposed method. The other contribution of the paper is the design of a new evaluation metric to measure the image quality of generative models. We propose the so-called \textit{normalized relative discriminative score} (NRDS), which introduces the idea of relative comparison, rather than providing absolute estimates like existing metrics.

##### Abstract (translated by Google)
图像生成任务中广泛采用了编解码网与敌对网相结合的方法。我们观察到最新的成果是通过仔细平衡重建损失和对抗性损失获得的，并且这种平衡移动具有不同的网络结构，数据集和训练策略。实证研究表明，两种损失之间不恰当的权重可能会导致不稳定，寻找最佳的设置是非常棘手的，特别是当缺乏对数据和网络的先验知识时。本文首先尝试通过提出“解耦学习”的概念来放松手动平衡的需求，其中设计了一种新的网络结构，明确地解决了两种损失的反向传播路径。实验结果表明了该方法的有效性，鲁棒性和通用性。本文的另一个贡献是设计一个新的评估度量指标来衡量生成模型的图像质量。我们提出所谓的\ textit {归一化相对判别分数}（NRDS），它引入了相对比较的思想，而不是像现有的指标那样提供绝对估计。

##### URL
[https://arxiv.org/abs/1801.06790](https://arxiv.org/abs/1801.06790)

##### PDF
[https://arxiv.org/pdf/1801.06790](https://arxiv.org/pdf/1801.06790)

