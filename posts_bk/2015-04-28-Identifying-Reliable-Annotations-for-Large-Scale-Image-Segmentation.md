---
layout: post
title: "Identifying Reliable Annotations for Large Scale Image Segmentation"
date: 2015-04-28 13:19:21
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Alexander Kolesnikov, Christoph H. Lampert
mathjax: true
---

* content
{:toc}

##### Abstract
Challenging computer vision tasks, in particular semantic image segmentation, require large training sets of annotated images. While obtaining the actual images is often unproblematic, creating the necessary annotation is a tedious and costly process. Therefore, one often has to work with unreliable annotation sources, such as Amazon Mechanical Turk or (semi-)automatic algorithmic techniques. In this work, we present a Gaussian process (GP) based technique for simultaneously identifying which images of a training set have unreliable annotation and learning a segmentation model in which the negative effect of these images is suppressed. Alternatively, the model can also just be used to identify the most reliably annotated images from the training set, which can then be used for training any other segmentation method. By relying on "deep features" in combination with a linear covariance function, our GP can be learned and its hyperparameter determined efficiently using only matrix operations and gradient-based optimization. This makes our method scalable even to large datasets with several million training instances.

##### Abstract (translated by Google)
具有挑战性的计算机视觉任务，特别是语义图像分割，需要大量的注释图像的训练集。虽然获取实际的图像往往是没有问题的，但创建必要的注释是一个繁琐而昂贵的过程。因此，经常需要使用不可靠的注释源，例如Amazon Mechanical Turk或（半）自动算法技术。在这项工作中，我们提出一种基于高斯过程（GP）的技术，用于同时识别训练集的哪些图像具有不可靠的注释，并学习抑制这些图像的负面影响的分割模型。另外，该模型也可以用来从训练集中识别最可靠的注释图像，然后可以用它来训练任何其他分割方法。通过将“深度特征”与线性协方差函数相结合，我们的GP可以被学习，并且仅使用矩阵运算和基于梯度的优化来有效地确定其超参数。这使得我们的方法可以扩展到数百万个训练实例的大型数据集。

##### URL
[https://arxiv.org/abs/1504.07460](https://arxiv.org/abs/1504.07460)

##### PDF
[https://arxiv.org/pdf/1504.07460](https://arxiv.org/pdf/1504.07460)

