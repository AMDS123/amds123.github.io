---
layout: post
title: "Stochastic Channel Decorrelation Network and Its Application to Visual Tracking"
date: 2018-07-03 12:03:21
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Relation
author: Jie Guo, Tingfa Xu, Shenwang Jiang, Ziyi Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) have dominated many computer vision domains because of their great power to extract good features automatically. However, many deep CNNs-based computer vison tasks suffer from lack of train-ing data while there are millions of parameters in the deep models. Obviously, these two biphase violation facts will re-sult in parameter redundancy of many poorly designed deep CNNs. Therefore, we look deep into the existing CNNs and find that the redundancy of network parameters comes from the correlation between features in different channels within a convolutional layer. To solve this problem, we propose the stochastic channel decorrelation (SCD) block which, in every iteration, randomly selects multiple pairs of channels within a convolutional layer and calculates their normalized cross cor-relation (NCC). Then a squared max-margin loss is proposed as the objective of SCD to suppress correlation and keep di-versity between channels explicitly. The proposed SCD is very flexible and can be applied to any current existing CNN models simply. Based on the SCD and the Fully-Convolutional Siamese Networks, we proposed a visual tracking algorithm to verify the effectiveness of SCD.

##### Abstract (translated by Google)
深度卷积神经网络（CNN）已经占据了许多计算机视觉领域，因为它们能够自动提取好的特征。然而，许多基于CNN的深度计算机视觉任务都缺乏训练数据，而深度模型中有数百万个参数。显然，这两个双相违规事实将导致许多设计不佳的深CNN的参数冗余。因此，我们深入研究现有的CNN，发现网络参数的冗余来自卷积层内不同信道的特征之间的相关性。为了解决这个问题，我们提出了随机信道去相关（SCD）块，其在每次迭代中随机选择卷积层内的多对信道并计算它们的归一化交叉相关（NCC）。然后提出平方最大边际损失作为SCD的目标，以抑制相关性并明确地保持通道之间的多样性。所提出的SCD非常灵活，可以简单地应用于任何现有的CNN模型。基于SCD和全卷积连体网络，我们提出了一种可视化跟踪算法来验证SCD的有效性。

##### URL
[https://arxiv.org/abs/1807.01103](https://arxiv.org/abs/1807.01103)

##### PDF
[https://arxiv.org/pdf/1807.01103](https://arxiv.org/pdf/1807.01103)

