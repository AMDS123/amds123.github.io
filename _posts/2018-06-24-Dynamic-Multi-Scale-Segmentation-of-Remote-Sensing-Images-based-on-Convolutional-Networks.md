---
layout: post
title: "Dynamic Multi-Scale Segmentation of Remote Sensing Images based on Convolutional Networks"
date: 2018-06-24 15:37:22
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification
author: Keiller Nogueira, Mauro Dalla Mura, Jocelyn Chanussot, William Robson Schwartz, Jefersson A. dos Santos
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation requires methods capable of learning high-level features while dealing with large volume of data. Towards such goal, Convolutional Networks can learn specific and adaptable features based on the data. However, these networks are not capable of processing a whole remote sensing image, given its huge size. To overcome such limitation, the image is processed using fixed size patches. The definition of the input patch size is usually performed empirically (evaluating several sizes) or imposed (by network constraint). Both strategies suffer from drawbacks and could not lead to the best patch size. To alleviate this problem, several works exploited multi-scale information by combining networks or layers. This process increases the number of parameters resulting in a more difficult model to train. In this work, we propose a novel technique to perform semantic segmentation of remote sensing images that exploits a multi-scale paradigm without increasing the number of parameters while defining, in training time, the best patch size. The main idea is to train a dilated network with distinct patch sizes, allowing it to capture multi-scale characteristics from heterogeneous contexts. While processing these varying patches, the network provides a score for each patch size, helping in the definition of the best size for the current scenario. A systematic evaluation of the proposed algorithm is conducted using four high-resolution remote sensing datasets with very distinct properties. Our results show that the proposed algorithm provides improvements in pixelwise classification accuracy when compared to state-of-the-art methods.

##### Abstract (translated by Google)
语义分割需要能够在处理大量数据时学习高级特征的方法。为了达到这样的目标，卷积网络可以根据数据学习特定的和可适应的特征。然而，鉴于其庞大的尺寸，这些网络无法处理整个遥感图像。为了克服这种限制，图像使用固定大小的补丁进行处理。输入补丁大小的定义通常是凭经验进行的（评估多个大小）或施加的（通过网络约束）。两种策略都有缺点，并且不能达到最佳的补丁大小。为了缓解这个问题，一些作品通过结合网络或图层来利用多尺度信息。该过程增加了参数的数量，导致更难以训练的模型。在这项工作中，我们提出了一种新颖的技术来执行遥感图像的语义分割，该技术利用多尺度范例而不增加参数的数量，同时在训练时间中定义最佳的分块大小。主要想法是训练具有不同补丁大小的扩展网络，使其能够从异构环境中捕捉多尺度特征。在处理这些不同的修补程序时，网络为每个修补程序大小提供评分，有助于为当前情况定义最佳大小。对所提出算法的系统评估是使用具有非常明显特性的四个高分辨率遥感数据集进行的。我们的结果显示，与最先进的方法相比，所提出的算法在像素级分类准确度方面提供了改进。

##### URL
[http://arxiv.org/abs/1804.04020](http://arxiv.org/abs/1804.04020)

##### PDF
[http://arxiv.org/pdf/1804.04020](http://arxiv.org/pdf/1804.04020)

