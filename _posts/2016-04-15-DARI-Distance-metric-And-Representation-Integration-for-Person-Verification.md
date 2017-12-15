---
layout: post
title: "DARI: Distance metric And Representation Integration for Person Verification"
date: 2016-04-15 07:21:26
categories: arXiv_CV
tags: arXiv_CV CNN Represenation_Learning
author: Guangrun Wang, Liang Lin, Shengyong Ding, Ya Li, Qing Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The past decade has witnessed the rapid development of feature representation learning and distance metric learning, whereas the two steps are often discussed separately. To explore their interaction, this work proposes an end-to-end learning framework called DARI, i.e. Distance metric And Representation Integration, and validates the effectiveness of DARI in the challenging task of person verification. Given the training images annotated with the labels, we first produce a large number of triplet units, and each one contains three images, i.e. one person and the matched/mismatch references. For each triplet unit, the distance disparity between the matched pair and the mismatched pair tends to be maximized. We solve this objective by building a deep architecture of convolutional neural networks. In particular, the Mahalanobis distance matrix is naturally factorized as one top fully-connected layer that is seamlessly integrated with other bottom layers representing the image feature. The image feature and the distance metric can be thus simultaneously optimized via the one-shot backward propagation. On several public datasets, DARI shows very promising performance on re-identifying individuals cross cameras against various challenges, and outperforms other state-of-the-art approaches.

##### Abstract (translated by Google)
近十年来，特征表示学习和距离度量学习得到了飞速的发展，而这两个步骤往往分开讨论。为了探索它们之间的交互作用，本文提出了一个称为DARI的端到端学习框架，即距离度量和表示集成，并验证了DARI在人员验证这个具有挑战性的任务中的有效性。给定用标签注释的训练图像，我们首先产生大量的三元组单元，并且每一个包含三个图像，即一个人和匹配/不匹配参考。对于每个三元组单元，匹配对和不匹配对之间的距离差异倾向于最大化。我们通过构建卷积神经网络的深层结构来解决这个问题。特别是，Mahalanobis距离矩阵自然地被分解为一个顶层完全连接层，与表示图像特征的其他底层无缝集成。图像特征和距离度量因此可以通过一次反向传播同时被优化。在一些公开的数据集上，DARI在重新识别跨越相机的个人面临各种挑战方面表现出了非常有希望的表现，并且胜过了其他最先进的方法。

##### URL
[https://arxiv.org/abs/1604.04377](https://arxiv.org/abs/1604.04377)

##### PDF
[https://arxiv.org/pdf/1604.04377](https://arxiv.org/pdf/1604.04377)

