---
layout: post
title: "Where are the Blobs: Counting by Localization with Point Supervision"
date: 2018-07-25 21:00:09
categories: arXiv_CV
tags: arXiv_CV Optimization Detection
author: Issam H. Laradji, Negar Rostamzadeh, Pedro O. Pinheiro, David Vazquez, Mark Schmidt
mathjax: true
---

* content
{:toc}

##### Abstract
Object counting is an important task in computer vision due to its growing demand in applications such as surveillance, traffic monitoring, and counting everyday objects. State-of-the-art methods use regression-based optimization where they explicitly learn to count the objects of interest. These often perform better than detection-based methods that need to learn the more difficult task of predicting the location, size, and shape of each object. However, we propose a detection-based method that does not need to estimate the size and shape of the objects and that outperforms regression-based methods. Our contributions are three-fold: (1) we propose a novel loss function that encourages the network to output a single blob per object instance using point-level annotations only; (2) we design two methods for splitting large predicted blobs between object instances; and (3) we show that our method achieves new state-of-the-art results on several challenging datasets including the Pascal VOC and the Penguins dataset. Our method even outperforms those that use stronger supervision such as depth features, multi-point annotations, and bounding-box labels.

##### Abstract (translated by Google)
对象计数是计算机视觉中的一项重要任务，因为它在监视，交通监控和计算日常物品等应用中的需求不断增长。最先进的方法使用基于回归的优化，他们明确地学习计算感兴趣的对象。这些通常比基于检测的方法表现更好，这些方法需要学习预测每个对象的位置，大小和形状的更困难的任务。然而，我们提出了一种基于检测的方法，该方法不需要估计对象的大小和形状，并且优于基于回归的方法。我们的贡献是三方面的：（1）我们提出了一种新的损失函数，它鼓励网络仅使用点级注释为每个对象实例输出单个blob; （2）我们设计了两种在对象实例之间拆分大预测blob的方法; （3）我们证明了我们的方法在几个具有挑战性的数据集上实现了最新的最新结果，包括Pascal VOC和Penguins数据集。我们的方法甚至优于那些使用更强大监督的方法，例如深度特征，多点注释和边界框标签。

##### URL
[http://arxiv.org/abs/1807.09856](http://arxiv.org/abs/1807.09856)

##### PDF
[http://arxiv.org/pdf/1807.09856](http://arxiv.org/pdf/1807.09856)

