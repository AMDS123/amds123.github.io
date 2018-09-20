---
layout: post
title: "Dual Reconstruction Nets for Image Super-Resolution with Gradient Sensitive Loss"
date: 2018-09-19 09:39:41
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Deep_Learning
author: Yong Guo, Qi Chen, Jian Chen, Junzhou Huang, Yanwu Xu, Jiezhang Cao, Peilin Zhao, Mingkui Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have exhibited promising performance in image super-resolution (SR) due to the power in learning the non-linear mapping from low-resolution (LR) images to high-resolution (HR) images. However, most deep learning methods employ feed-forward architectures, and thus the dependencies between LR and HR images are not fully exploited, leading to limited learning performance. Moreover, most deep learning based SR methods apply the pixel-wise reconstruction error as the loss, which, however, may fail to capture high-frequency information and produce perceptually unsatisfying results, whilst the recent perceptual loss relies on some pre-trained deep model and they may not generalize well. In this paper, we introduce a mask to separate the image into low- and high-frequency parts based on image gradient magnitude, and then devise a gradient sensitive loss to well capture the structures in the image without sacrificing the recovery of low-frequency content. Moreover, by investigating the duality in SR, we develop a dual reconstruction network (DRN) to improve the SR performance. We provide theoretical analysis on the generalization performance of our method and demonstrate its effectiveness and superiority with thorough experiments.

##### Abstract (translated by Google)
由于学习从低分辨率（LR）图像到高分辨率（HR）图像的非线性映射的能力，深度神经网络在图像超分辨率（SR）中表现出有希望的性能。然而，大多数深度学习方法采用前馈架构，因此LR和HR图像之间的依赖性未被充分利用，导致有限的学习性能。此外，大多数基于深度学习的SR方法将像素方式的重建误差应用为损失，然而，这可能无法捕获高频信息并产生感知上不满意的结果，而最近的感知损失依赖于一些预先训练的深度模型。他们可能不会很好地概括。在本文中，我们引入了一个掩模，根据图像梯度幅度将图像分成低频和高频部分，然后设计梯度敏感损耗，以便很好地捕获图像中的结构，而不会牺牲低频内容的恢复。此外，通过研究SR的二元性，我们开发了双重建网络（DRN）来提高SR性能。我们对该方法的泛化性能进行了理论分析，并通过深入的实验证明了其有效性和优越性。

##### URL
[http://arxiv.org/abs/1809.07099](http://arxiv.org/abs/1809.07099)

##### PDF
[http://arxiv.org/pdf/1809.07099](http://arxiv.org/pdf/1809.07099)

