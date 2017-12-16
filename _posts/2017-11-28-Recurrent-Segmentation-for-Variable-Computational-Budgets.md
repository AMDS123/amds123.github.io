---
layout: post
title: "Recurrent Segmentation for Variable Computational Budgets"
date: 2017-11-28 06:55:19
categories: arXiv_CV
tags: arXiv_CV Segmentation RNN Prediction
author: Lane McIntosh, David Sussillo, Niru Maheswaranathan, Jonathon Shlens
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art systems for semantic image segmentation utilize feed-forward pipelines with fixed computational costs. Building an image segmentation system that works across a range of computational budgets is challenging and time-intensive as new architectures must be designed and trained for every computational setting. To address this problem we develop a recurrent neural network that successively improves prediction quality with each iteration. Importantly, the RNN may be employed across a range of computational budgets by merely running the model for varying numbers of iterations. The RNN achieves results comparable to state-of-the-art systems in image segmentation on PASCAL VOC 2012 and Cityscapes segmentation datasets, however the RNN performs this task with a fraction of the computational budget. Finally, we demonstrate how one may exploit the properties of the RNN to efficiently perform video segmentation with half the computational cost of a comparable, state-of-the-art image segmentation method.

##### Abstract (translated by Google)
最先进的语义图像分割系统利用具有固定计算成本的前馈流水线。建立一个跨越一系列计算预算工作的图像分割系统是具有挑战性和时间密集性的，因为必须为每个计算设置设计和训练新的体系结构。为了解决这个问题，我们开发了一个循环神经网络，在每次迭代中都能够连续提高预测质量。重要的是，RNN可以在一定范围的计算预算中使用，只需运行模型进行不同次数的迭代。 RNN在PASCAL VOC 2012和Cityscapes分割数据集的图像分割中获得了与最先进的系统相媲美的结果，然而RNN只用计算预算的一小部分来执行此任务。最后，我们演示如何利用RNN的性质来有效地执行视频分割，其中一半的计算成本是可比较的，最先进的图像分割方法。

##### URL
[https://arxiv.org/abs/1711.10151](https://arxiv.org/abs/1711.10151)

##### PDF
[https://arxiv.org/pdf/1711.10151](https://arxiv.org/pdf/1711.10151)

