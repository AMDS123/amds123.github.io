---
layout: post
title: "Hi Detector, What's Wrong with that Object? Identifying Irregular Object From Images by Modelling the Detection Score Distribution"
date: 2016-02-14 06:39:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Peng Wang, Lingqiao Liu, Chunhua Shen, Anton van den Hengel, Heng Tao Shen
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we study the challenging problem of identifying the irregular status of objects from images in an "open world" setting, that is, distinguishing the irregular status of an object category from its regular status as well as objects from other categories in the absence of "irregular object" training data. To address this problem, we propose a novel approach by inspecting the distribution of the detection scores at multiple image regions based on the detector trained from the "regular object" and "other objects". The key observation motivating our approach is that for "regular object" images as well as "other objects" images, the region-level scores follow their own essential patterns in terms of both the score values and the spatial distributions while the detection scores obtained from an "irregular object" image tend to break these patterns. To model this distribution, we propose to use Gaussian Processes (GP) to construct two separate generative models for the case of the "regular object" and the "other objects". More specifically, we design a new covariance function to simultaneously model the detection score at a single region and the score dependencies at multiple regions. We finally demonstrate the superior performance of our method on a large dataset newly proposed in this paper.

##### Abstract (translated by Google)
在这项工作中，我们研究了在“开放世界”设置中识别图像中物体不规则状态的挑战性问题，即区分物体类别的不规则状态与正常状态以及物体与其他类别的物体缺少“不规则物体”训练数据。为了解决这个问题，我们提出了一种新颖的方法，通过检查“常规对象”和“其他对象”训练的检测器在多个图像区域检测分数的分布。激励我们的方法的关键观察是，对于“常规对象”图像以及“其他对象”图像，地区级别分数在分数值和空间分布两方面都遵循它们自己的基本模式，而从一个“不规则物体”的图像往往会打破这些模式。为了模拟这种分布，我们建议使用高斯过程（GP）为“常规对象”和“其他对象”构建两个单独的生成模型。更具体地说，我们设计了一个新的协方差函数来同时模拟单个地区的检测分数和多个地区的分数依赖性。最后我们证明了本文新提出的一个大型数据集的优越性能。

##### URL
[https://arxiv.org/abs/1602.04422](https://arxiv.org/abs/1602.04422)

##### PDF
[https://arxiv.org/pdf/1602.04422](https://arxiv.org/pdf/1602.04422)

