---
layout: post
title: "3D Shape Segmentation via Shape Fully Convolutional Networks"
date: 2017-07-29 08:39:05
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Pengyu Wang, Yuan Gan, Panpan Shui, Fenggen Yu, Yan Zhang, Songle Chen, Zhengxing Sun
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel fully convolutional network architecture for shapes, denoted by Shape Fully Convolutional Networks (SFCN). 3D shapes are represented as graph structures in the SFCN architecture, based on novel graph convolution and pooling operations, which are similar to convolution and pooling operations used on images. Meanwhile, to build our SFCN architecture in the original image segmentation fully convolutional network (FCN) architecture, we also design and implement a generating operation} with bridging function. This ensures that the convolution and pooling operation we have designed can be successfully applied in the original FCN architecture. In this paper, we also present a new shape segmentation approach based on SFCN. Furthermore, we allow more general and challenging input, such as mixed datasets of different categories of shapes} which can prove the ability of our generalisation. In our approach, SFCNs are trained triangles-to-triangles by using three low-level geometric features as input. Finally, the feature voting-based multi-label graph cuts is adopted to optimise the segmentation results obtained by SFCN prediction. The experiment results show that our method can effectively learn and predict mixed shape datasets of either similar or different characteristics, and achieve excellent segmentation results.

##### Abstract (translated by Google)
我们提出了一种新的形状完全卷积网络体系结构，由形状完全卷积网络（SFCN）表示。在SFCN体系结构中，3D形状被表示为图形结构，基于新型图形卷积和池化操作，这与图像上使用的卷积和池化操作类似。同时，为了在原有的图像分割全卷积网络（FCN）体系结构中构建SFCN体系结构，我们还设计并实现了具有桥接功能的生成操作。这确保了我们设计的卷积和合并操作可以在原有的FCN架构中成功应用。在本文中，我们还提出了一种基于SFCN的新的形状分割方法。此外，我们允许更多的一般和具有挑战性的输入，如不同类型的混合数据集}这可以证明我们的概括能力。在我们的方法中，SFCNs通过使用三个低级几何特征作为输入来训练三角形到三角形。最后，采用基于特征投票的多标签图裁剪来优化SFCN预测得到的分割结果。实验结果表明，该方法可以有效地学习和预测相似或不同特征的混合形状数据集，实现优异的分割结果。

##### URL
[https://arxiv.org/abs/1702.08675](https://arxiv.org/abs/1702.08675)

##### PDF
[https://arxiv.org/pdf/1702.08675](https://arxiv.org/pdf/1702.08675)

