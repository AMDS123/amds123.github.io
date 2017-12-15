---
layout: post
title: "Deep Joint Task Learning for Generic Object Extraction"
date: 2015-02-03 05:35:09
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation CNN Optimization
author: Xiaolong Wang, Liliang Zhang, Liang Lin, Zhujin Liang, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates how to extract objects-of-interest without relying on hand-craft features and sliding windows approaches, that aims to jointly solve two sub-tasks: (i) rapidly localizing salient objects from images, and (ii) accurately segmenting the objects based on the localizations. We present a general joint task learning framework, in which each task (either object localization or object segmentation) is tackled via a multi-layer convolutional neural network, and the two networks work collaboratively to boost performance. In particular, we propose to incorporate latent variables bridging the two networks in a joint optimization manner. The first network directly predicts the positions and scales of salient objects from raw images, and the latent variables adjust the object localizations to feed the second network that produces pixelwise object masks. An EM-type method is presented for the optimization, iterating with two steps: (i) by using the two networks, it estimates the latent variables by employing an MCMC-based sampling method; (ii) it optimizes the parameters of the two networks unitedly via back propagation, with the fixed latent variables. Extensive experiments suggest that our framework significantly outperforms other state-of-the-art approaches in both accuracy and efficiency (e.g. 1000 times faster than competing approaches).

##### Abstract (translated by Google)
本文研究如何提取兴趣对象而不依靠手工特征和滑动窗口的方法，旨在联合解决两个子任务：（1）快速定位显着的对象的图像，和（2）准确地分割基于本地化的对象。我们提出了一个通用的联合任务学习框架，其中通过多层卷积神经网络来处理每个任务（对象本地化或对象分割），并且这两个网络协同工作以提高性能。具体而言，我们建议将联结两个网络的潜在变量以联合优化方式结合。第一个网络从原始图像直接预测显着物体的位置和尺度，并且潜在变量调整物体定位以馈送产生像素对象掩模的第二网络。提出了一种EM型方法进行优化，迭代分两步进行：（1）利用两种网络，采用基于MCMC的采样方法估计潜变量; （ii）通过反向传播和固定的潜在变量联合优化两个网络的参数。广泛的实验表明，我们的框架在准确性和效率方面明显优于其他最先进的方法（例如比竞争方法快1000倍）。

##### URL
[https://arxiv.org/abs/1502.00743](https://arxiv.org/abs/1502.00743)

##### PDF
[https://arxiv.org/pdf/1502.00743](https://arxiv.org/pdf/1502.00743)

