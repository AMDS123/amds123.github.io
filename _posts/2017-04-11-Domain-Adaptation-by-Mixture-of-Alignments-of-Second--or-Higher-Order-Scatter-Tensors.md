---
layout: post
title: "Domain Adaptation by Mixture of Alignments of Second- or Higher-Order Scatter Tensors"
date: 2017-04-11 13:43:24
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Piotr Koniusz, Yusuf Tas, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an approach to the domain adaptation, dubbed Second- or Higher-order Transfer of Knowledge (So-HoT), based on the mixture of alignments of second- or higher-order scatter statistics between the source and target domains. The human ability to learn from few labeled samples is a recurring motivation in the literature for domain adaptation. Towards this end, we investigate the supervised target scenario for which few labeled target training samples per category exist. Specifically, we utilize two CNN streams: the source and target networks fused at the classifier level. Features from the fully connected layers fc7 of each network are used to compute second- or even higher-order scatter tensors; one per network stream per class. As the source and target distributions are somewhat different despite being related, we align the scatters of the two network streams of the same class (within-class scatters) to a desired degree with our bespoke loss while maintaining good separation of the between-class scatters. We train the entire network in end-to-end fashion. We provide evaluations on the standard Office benchmark (visual domains), RGB-D combined with Caltech256 (depth-to-rgb transfer) and Pascal VOC2007 combined with the TU Berlin dataset (image-to-sketch transfer). We attain state-of-the-art results.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于源域和目标域之间的二阶或更高阶散点统计的对齐混合的域适应方法，称为二阶或更高阶的知识转移（So-HoT） 。人类从少数标记样本中学习的能力是领域适应性文献中反复出现的动机。为此，我们调查每个类别存在少量标记的目标训练样本的监督目标情景。具体来说，我们利用两个CNN流：源和目标网络在分类器级融合。每个网络的完全连接层fc7的特征用于计算二阶或甚至更高阶的散射张量;每类每个网络流一个。由于源和目标分布尽管相关有所不同，我们将同一类（类内散点图）的两个网络流的散点图与我们定制的损失调整到期望的程度，同时保持类间散点图。我们以端到端的方式训练整个网络。我们提供标准Office基准（视觉领域），RGB-D与Caltech256（深度到RGB转移）相结合的评估以及与TU柏林数据集（图像到草图转移）相结合的Pascal VOC2007。我们获得了最先进的成果。

##### URL
[https://arxiv.org/abs/1611.08195](https://arxiv.org/abs/1611.08195)

##### PDF
[https://arxiv.org/pdf/1611.08195](https://arxiv.org/pdf/1611.08195)

