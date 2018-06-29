---
layout: post
title: "Towards automatic initialization of registration algorithms using simulated endoscopy images"
date: 2018-06-28 02:58:25
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Ayushi Sinha, Masaru Ishii, Russell H. Taylor, Gregory D. Hager, Austin Reiter
mathjax: true
---

* content
{:toc}

##### Abstract
Registering images from different modalities is an active area of research in computer aided medical interventions. Several registration algorithms have been developed, many of which achieve high accuracy. However, these results are dependent on many factors, including the quality of the extracted features or segmentations being registered as well as the initial alignment. Although several methods have been developed towards improving segmentation algorithms and automating the segmentation process, few automatic initialization algorithms have been explored. In many cases, the initial alignment from which a registration is initiated is performed manually, which interferes with the clinical workflow. Our aim is to use scene classification in endoscopic procedures to achieve coarse alignment of the endoscope and a preoperative image of the anatomy. In this paper, we show using simulated scenes that a neural network can predict the region of anatomy (with respect to a preoperative image) that the endoscope is located in by observing a single endoscopic video frame. With limited training and without any hyperparameter tuning, our method achieves an accuracy of 76.53 (+/-1.19)%. There are several avenues for improvement, making this a promising direction of research. Code is available at https://github.com/AyushiSinha/AutoInitialization.

##### Abstract (translated by Google)
注册不同形式的图像是计算机辅助医疗干预研究的一个活跃领域。已经开发了几种注册算法，其中许多算法实现了高精度。但是，这些结果取决于许多因素，包括提取的特征或分段的质量以及初始对齐。尽管已经开发了几种方法来改进分割算法并使分割过程自动化，但很少有自动初始化算法被探索。在许多情况下，开始注册的初始对齐是手动执行的，这会干扰临床工作流程。我们的目标是在内窥镜程序中使用场景分类来实现内窥镜的粗对准和解剖结构的术前图像。在本文中，我们展示了使用模拟场景，神经网络可以通过观察单个内窥镜视频帧来预测内窥镜位于的解剖区域（相对于术前图像）。由于训练有限且没有任何超参数调整，我们的方法达到了76.53（+/- 1.19）％的准确度。有几个途径需要改进，使得这是一个有前景的研究方向。代码位于https://github.com/AyushiSinha/AutoInitialization。

##### URL
[http://arxiv.org/abs/1806.10748](http://arxiv.org/abs/1806.10748)

##### PDF
[http://arxiv.org/pdf/1806.10748](http://arxiv.org/pdf/1806.10748)

