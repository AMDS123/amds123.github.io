---
layout: post
title: "Fully Point-wise Convolutional Neural Network for Modeling Statistical Regularities in Natural Images"
date: 2018-01-19 05:32:33
categories: arXiv_CV
tags: arXiv_CV Image_Enhancement CNN
author: Jing Zhang, Yang Cao, Yang Wang, Zheng-Jun Zha, Chenglin Wen, Chang Wen Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Modeling statistical regularities is the problem of representing the pixel distributions in natural images, and usually applied to solve the ill-posed image processing problems. In this paper, we present an extremely efficient CNN architecture for modeling statistical regularities. Our method is based on the observation that, by random sampling the pixels in natural images, we can obtain a set of pixel ensembles in which the pixel value is independent identically distributed. This leads to the idea of using 1*1 (point-wise) convolution kernel instead of k*k convolution kernel to learn the feature representation efficiently. Accordingly, we design a novel architecture with fully point-wise convolutions to greatly reduce the model complexity while maintaining the representation ability. Experiments on three applications: color constancy, image dehazing and underwater image enhancement demonstrate the superior performance of our proposed network over the existing architectures, i.e., using 1/10-1/100 network parameters and computational cost over the state-of-the-art networks while achieving comparable accuracy. Codes and models will be made publicly available.

##### Abstract (translated by Google)
统计规律性的建模是表示自然图像中像素分布的问题，通常用于解决不适定的图像处理问题。在本文中，我们提出了一个非常有效的CNN架构来建模统计规律。我们的方法是基于以下观察：通过对自然图像中的像素进行随机采样，可以获得一组像素集合，其中像素值是独立同分布的。这导致了使用1 * 1（逐点）卷积核而不是k * k卷积核以有效地学习特征表示的想法。相应地，我们设计了一种新的完全按点卷积的体系结构，在保持表示能力的同时大大降低了模型的复杂度。在三个应用上的实验：颜色恒定性，图像去雾和水下图像增强证明了我们提出的网络优于现有架构的优越性能，即，使用1 / 10-1 / 100网络参数和计算代价，艺术网络同时达到可比的准确性代码和模型将公开发布。

##### URL
[http://arxiv.org/abs/1801.06302](http://arxiv.org/abs/1801.06302)

##### PDF
[http://arxiv.org/pdf/1801.06302](http://arxiv.org/pdf/1801.06302)

