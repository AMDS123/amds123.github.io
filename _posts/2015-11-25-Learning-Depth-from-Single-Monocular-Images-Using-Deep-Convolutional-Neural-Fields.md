---
layout: post
title: "Learning Depth from Single Monocular Images Using Deep Convolutional Neural Fields"
date: 2015-11-25 00:03:31
categories: arXiv_CV
tags: arXiv_CV CNN
author: Fayao Liu, Chunhua Shen, Guosheng Lin, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
In this article, we tackle the problem of depth estimation from single monocular images. Compared with depth estimation using multiple images such as stereo depth perception, depth from monocular images is much more challenging. Prior work typically focuses on exploiting geometric priors or additional sources of information, most using hand-crafted features. Recently, there is mounting evidence that features from deep convolutional neural networks (CNN) set new records for various vision applications. On the other hand, considering the continuous characteristic of the depth values, depth estimations can be naturally formulated as a continuous conditional random field (CRF) learning problem. Therefore, here we present a deep convolutional neural field model for estimating depths from single monocular images, aiming to jointly explore the capacity of deep CNN and continuous CRF. In particular, we propose a deep structured learning scheme which learns the unary and pairwise potentials of continuous CRF in a unified deep CNN framework. We then further propose an equally effective model based on fully convolutional networks and a novel superpixel pooling method, which is $\sim 10$ times faster, to speedup the patch-wise convolutions in the deep model. With this more efficient model, we are able to design deeper networks to pursue better performance. Experiments on both indoor and outdoor scene datasets demonstrate that the proposed method outperforms state-of-the-art depth estimation approaches.

##### Abstract (translated by Google)
在这篇文章中，我们解决单眼图像深度估计的问题。与使用诸如立体深度感知的多个图像的深度估计相比，单眼图像的深度更具挑战性。以前的工作通常侧重于利用几何先验或其他信息来源，大部分使用手工制作的特征。最近，越来越多的证据表明，来自深度卷积神经网络（CNN）的特征为各种视觉应用创造了新的记录。另一方面，考虑深度值的连续特性，深度估计可以自然地表示为连续条件随机场（CRF）学习问题。因此，本文提出了一种深度卷积神经网络模型来估计单个单目图像的深度，旨在共同探索深部CNN和连续CRF的能力。具体而言，我们提出了一个深入的学习方案，在一个统一的深度CNN框架下学习连续CRF的一元和二元的潜力。然后，我们进一步提出一个基于完全卷积网络和一种新的超像素池方法的同样有效的模型，这个模型的速度要快10倍，以加速深层模型中的面片卷积。有了这个更高效的模型，我们可以设计更深的网络来追求更好的性能。在室内和室外场景数据集上的实验表明，所提出的方法优于最新的深度估计方法。

##### URL
[https://arxiv.org/abs/1502.07411](https://arxiv.org/abs/1502.07411)

##### PDF
[https://arxiv.org/pdf/1502.07411](https://arxiv.org/pdf/1502.07411)

