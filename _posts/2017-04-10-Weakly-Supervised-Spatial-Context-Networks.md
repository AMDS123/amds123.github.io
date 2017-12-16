---
layout: post
title: "Weakly-Supervised Spatial Context Networks"
date: 2017-04-10 18:15:34
categories: arXiv_CV
tags: arXiv_CV Detection
author: Zuxuan Wu, Larry S. Davis, Leonid Sigal
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the power of spatial context as a self-supervisory signal for learning visual representations. In particular, we propose spatial context networks that learn to predict a representation of one image patch from another image patch, within the same image, conditioned on their real-valued relative spatial offset. Unlike auto-encoders, that aim to encode and reconstruct original image patches, our network aims to encode and reconstruct intermediate representations of the spatially offset patches. As such, the network learns a spatially conditioned contextual representation. By testing performance with various patch selection mechanisms we show that focusing on object-centric patches is important, and that using object proposal as a patch selection mechanism leads to the highest improvement in performance. Further, unlike auto-encoders, context encoders [21], or other forms of unsupervised feature learning, we illustrate that contextual supervision (with pre-trained model initialization) can improve on existing pre-trained model performance. We build our spatial context networks on top of standard VGG_19 and CNN_M architectures and, among other things, show that we can achieve improvements (with no additional explicit supervision) over the original ImageNet pre-trained VGG_19 and CNN_M models in object categorization and detection on VOC2007.

##### Abstract (translated by Google)
我们探索空间情境作为学习视觉表现的自我监督信号的力量。具体而言，我们提出了空间上下文网络，学习预测来自另一图像片的一个图像片的表示，在相同的图像内，以它们的实值相对空间偏移为条件。与自动编码器不同，它旨在对原始图像块进行编码和重构，我们的网络旨在编码和重建空间偏移块的中间表示。如此，网络学习空间条件化的上下文表示。通过使用各种补丁选择机制来测试性能，我们表明，重点关注以对象为中心的补丁非常重要，而使用对象提议作为补丁选择机制可以提高性能。此外，与自动编码器，上下文编码器[21]或其他形式的无监督特征学习不同，我们说明，上下文监督（带有预先训练的模型初始化）可以改进现有的预先训练的模型性能。我们在标准VGG_19和CNN_M体系结构的基础上构建了我们的空间上下文网络，其中包括对原始ImageNet预先训练的VGG_19和CNN_M模型在对象分类和检测上的改进（无需额外的明确监督） VOC2007。

##### URL
[https://arxiv.org/abs/1704.02998](https://arxiv.org/abs/1704.02998)

##### PDF
[https://arxiv.org/pdf/1704.02998](https://arxiv.org/pdf/1704.02998)

