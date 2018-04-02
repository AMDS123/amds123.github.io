---
layout: post
title: "Parallel Grid Pooling for Data Augmentation"
date: 2018-03-30 07:25:00
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Akito Takeki, Daiki Ikami, Go Irie, Kiyoharu Aizawa
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural network (CNN) architectures utilize downsampling layers, which restrict the subsequent layers to learn spatially invariant features while reducing computational costs. However, such a downsampling operation makes it impossible to use the full spectrum of input features. Motivated by this observation, we propose a novel layer called parallel grid pooling (PGP) which is applicable to various CNN models. PGP performs downsampling without discarding any intermediate feature. It works as data augmentation and is complementary to commonly used data augmentation techniques. Furthermore, we demonstrate that a dilated convolution can naturally be represented using PGP operations, which suggests that the dilated convolution can also be regarded as a type of data augmentation technique. Experimental results based on popular image classification benchmarks demonstrate the effectiveness of the proposed method. Code is available at: this https URL

##### Abstract (translated by Google)
卷积神经网络（CNN）架构利用下采样层，这限制了后续层学习空间不变特征，同时降低计算成本。但是，这样的下采样操作使得不可能使用全频谱的输入特征。受此观察的启发，我们提出了一种新的称为并行网格池（PGP）的层，它适用于各种CNN模型。 PGP执行下采样而不丢弃任何中间特征。它用作数据增强，并且是常用数据增强技术的补充。此外，我们证明了扩张卷积可以自然地用PGP运算来表示，这表明扩张卷积也可以被认为是一种数据增强技术。基于流行的图像分类基准的实验结果证明了所提出方法的有效性。代码位于：https网址

##### URL
[https://arxiv.org/abs/1803.11370](https://arxiv.org/abs/1803.11370)

##### PDF
[https://arxiv.org/pdf/1803.11370](https://arxiv.org/pdf/1803.11370)

