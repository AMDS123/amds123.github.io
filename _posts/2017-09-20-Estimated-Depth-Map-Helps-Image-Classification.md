---
layout: post
title: "Estimated Depth Map Helps Image Classification"
date: 2017-09-20 20:39:47
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Classification Transfer_Learning Classification
author: Yihui He
mathjax: true
---

* content
{:toc}

##### Abstract
We consider image classification with estimated depth. This problem falls into the domain of transfer learning, since we are using a model trained on a set of depth images to generate depth maps (additional features) for use in another classification problem using another disjoint set of images. It's challenging as no direct depth information is provided. Though depth estimation has been well studied, none have attempted to aid image classification with estimated depth. Therefore, we present a way of transferring domain knowledge on depth estimation to a separate image classification task over a disjoint set of train, and test data. We build a RGBD dataset based on RGB dataset and do image classification on it. Then evaluation the performance of neural networks on the RGBD dataset compared to the RGB dataset. From our experiments, the benefit is significant with shallow and deep networks. It improves ResNet-20 by 0.55% and ResNet-56 by 0.53%. Our code and dataset are available publicly.

##### Abstract (translated by Google)
我们考虑估计深度的图像分类。这个问题属于转移学习的领域，因为我们使用一个训练在一组深度图像上的模型来生成深度图（附加特征），以用于使用另一个不相交的图像组的另一个分类问题。由于没有提供直接的深度信息，因此具有挑战性。虽然深度估计已经得到很好的研究，但没有人试图帮助估计深度的图像分类。因此，我们提出一种将深度估计的领域知识转移到不相交的一组列车上的单独图像分类任务和测试数据的方法。我们建立一个基于RGB数据集的RGBD数据集并对其进行图像分类。然后评估与RGB数据集相比，RGBD数据集上的神经网络的性能。从我们的实验来看，网络浅而深的好处是显着的。它将ResNet-20提高了0.55％，ResNet-56提高了0.53％。我们的代码和数据集可以公开获得。

##### URL
[https://arxiv.org/abs/1709.07077](https://arxiv.org/abs/1709.07077)

##### PDF
[https://arxiv.org/pdf/1709.07077](https://arxiv.org/pdf/1709.07077)

