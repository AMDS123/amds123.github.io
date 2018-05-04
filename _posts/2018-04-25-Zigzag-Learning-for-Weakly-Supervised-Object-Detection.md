---
layout: post
title: "Zigzag Learning for Weakly Supervised Object Detection"
date: 2018-04-25 10:26:57
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection Weakly_Supervised CNN Detection
author: Xiaopeng Zhang, Jiashi Feng, Hongkai Xiong, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses weakly supervised object detection with only image-level supervision at training stage. Previous approaches train detection models with entire images all at once, making the models prone to being trapped in sub-optimums due to the introduced false positive examples. Unlike them, we propose a zigzag learning strategy to simultaneously discover reliable object instances and prevent the model from overfitting initial seeds. Towards this goal, we first develop a criterion named mean Energy Accumulation Scores (mEAS) to automatically measure and rank localization difficulty of an image containing the target object, and accordingly learn the detector progressively by feeding examples with increasing difficulty. In this way, the model can be well prepared by training on easy examples for learning from more difficult ones and thus gain a stronger detection ability more efficiently. Furthermore, we introduce a novel masking regularization strategy over the high level convolutional feature maps to avoid overfitting initial samples. These two modules formulate a zigzag learning process, where progressive learning endeavors to discover reliable object instances, and masking regularization increases the difficulty of finding object instances properly. We achieve 47.6% mAP on PASCAL VOC 2007, surpassing the state-of-the-arts by a large margin.

##### Abstract (translated by Google)
本文针对训练阶段只有图像级监督的弱监督目标检测。以前的方法一次训练整个图像的检测模型，由于引入了假阳性例子，模型容易陷入次优。与他们不同，我们提出了一个曲折的学习策略，以同时发现可靠的对象实例并防止模型过度填充初始种子。为了实现这一目标，我们首先制定了一个名为平均能量积累分数（mEAS）的标准，用于自动测量和排列包含目标物体的图像的定位难度，并相应地通过增加难度来提供示例来逐步了解检测器。通过这种方式，可以通过训练简单的示例以从更困难的示例中学习，从而更好地获得更强的检测能力，从而为模型做好准备。此外，我们在高级卷积特征映射上引入了一种新的掩蔽正则化策略，以避免过度拟合初始样本。这两个模块制定了一个曲折的学习过程，逐步学习尝试发现可靠的对象实例，掩蔽正则化增加了正确查找对象实例的难度。我们在PASCAL VOC 2007中实现了47.6％的MAP，大幅超越了艺术级别。

##### URL
[https://arxiv.org/abs/1804.09466](https://arxiv.org/abs/1804.09466)

##### PDF
[https://arxiv.org/pdf/1804.09466](https://arxiv.org/pdf/1804.09466)

