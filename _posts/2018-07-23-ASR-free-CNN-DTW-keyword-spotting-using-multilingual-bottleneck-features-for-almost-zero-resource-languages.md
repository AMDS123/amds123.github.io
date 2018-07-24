---
layout: post
title: "ASR-free CNN-DTW keyword spotting using multilingual bottleneck features for almost zero-resource languages"
date: 2018-07-23 15:14:32
categories: arXiv_CL
tags: arXiv_CL CNN
author: Raghav Menon, Herman Kamper, Emre Yilmaz, John Quinn, Thomas Niesler
mathjax: true
---

* content
{:toc}

##### Abstract
We consider multilingual bottleneck features (BNFs) for nearly zero-resource keyword spotting. This forms part of a United Nations effort using keyword spotting to support humanitarian relief programmes in parts of Africa where languages are severely under-resourced. We use 1920 isolated keywords (40 types, 34 minutes) as exemplars for dynamic time warping (DTW) template matching, which is performed on a much larger body of untranscribed speech. These DTW costs are used as targets for a convolutional neural network (CNN) keyword spotter, giving a much faster system than direct DTW. Here we consider how available data from well-resourced languages can improve this CNN-DTW approach. We show that multilingual BNFs trained on ten languages improve the area under the ROC curve of a CNN-DTW system by 10.9% absolute relative to the MFCC baseline. By combining low-resource DTW-based supervision with information from well-resourced languages, CNN-DTW is a competitive option for low-resource keyword spotting.

##### Abstract (translated by Google)
我们考虑使用多语言瓶颈功能（BNF）来实现几乎零资源的关键字定位。这是联合国努力的一部分，使用关键词定位来支持非洲部分语言资源严重不足的人道主义救济方案。我们使用1920个孤立的关键字（40种类型，34分钟）作为动态时间扭曲（DTW）模板匹配的示例，其在更大的未转录语音体上执行。这些DTW成本用作卷积神经网络（CNN）关键字检测器的目标，提供比直接DTW快得多的系统。在这里，我们考虑来自资源充足的语言的可用数据如何改进这种CNN-DTW方法。我们表明，用十种语言训练的多语种BNF改善了CNN-DTW系统的ROC曲线下面积相对于MFCC基线的绝对值10.9％。通过将基于DTW的低资源监督与来自资源充足的语言的信息相结合，CNN-DTW是低资源关键字定位的竞争选择。

##### URL
[http://arxiv.org/abs/1807.08666](http://arxiv.org/abs/1807.08666)

##### PDF
[http://arxiv.org/pdf/1807.08666](http://arxiv.org/pdf/1807.08666)

