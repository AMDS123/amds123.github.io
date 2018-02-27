---
layout: post
title: "Deep Learning is Robust to Massive Label Noise"
date: 2018-02-26 16:51:57
categories: arXiv_AI
tags: arXiv_AI Image_Classification Classification Deep_Learning
author: David Rolnick, Andreas Veit, Serge Belongie, Nir Shavit
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks trained on large supervised datasets have led to impressive results in image classification and other tasks. However, well-annotated datasets can be time-consuming and expensive to collect, lending increased interest to larger but noisy datasets that are more easily obtained. In this paper, we show that deep neural networks are capable of generalizing from training data for which true labels are massively outnumbered by incorrect labels. We demonstrate remarkably high test performance after training on corrupted data from MNIST, CIFAR, and ImageNet. For example, on MNIST we obtain test accuracy above 90 percent even after each clean training example has been diluted with 100 randomly-labeled examples. Such behavior holds across multiple patterns of label noise, even when erroneous labels are biased towards confusing classes. We show that training in this regime requires a significant but manageable increase in dataset size that is related to the factor by which correct labels have been diluted. Finally, we provide an analysis of our results that shows how increasing noise decreases the effective batch size.

##### Abstract (translated by Google)
在大型监督数据集上训练的深度神经网络已经在图像分类和其他任务中产生了令人印象深刻的结果。但是，注释良好的数据集可能非常耗时且昂贵，因此对更容易获得的较大但噪音较大的数据集的兴趣增加。在本文中，我们表明深度神经网络能够从训练数据中推广出来，因为真正的标签被不正确的标签大量超过数量。在对来自MNIST，CIFAR和ImageNet的损坏数据进行训练之后，我们表现出非常高的测试性能。例如，在MNIST上，即使每个干净的训练实例已用100个随机标记的例子稀释后，我们的测试精度仍高于90％。这种行为可以保持多种标签噪声模式，即使错误的标签偏向混淆的类时也是如此。我们表明，在这个制度下的培训需要一个显着但可管理的数据集大小的增加，这与正确标签被稀释的因素有关。最后，我们对我们的结果进行分析，显示增加的噪音如何降低有效批量。

##### URL
[http://arxiv.org/abs/1705.10694](http://arxiv.org/abs/1705.10694)

##### PDF
[http://arxiv.org/pdf/1705.10694](http://arxiv.org/pdf/1705.10694)

