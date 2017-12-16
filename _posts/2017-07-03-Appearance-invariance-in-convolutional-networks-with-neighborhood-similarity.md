---
layout: post
title: "Appearance invariance in convolutional networks with neighborhood similarity"
date: 2017-07-03 20:53:56
categories: arXiv_CV
tags: arXiv_CV Attention CNN Detection Recognition
author: Tolga Tasdizen, Mehdi Sajjadi, Mehran Javanmardi, Nisha Ramesh
mathjax: true
---

* content
{:toc}

##### Abstract
We present a neighborhood similarity layer (NSL) which induces appearance invariance in a network when used in conjunction with convolutional layers. We are motivated by the observation that, even though convolutional networks have low generalization error, their generalization capability does not extend to samples which are not represented by the training data. For instance, while novel appearances of learned concepts pose no problem for the human visual system, feedforward convolutional networks are generally not successful in such situations. Motivated by the Gestalt principle of grouping with respect to similarity, the proposed NSL transforms its input feature map using the feature vectors at each pixel as a frame of reference, i.e. center of attention, for its surrounding neighborhood. This transformation is spatially varying, hence not a convolution. It is differentiable; therefore, networks including the proposed layer can be trained in an end-to-end manner. We analyze the invariance of NSL to significant changes in appearance that are not represented in the training data. We also demonstrate its advantages for digit recognition, semantic labeling and cell detection problems.

##### Abstract (translated by Google)
我们提出了一个邻域相似层（NSL），当与卷积层一起使用时，在网络中引入了外观不变性。我们的动机是，即使卷积网络具有较低的泛化误差，它们的泛化能力也不会扩展到训练数据未表示的样本。例如，虽然学习概念的新颖外观对人类视觉系统没有任何问题，但前馈卷积网络在这种情况下一般不会成功。在相似性分组的格式塔原理的推动下，所提出的NSL使用每个像素处的特征向量作为参考帧（即，关注中心）来针对其周围邻域来变换其输入特征映射。这种变换是空间变化的，因此不是卷积。这是可区分的;因此，包括所提议的层的网络可以以端对端的方式进行训练。我们分析NSL对于训练数据中没有表现出来的显着变化的不变性。我们还展示了它在数字识别，语义标记和细胞检测问题方面的优势。

##### URL
[https://arxiv.org/abs/1707.00755](https://arxiv.org/abs/1707.00755)

##### PDF
[https://arxiv.org/pdf/1707.00755](https://arxiv.org/pdf/1707.00755)

