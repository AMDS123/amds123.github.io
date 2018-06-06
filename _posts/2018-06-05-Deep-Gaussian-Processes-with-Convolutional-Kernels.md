---
layout: post
title: "Deep Gaussian Processes with Convolutional Kernels"
date: 2018-06-05 12:41:14
categories: arXiv_AI
tags: arXiv_AI CNN Image_Classification Classification Deep_Learning
author: Vinayak Kumar, Vaibhav Singh, P. K. Srijith, Andreas Damianou
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Gaussian processes (DGPs) provide a Bayesian non-parametric alternative to standard parametric deep learning models. A DGP is formed by stacking multiple GPs resulting in a well-regularized composition of functions. The Bayesian framework that equips the model with attractive properties, such as implicit capacity control and predictive uncertainty, makes it at the same time challenging to combine with a convolutional structure. This has hindered the application of DGPs in computer vision tasks, an area where deep parametric models (i.e. CNNs) have made breakthroughs. Standard kernels used in DGPs such as radial basis functions (RBFs) are insufficient for handling pixel variability in raw images. In this paper, we build on the recent convolutional GP to develop Convolutional DGP (CDGP) models which effectively capture image level features through the use of convolution kernels, therefore opening up the way for applying DGPs to computer vision tasks. Our model learns local spatial influence and outperforms strong GP based baselines on multi-class image classification. We also consider various constructions of convolution kernel over the image patches, analyze the computational trade-offs and provide an efficient framework for convolutional DGP models. The experimental results on image data such as MNIST, rectangles-image, CIFAR10 and Caltech101 demonstrate the effectiveness of the proposed approaches.

##### Abstract (translated by Google)
深高斯过程（DGP）提供了标准参数深度学习模型的贝叶斯非参数替代方案。 DGP是通过堆叠多个GP形成的，从而导致功能的正规化组合。使模型具有吸引力特性的贝叶斯框架（如隐式容量控制和预测不确定性）使得与卷积结构相结合的同时具有挑战性。这阻碍了DGP在计算机视觉任务中的应用，这是深层参数模型（即CNN）取得突破的领域。在DGP中使用的标准内核如径向基函数（RBF）不足以处理原始图像中的像素变化。在本文中，我们基于最近的卷积GP开发了卷积DGP（CDGP）模型，该模型通过使用卷积核有效地捕获图像级特征，因此为将DGP应用于计算机视觉任务开辟了道路。我们的模型学习局部空间影响并且胜过基于多级图像分类的基于GP的强基线。我们还考虑了卷积核在图像块上的各种构造，分析计算折衷并为卷积DGP模型提供了一个有效的框架。图像数据如MNIST，矩形图像，CIFAR10和Caltech101的实验结果证明了所提出方法的有效性。

##### URL
[http://arxiv.org/abs/1806.01655](http://arxiv.org/abs/1806.01655)

##### PDF
[http://arxiv.org/pdf/1806.01655](http://arxiv.org/pdf/1806.01655)

