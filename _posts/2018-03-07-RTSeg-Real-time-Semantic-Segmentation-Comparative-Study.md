---
layout: post
title: "RTSeg: Real-time Semantic Segmentation Comparative Study"
date: 2018-03-07 16:49:48
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Semantic_Segmentation
author: Mennatullah Siam, Mostafa Gamal, Moemen Abdel-Razek, Senthil Yogamani, Martin Jagersand
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation benefits robotics related applications especially autonomous driving. Most of the research on semantic segmentation is only on increasing the accuracy of segmentation models with little attention to computationally efficient solutions. The few work conducted in this direction does not provide principled methods to evaluate the different design choices for segmentation. In this paper, we address this gap by presenting a real-time semantic segmentation benchmarking framework with a decoupled design for feature extraction and decoding methods. The framework is comprised of different network architectures for feature extraction such as VGG16, Resnet18, MobileNet, and ShuffleNet. It is also comprised of multiple meta-architectures for segmentation that define the decoding methodology. These include SkipNet, UNet, and Dilation Frontend. Experimental results are presented on the Cityscapes dataset for urban scenes. The modular design allows novel architectures to emerge, that lead to 143x GFLOPs reduction in comparison to SegNet. This benchmarking framework is publicly available at "https://github.com/MSiam/TFSegmentation".

##### Abstract (translated by Google)
语义分割有利于机器人相关的应用，尤其是自动驾驶。大多数关于语义分割的研究只是提高分割模型的准确性，而很少关注计算有效的解决方案。在这方面进行的少量工作并没有提供评估分割不同设计选择的原则性方法。在本文中，我们通过提出一种实时语义分割基准测试框架来解决这个差距，该基准框架具有用于特征提取和解码方法的解耦设计。该框架由用于特征提取的不同网络体系结构组成，如VGG16，Resnet18，MobileNet和ShuffleNet。它还包含多个用于定义解码方法的分段元结构。这些包括SkipNet，UNet和Dilation Frontend。城市景观数据集中提供了实验结果。模块化设计使得新颖的架构得以实现，与SegNet相比，可减少143x GFLOPs。这个基准测试框架公开发布在“https://github.com/MSiam/TFSegmentation”。

##### URL
[http://arxiv.org/abs/1803.02758](http://arxiv.org/abs/1803.02758)

##### PDF
[http://arxiv.org/pdf/1803.02758](http://arxiv.org/pdf/1803.02758)

