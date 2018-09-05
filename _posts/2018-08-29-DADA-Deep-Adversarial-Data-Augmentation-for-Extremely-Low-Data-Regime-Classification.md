---
layout: post
title: "DADA: Deep Adversarial Data Augmentation for Extremely Low Data Regime Classification"
date: 2018-08-29 09:01:31
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Transfer_Learning Classification Deep_Learning Quantitative
author: Xiaofeng Zhang, Zhangyang Wang, Dong Liu, Qing Ling
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has revolutionized the performance of classification, but meanwhile demands sufficient labeled data for training. Given insufficient data, while many techniques have been developed to help combat overfitting, the challenge remains if one tries to train deep networks, especially in the ill-posed extremely low data regimes: only a small set of labeled data are available, and nothing -- including unlabeled data -- else. Such regimes arise from practical situations where not only data labeling but also data collection itself is expensive. We propose a deep adversarial data augmentation (DADA) technique to address the problem, in which we elaborately formulate data augmentation as a problem of training a class-conditional and supervised generative adversarial network (GAN). Specifically, a new discriminator loss is proposed to fit the goal of data augmentation, through which both real and augmented samples are enforced to contribute to and be consistent in finding the decision boundaries. Tailored training techniques are developed accordingly. To quantitatively validate its effectiveness, we first perform extensive simulations to show that DADA substantially outperforms both traditional data augmentation and a few GAN-based options. We then extend experiments to three real-world small labeled datasets where existing data augmentation and/or transfer learning strategies are either less effective or infeasible. All results endorse the superior capability of DADA in enhancing the generalization ability of deep networks trained in practical extremely low data regimes. Source code is available at https://github.com/SchafferZhang/DADA.

##### Abstract (translated by Google)
深度学习已经彻底改变了分类的性能，但同时需要足够的标记数据进行培训。鉴于数据不足，虽然已经开发了许多技术来帮助防止过度拟合，但是如果有人试图训练深度网络，特别是在病态极差的极低数据系统中，挑战仍然存在：只有一小部分标记数据可用，而且没有 -  - 包括未标记的数据 - 否则。这种制度产生于实际情况，其中不仅数据标记而且数据收集本身也很昂贵。我们提出了一种深层对抗数据增强（DADA）技术来解决这个问题，其中我们精心制定数据增强作为训练类条件和监督生成对抗网络（GAN）的问题。具体而言，提出了新的鉴别器损失以适应数据增加的目标，通过该目标实施实际和增强样本以促成并且在找到决策边界时保持一致。相应地开发了量身定制的培训技术。为了定量验证其有效性，我们首先进行了大量的模拟，以显示DADA大大优于传统的数据增强和一些基于GAN的选项。然后，我们将实验扩展到三个真实的小标记数据集，其中现有的数据增强和/或转移学习策略要么不太有效，要么不可行。所有结果都证明了DADA在提高在实际极低数据体系中训练的深度网络的泛化能力方面的卓越能力。源代码可在https://github.com/SchafferZhang/DADA获得。

##### URL
[http://arxiv.org/abs/1809.00981](http://arxiv.org/abs/1809.00981)

##### PDF
[http://arxiv.org/pdf/1809.00981](http://arxiv.org/pdf/1809.00981)

