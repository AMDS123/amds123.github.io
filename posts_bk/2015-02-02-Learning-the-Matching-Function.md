---
layout: post
title: "Learning the Matching Function"
date: 2015-02-02 21:20:43
categories: arXiv_CV
tags: arXiv_CV Regularization Detection
author: Ľubor Ladický, Christian Häne, Marc Pollefeys
mathjax: true
---

* content
{:toc}

##### Abstract
The matching function for the problem of stereo reconstruction or optical flow has been traditionally designed as a function of the distance between the features describing matched pixels. This approach works under assumption, that the appearance of pixels in two stereo cameras or in two consecutive video frames does not change dramatically. However, this might not be the case, if we try to match pixels over a large interval of time. In this paper we propose a method, which learns the matching function, that automatically finds the space of allowed changes in visual appearance, such as due to the motion blur, chromatic distortions, different colour calibration or seasonal changes. Furthermore, it automatically learns the importance of matching scores of contextual features at different relative locations and scales. Proposed classifier gives reliable estimations of pixel disparities already without any form of regularization. We evaluated our method on two standard problems - stereo matching on KITTI outdoor dataset, optical flow on Sintel data set, and on newly introduced TimeLapse change detection dataset. Our algorithm obtained very promising results comparable to the state-of-the-art.

##### Abstract (translated by Google)
传统上将用于立体重建或光流的问题的匹配函数设计为描述匹配像素的特征之间的距离的函数。这种方法在假设下工作，即两个立体相机或两个连续视频帧中的像素的外观不会显着改变。但是，如果我们尝试在很长一段时间内匹配像素，情况可能不会如此。在本文中，我们提出了一种学习匹配函数的方法，该方法自动找到允许的视觉外观变化的空间，例如由于运动模糊，色彩失真，不同的颜色校准或季节变化。此外，它自动学习在不同的相对位置和尺度上匹配上下文特征分数的重要性。建议的分类器给出了可靠的像素差异估计，没有任何形式的正则化。我们在两个标准问题上评估了我们的方法 -  KITTI室外数据集上的立体匹配，Sintel数据集上的光流以及新引入的TimeLapse变化检测数据集。我们的算法获得了与现有技术相媲美的非常有希望的结果。

##### URL
[https://arxiv.org/abs/1502.00652](https://arxiv.org/abs/1502.00652)

##### PDF
[https://arxiv.org/pdf/1502.00652](https://arxiv.org/pdf/1502.00652)

