---
layout: post
title: "Few Shot Learning with Simplex"
date: 2018-07-27 16:52:57
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Bowen Zhang, Xifan Zhang, Fan Cheng, Deli Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has made remarkable achievement in many fields. However, learning the parameters of neural networks usually demands a large amount of labeled data. The algorithms of deep learning, therefore, encounter difficulties when applied to supervised learning where only little data are available. This specific task is called few-shot learning. To address it, we propose a novel algorithm for few-shot learning using discrete geometry, in the sense that the samples in a class are modeled as a reduced simplex. The volume of the simplex is used for the measurement of class scatter. During testing, combined with the test sample and the points in the class, a new simplex is formed. Then the similarity between the test sample and the class can be quantized with the ratio of volumes of the new simplex to the original class simplex. Moreover, we present an approach to constructing simplices using local regions of feature maps yielded by convolutional neural networks. Experiments on Omniglot and miniImageNet verify the effectiveness of our simplex algorithm on few-shot learning.

##### Abstract (translated by Google)
深度学习在许多领域取得了显着成就。然而，学习神经网络的参数通常需要大量标记数据。因此，当应用于仅有少量数据的监督学习时，深度学习算法遇到困难。这项具体任务称为少射学习。为了解决这个问题，我们提出了一种新的算法，用于使用离散几何的小镜头学习，因为类中的样本被建模为简化的单纯形。单形体的体积用于测量类散射。在测试期间，结合测试样本和类中的要点，形成一个新的单形。然后，可以使用新单形体与原始类单形体的体积比来量化测试样本和类之间的相似性。此外，我们提出了一种使用卷积神经网络产生的特征映射的局部区域来构造单纯形的方法。 Omniglot和miniImageNet上的实验验证了我们的单纯形算法在少数镜头学习中的有效性。

##### URL
[http://arxiv.org/abs/1807.10726](http://arxiv.org/abs/1807.10726)

##### PDF
[http://arxiv.org/pdf/1807.10726](http://arxiv.org/pdf/1807.10726)

