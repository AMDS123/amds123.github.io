---
layout: post
title: "Rich feature hierarchies for accurate object detection and semantic segmentation"
date: 2014-10-22 17:23:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Detection
author: Ross Girshick, Jeff Donahue, Trevor Darrell, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection performance, as measured on the canonical PASCAL VOC dataset, has plateaued in the last few years. The best-performing methods are complex ensemble systems that typically combine multiple low-level image features with high-level context. In this paper, we propose a simple and scalable detection algorithm that improves mean average precision (mAP) by more than 30% relative to the previous best result on VOC 2012---achieving a mAP of 53.3%. Our approach combines two key insights: (1) one can apply high-capacity convolutional neural networks (CNNs) to bottom-up region proposals in order to localize and segment objects and (2) when labeled training data is scarce, supervised pre-training for an auxiliary task, followed by domain-specific fine-tuning, yields a significant performance boost. Since we combine region proposals with CNNs, we call our method R-CNN: Regions with CNN features. We also compare R-CNN to OverFeat, a recently proposed sliding-window detector based on a similar CNN architecture. We find that R-CNN outperforms OverFeat by a large margin on the 200-class ILSVRC2013 detection dataset. Source code for the complete system is available at this http URL

##### Abstract (translated by Google)
在规范的PASCAL VOC数据集上测量的对象检测性能在过去几年中一直处于稳定状态。性能最好的方法是复合系统，通常将多个低级图像特征与高级上下文组合在一起。在本文中，我们提出了一种简单可扩展的检测算法，相对于2012年前的最佳结果，平均精度（mAP）提高了30％以上 - 达到53.3％的mAP。我们的方法结合了两个关键的见解：（1）可以将高容量卷积神经网络（CNN）应用于自下而上的地区建议，以便对对象进行本地化和分段;（2）当标记的训练数据稀缺时，有监督的预训练对于辅助任务，接下来是特定领域的微调，产生显着的性能提升。由于我们将区域提案与CNN结合在一起，我们将其称为我们的方法R-CNN：具有CNN特征的区域。我们还将R-CNN与最近提出的基于类似CNN架构的滑动窗口检测器OverFeat进行比较。我们发现R-CNN在200级ILSVRC2013检测数据集上的性能优于OverFeat。完整系统的源代码可以在这个http URL中找到

##### URL
[https://arxiv.org/abs/1311.2524](https://arxiv.org/abs/1311.2524)

