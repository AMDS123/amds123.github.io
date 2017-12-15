---
layout: post
title: "Data Augmentation in Emotion Classification Using Generative Adversarial Networks"
date: 2017-12-14 06:27:58
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification
author: Xinyue Zhu, Yifan Liu, Zengchang Qin, Jiahong Li
mathjax: true
---

* content
{:toc}

##### Abstract
It is a difficult task to classify images with multiple class labels using only a small number of labeled examples, especially when the label (class) distribution is imbalanced. Emotion classification is such an example of imbalanced label distribution, because some classes of emotions like \emph{disgusted} are relatively rare comparing to other labels like {\it happy or sad}. In this paper, we propose a data augmentation method using generative adversarial networks (GAN). It can complement and complete the data manifold and find better margins between neighboring classes. Specifically, we design a framework with a CNN model as the classifier and a cycle-consistent adversarial networks (CycleGAN) as the generator. In order to avoid gradient vanishing problem, we employ the least-squared loss as adversarial loss. We also propose several evaluation methods on three benchmark datasets to validate GAN's performance. Empirical results show that we can obtain 5%~10% increase in the classification accuracy after employing the GAN-based data augmentation techniques.

##### Abstract (translated by Google)
使用多个标签的例子来分类具有多个类别标签的图像是困难的，特别是当标签（类别）分布不平衡时。情感分类就是这样一个不平衡的标签分布的例子，因为像\ emph {disgusted}这样的一类情感相对于其他标签比较少见，比如{\ it happy \ sad}。在本文中，我们提出了一种使用生成对抗网络（GAN）的数据增强方法。它可以补充和完成数据流形，并找到相邻类之间更好的利润率。具体来说，我们设计了一个框架，CNN模型作为分类器和一个循环一致的对抗网络（CycleGAN）作为生成器。为了避免梯度消失问题，我们采用最小平方损失作为对抗损失。我们还对三个基准数据集提出了几种评估方法来验证GAN的性能。实证结果表明，采用基于GAN的数据增强技术后，分类精度可以提高5％〜10％。

##### URL
[http://arxiv.org/abs/1711.00648](http://arxiv.org/abs/1711.00648)

##### PDF
[http://arxiv.org/pdf/1711.00648](http://arxiv.org/pdf/1711.00648)

