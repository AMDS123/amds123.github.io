---
layout: post
title: "Cycle-Consistent Speech Enhancement"
date: 2018-09-06 23:55:49
categories: arXiv_CL
tags: arXiv_CL Adversarial
author: Zhong Meng, Jinyu Li, Yifan Gong, Biing-Hwang (Fred)Juang
mathjax: true
---

* content
{:toc}

##### Abstract
Feature mapping using deep neural networks is an effective approach for single-channel speech enhancement. Noisy features are transformed to the enhanced ones through a mapping network and the mean square errors between the enhanced and clean features are minimized. In this paper, we propose a cycle-consistent speech enhancement (CSE) in which an additional inverse mapping network is introduced to reconstruct the noisy features from the enhanced ones. A cycle-consistent constraint is enforced to minimize the reconstruction loss. Similarly, a backward cycle of mappings is performed in the opposite direction with the same networks and losses. With cycle-consistency, the speech structure is well preserved in the enhanced features while noise is effectively reduced such that the feature-mapping network generalizes better to unseen data. In cases where only unparalleled noisy and clean data is available for training, two discriminator networks are used to distinguish the enhanced and noised features from the clean and noisy ones. The discrimination losses are jointly optimized with reconstruction losses through adversarial multi-task learning. Evaluated on the CHiME-3 dataset, the proposed CSE achieves 19.60% and 6.69% relative word error rate improvements respectively when using or without using parallel clean and noisy speech data.

##### Abstract (translated by Google)
使用深度神经网络的特征映射是用于单通道语音增强的有效方法。通过映射网络将噪声特征转换为增强特征，并且最小化增强特征和干净特征之间的均方误差。在本文中，我们提出了一种循环一致的语音增强（CSE），其中引入了附加的逆映射网络来重建来自增强的噪声特征的噪声特征。强制执行循环一致约束以最小化重建损失。类似地，映射的后向循环在相反方向上执行，具有相同的网络和损耗。通过循环一致性，语音结构在增强的特征中得到很好的保留，同时有效地降低了噪声，使得特征映射网络更好地概括了看不见的数据。在只有无与伦比的噪声和干净数据可用于训练的情况下，使用两个鉴别器网络来区分增强和噪声特征与干净和噪声特征。通过对抗性多任务学习，通过重建损失共同优化歧视损失。根据CHiME-3数据集进行评估，当使用或不使用并行干净和有噪声的语音数据时，所提出的CSE分别实现19.60％和6.69％的相对字错误率改善。

##### URL
[https://arxiv.org/abs/1809.02253](https://arxiv.org/abs/1809.02253)

##### PDF
[https://arxiv.org/pdf/1809.02253](https://arxiv.org/pdf/1809.02253)

