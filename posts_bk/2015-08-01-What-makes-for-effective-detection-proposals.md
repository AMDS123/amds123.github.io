---
layout: post
title: "What makes for effective detection proposals?"
date: 2015-08-01 16:33:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Jan Hosang, Rodrigo Benenson, Piotr Dollár, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
Current top performing object detectors employ detection proposals to guide the search for objects, thereby avoiding exhaustive sliding window search across images. Despite the popularity and widespread use of detection proposals, it is unclear which trade-offs are made when using them during object detection. We provide an in-depth analysis of twelve proposal methods along with four baselines regarding proposal repeatability, ground truth annotation recall on PASCAL, ImageNet, and MS COCO, and their impact on DPM, R-CNN, and Fast R-CNN detection performance. Our analysis shows that for object detection improving proposal localisation accuracy is as important as improving recall. We introduce a novel metric, the average recall (AR), which rewards both high recall and good localisation and correlates surprisingly well with detection performance. Our findings show common strengths and weaknesses of existing methods, and provide insights and metrics for selecting and tuning proposal methods.

##### Abstract (translated by Google)
当前性能最好的对象检测器使用检测建议来指导对象的搜索，从而避免在图像上进行穷尽的滑动窗口搜索。尽管检测建议的普及和广泛使用，但在对象检测期间使用它们时还不清楚哪些是取舍的。我们对12种提案方法以及PASCAL，ImageNet和MS COCO的提案可重复性，地面实况标注回忆，以及它们对DPM，R-CNN和Fast R-CNN检测性能的影响提供了四个基线的深入分析。我们的分析表明，对于提高对象检测的提议，定位精度与提高召回率同样重要。我们引入了一个新的度量标准，即平均召回率（AR），这个标准可以提高召回率和良好的本地化水平，并且与检测性能之间的相关性非常好。我们的研究结果显示了现有方法的共同优点和缺点，并为选择和调整提案方法提供了见解和指标。

##### URL
[https://arxiv.org/abs/1502.05082](https://arxiv.org/abs/1502.05082)

##### PDF
[https://arxiv.org/pdf/1502.05082](https://arxiv.org/pdf/1502.05082)

