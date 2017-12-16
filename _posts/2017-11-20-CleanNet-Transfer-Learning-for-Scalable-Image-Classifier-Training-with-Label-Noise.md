---
layout: post
title: "CleanNet: Transfer Learning for Scalable Image Classifier Training with Label Noise"
date: 2017-11-20 03:50:53
categories: arXiv_CV
tags: arXiv_CV Knowledge Weakly_Supervised Embedding CNN Image_Classification Transfer_Learning Classification Detection
author: Kuang-Huei Lee, Xiaodong He, Lei Zhang, Linjun Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the problem of learning image classification models with label noise. Existing approaches depending on human supervision are generally not scalable as manually identifying correct or incorrect labels is timeconsuming, whereas approaches not relying on human supervision are scalable but less effective. To reduce the amount of human supervision for label noise cleaning, we introduce CleanNet, a joint neural embedding network, which only requires a fraction of the classes being manually verified to provide the knowledge of label noise that can be transferred to other classes. We further integrate CleanNet and conventional convolutional neural network classifier into one framework for image classification learning. We demonstrate the effectiveness of the proposed algorithm on both of the label noise detection task and the image classification on noisy data task on several large-scale datasets. Experimental results show that CleanNet can reduce label noise detection error rate on held-out classes where no human supervision available by 41.5% compared to current weakly supervised methods. It also achieves 47% of the performance gain of verifying all images with only 3.2% images verified on an image classification task.

##### Abstract (translated by Google)
在本文中，我们研究了带有标签噪声的学习图像分类模型的问题。取决于人类监督的现有方法通常不可扩展，因为人工识别正确或不正确的标签是耗时的，而不依赖于人员监督的方法是可扩展的，但效果较差。为了减少标签噪声清理的人力监管，我们引入了CleanNet（联合神经嵌入网络），它只需要手动验证一小部分类别，以提供可转移到其他类别的标签噪声的知识。我们进一步将CleanNet和传统的卷积神经网络分类器集成到一个图像分类学习框架中。我们证明了所提出的算法在标签噪声检测任务和在几个大规模数据集的噪声数据任务上的图像分类的有效性。实验结果表明，与目前的弱监督方法相比，CleanNet可以降低外出班级标签噪声检测的错误率，没有人工监控可达41.5％。在图像分类任务中，只有3.2％的图像被验证，同样能够达到验证所有图像的性能增益的47％。

##### URL
[https://arxiv.org/abs/1711.07131](https://arxiv.org/abs/1711.07131)

##### PDF
[https://arxiv.org/pdf/1711.07131](https://arxiv.org/pdf/1711.07131)

