---
layout: post
title: "Noise Based Detection and Segmentation of Nebulous Objects"
date: 2015-09-07 12:54:52
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Mohammad Akhlaghi, Takashi Ichikawa
mathjax: true
---

* content
{:toc}

##### Abstract
A noise-based non-parametric technique for detecting nebulous objects, for example, irregular or clumpy galaxies, and their structure in noise is introduced. "Noise-based" and "non-parametric" imply that this technique imposes negligible constraints on the properties of the targets and that it employs no regression analysis or fittings. The sub-sky detection threshold is defined and initial detections are found, independently of the sky value. False detections are then estimated and removed using the ambient noise as a reference. This results in a purity level of 0.89 for the final detections as compared to 0.29 for SExtractor when a completeness of 1 is desired for a sample of extremely faint and diffuse mock galaxy profiles. The difference in the mean of the undetected pixels with the known background of mock images is decreased by 4.6 times depending on the diffuseness of the test profiles, quantifying the success in their detection. A non-parametric approach to defining substructure over a detected region is also introduced. NoiseChisel is our software implementation of this new technique. Contrary to the existing signal-based approach to detection, in its various implementations, signal-related parameters such as the image point spread function or known object shapes and models are irrelevant here. Such features make this technique very useful in astrophysical applications such as detection, photometry, or morphological analysis of nebulous objects buried in noise, for example, galaxies that do not generically have a known shape when imaged.

##### Abstract (translated by Google)
介绍了一种基于噪声的非参数检测技术，用于检测星系物体，例如不规则或团块状的星系，以及它们在噪声中的结构。 “基于噪声”和“非参数”意味着这种技术对目标的属性施加了可以忽略的约束，并且它不采用回归分析或配件。定义子天空检测阈值并且独立于天空值找到初始检测。然后使用环境噪声作为参考来估计并去除假检测。这导致最终检测的纯度为0.89，而SExtractor的纯度为0.29，而对于极其微弱和漫反射的模拟星系剖面的样品，要求完整性为1。模糊图像的已知背景的未检测像素的均值的差异根据测试轮廓的扩散性而减少4.6倍，量化其检测的成功。还介绍了用于定义检测区域上的子结构的非参数方法。 NoiseChisel是我们这种新技术的软件实现。与现有的基于信号的检测方法相反，在其各种实施方式中，与像信号有关的参数如图像点扩散函数或已知的物体形状和模型在这里是不相关的。这种特征使得这种技术在天体物理学应用中非常有用，例如检测，测光或掩埋在噪声中的含糊的物体的形态分析，例如在成像时通常不具有已知形状的星系。

##### URL
[https://arxiv.org/abs/1505.01664](https://arxiv.org/abs/1505.01664)

##### PDF
[https://arxiv.org/pdf/1505.01664](https://arxiv.org/pdf/1505.01664)

