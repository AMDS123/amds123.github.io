---
layout: post
title: "U-Net: Convolutional Networks for Biomedical Image Segmentation"
date: 2015-05-18 11:28:37
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking CNN
author: Olaf Ronneberger, Philipp Fischer, Thomas Brox
mathjax: true
---

* content
{:toc}

##### Abstract
There is large consent that successful training of deep networks requires many thousand annotated training samples. In this paper, we present a network and training strategy that relies on the strong use of data augmentation to use the available annotated samples more efficiently. The architecture consists of a contracting path to capture context and a symmetric expanding path that enables precise localization. We show that such a network can be trained end-to-end from very few images and outperforms the prior best method (a sliding-window convolutional network) on the ISBI challenge for segmentation of neuronal structures in electron microscopic stacks. Using the same network trained on transmitted light microscopy images (phase contrast and DIC) we won the ISBI cell tracking challenge 2015 in these categories by a large margin. Moreover, the network is fast. Segmentation of a 512x512 image takes less than a second on a recent GPU. The full implementation (based on Caffe) and the trained networks are available at this http URL .

##### Abstract (translated by Google)
有大量的同意认为深度网络的成功训练需要数千个注释训练样本。在本文中，我们提出了一个网络和培训策略，依靠强大的数据增强使用更有效地使用可用的注释样本。该体系结构由一个捕捉上下文的合同路径和一个对称扩展路径组成，可实现精确定位。我们表明，这样一个网络可以训练端到端从极少的图像，并胜过先前最好的方法（滑动窗口卷积网络）的ISBI挑战分割神经元结构在电子显微镜堆栈。使用透射光显微镜图像（相差和DIC）训练的相同网络，我们在这些类别中赢得了ISBI细胞跟踪挑战2015大幅度的提升。而且，网络速度很快。在最近的GPU上，512x512图像的分割不到一秒钟。完整的实现（基于Caffe）和训练有素的网络可以在这个http URL中找到。

##### URL
[https://arxiv.org/abs/1505.04597](https://arxiv.org/abs/1505.04597)

##### PDF
[https://arxiv.org/pdf/1505.04597](https://arxiv.org/pdf/1505.04597)

