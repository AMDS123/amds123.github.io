---
layout: post
title: "Learning Light Field Reconstruction from a Single Coded Image"
date: 2018-01-20 18:17:19
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Anil Kumar Vadathya, Saikiran Cholleti, Gautham Ramajayam, Vijayalakshmi Kanchana, Kaushik Mitra
mathjax: true
---

* content
{:toc}

##### Abstract
Light field imaging is a rich way of representing the 3D world around us. However, due to limited sensor resolution capturing light field data inherently poses spatio-angular resolution trade-off. In this paper, we propose a deep learning based solution to tackle the resolution trade-off. Specifically, we reconstruct full sensor resolution light field from a single coded image. We propose to do this in three stages 1) reconstruction of center view from the coded image 2) estimating disparity map from the coded image and center view 3) warping center view using the disparity to generate light field. We propose three neural networks for these stages. Our disparity estimation network is trained in an unsupervised manner alleviating the need for ground truth disparity. Our results demonstrate better recovery of parallax from the coded image. Also, we get better results than dictionary learning approaches on simulated data.

##### Abstract (translated by Google)
光场成像是代表我们周围的3D世界的丰富方式。然而，由于有限的传感器分辨率捕获光场数据固有地构成空间角分辨率折衷。在本文中，我们提出了一个基于深度学习的解决方案来解决分辨率的权衡。具体而言，我们从单个编码图像重建完整的传感器分辨率光场。我们建议在三个阶段进行1）从编码图像重建中心视图2）从编码图像和中心视图估计视差图3）使用视差来产生光场的变形中心视图。我们为这些阶段提出三个神经网络。我们的视差估计网络以无监督的方式进行训练，减轻了对地面差距的需求。我们的结果表明从编码的图像更好地恢复视差。而且，我们在模拟数据上获得比字典学习方法更好的结果。

##### URL
[https://arxiv.org/abs/1801.06710](https://arxiv.org/abs/1801.06710)

##### PDF
[https://arxiv.org/pdf/1801.06710](https://arxiv.org/pdf/1801.06710)

