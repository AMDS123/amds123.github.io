---
layout: post
title: "People Counting in High Density Crowds from Still Images"
date: 2015-07-30 10:47:31
categories: arXiv_CV
tags: arXiv_CV Detection
author: Ankan Bansal, K.S. Venkatesh
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method of estimating the number of people in high density crowds from still images. The method estimates counts by fusing information from multiple sources. Most of the existing work on crowd counting deals with very small crowds (tens of individuals) and use temporal information from videos. Our method uses only still images to estimate the counts in high density images (hundreds to thousands of individuals). At this scale, we cannot rely on only one set of features for count estimation. We, therefore, use multiple sources, viz. interest points (SIFT), Fourier analysis, wavelet decomposition, GLCM features and low confidence head detections, to estimate the counts. Each of these sources gives a separate estimate of the count along with confidences and other statistical measures which are then combined to obtain the final estimate. We test our method on an existing dataset of fifty images containing over 64000 individuals. Further, we added another fifty annotated images of crowds and tested on the complete dataset of hundred images containing over 87000 individuals. The counts per image range from 81 to 4633. We report the performance in terms of mean absolute error, which is a measure of accuracy of the method, and mean normalised absolute error, which is a measure of the robustness.

##### Abstract (translated by Google)
我们提出一种从静止图像中估计高密度人群中人数的方法。该方法通过融合来自多个来源的信息来估计计数。现有的人群统计工作大部分是针对非常小的人群（数十人），并利用视频中的时间信息。我们的方法只使用静止图像来估计高密度图像（数百到数千人）的计数。在这个尺度上，我们不能只依靠一组特征来进行计数估计。因此，我们使用多个来源，即。兴趣点（SIFT），傅立叶分析，小波分解，GLCM特征和低置信度头部检测，以估计计数。这些来源中的每一个给出了计数的单独估计以及置信度和其他统计测量，然后将这些统计测量结合起来以获得最终估计。我们在包含超过64000个个体的50个图像的现有数据集上测试我们的方法。此外，我们增加了另外五十个带注释的人群图像，并在包含超过87000个个人的100张图像的完整数据集上进行测试。每个图像的计数范围从81到4633.我们报告的平均绝对误差，这是一种方法的准确性的措施，平均归一化绝对误差，这是一个衡量鲁棒性的性能。

##### URL
[https://arxiv.org/abs/1507.08445](https://arxiv.org/abs/1507.08445)

##### PDF
[https://arxiv.org/pdf/1507.08445](https://arxiv.org/pdf/1507.08445)

