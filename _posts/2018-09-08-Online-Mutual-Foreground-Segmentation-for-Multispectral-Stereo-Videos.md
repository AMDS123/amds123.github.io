---
layout: post
title: "Online Mutual Foreground Segmentation for Multispectral Stereo Videos"
date: 2018-09-08 18:21:50
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Pierre-Luc St-Charles, Guillaume-Alexandre Bilodeau, Robert Bergevin
mathjax: true
---

* content
{:toc}

##### Abstract
The segmentation of video sequences into foreground and background regions is a low-level process commonly used in video content analysis and smart surveillance applications. Using a multispectral camera setup can improve this process by providing more diverse data to help identify objects despite adverse imaging conditions. The registration of several data sources is however not trivial if the appearance of objects produced by each sensor differs substantially. This problem is further complicated when parallax effects cannot be ignored when using close-range stereo pairs. In this work, we present a new method to simultaneously tackle multispectral segmentation and stereo registration. Using an iterative procedure, we estimate the labeling result for one problem using the provisional result of the other. Our approach is based on the alternating minimization of two energy functions that are linked through the use of dynamic priors. We rely on the integration of shape and appearance cues to find proper multispectral correspondences, and to properly segment objects in low contrast regions. We also formulate our model as a frame processing pipeline using higher order terms to improve the temporal coherence of our results. Our method is evaluated under different configurations on multiple multispectral datasets, and our implementation is available online.

##### Abstract (translated by Google)
将视频序列分割成前景和背景区域是视频内容分析和智能监视应用中常用的低级过程。使用多光谱相机设置可以通过提供更多样化的数据来改善此过程，以帮助在不利的成像条件下识别物体。然而，如果每个传感器产生的物体的外观显着不同，则几个数据源的登记并不是微不足道的。当使用近距离立体声对时，当不能忽略视差效应时，这个问题会更加复杂。在这项工作中，我们提出了一种同时解决多光谱分割和立体声配准的新方法。使用迭代过程，我们使用另一个的临时结果估计一个问题的标记结果。我们的方法基于通过使用动态先验链接的两个能量函数的交替最小化。我们依靠形状和外观线索的整合来找到适当的多光谱对应关系，并在低对比度区域中正确地分割对象。我们还使用高阶项将我们的模型表示为帧处理流水线，以改善我们结果的时间一致性。我们的方法在多个多光谱数据集的不同配置下进行评估，我们的实现可在线获得。

##### URL
[http://arxiv.org/abs/1809.02851](http://arxiv.org/abs/1809.02851)

##### PDF
[http://arxiv.org/pdf/1809.02851](http://arxiv.org/pdf/1809.02851)

