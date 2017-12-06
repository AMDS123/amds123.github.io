---
layout: post
title: "Detection of Partially Visible Objects"
date: 2013-11-24 16:59:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Patrick Ott, Mark Everingham, Jiri Matas
mathjax: true
---

* content
{:toc}

##### Abstract
An "elephant in the room" for most current object detection and localization methods is the lack of explicit modelling of partial visibility due to occlusion by other objects or truncation by the image boundary. Based on a sliding window approach, we propose a detection method which explicitly models partial visibility by treating it as a latent variable. A novel non-maximum suppression scheme is proposed which takes into account the inferred partial visibility of objects while providing a globally optimal solution. The method gives more detailed scene interpretations than conventional detectors in that we are able to identify the visible parts of an object. We report improved average precision on the PASCAL VOC 2010 dataset compared to a baseline detector.

##### Abstract (translated by Google)
对于大多数当前的物体检测和定位方法来说，“房间中的大象”是由于其他物体的遮挡或者图像边界的截断而缺乏局部可见性的显式建模。基于滑动窗口方法，我们提出了一种检测方法，明确地模仿局部可见性，将其视为一个潜在的变量。提出了一种新的非最大抑制方案，该方案考虑了对象的推断局部可见性，同时提供了全局最优解。该方法比传统的检测器提供更详细的场景解释，因为我们能够识别物体的可见部分。与基线检测器相比，我们报告PASCAL VOC 2010数据集的平均精度提高。

##### URL
[https://arxiv.org/abs/1311.6758](https://arxiv.org/abs/1311.6758)

