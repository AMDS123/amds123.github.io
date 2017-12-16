---
layout: post
title: "People Counting in Crowded and Outdoor Scenes using a Hybrid Multi-Camera Approach"
date: 2017-05-08 12:51:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Fabio Dittrich, Luiz E. S. de Oliveira, Alceu S. Britto Jr., Alessandro L. Koerich
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents two novel approaches for people counting in crowded and open environments that combine the information gathered by multiple views. Multiple camera are used to expand the field of view as well as to mitigate the problem of occlusion that commonly affects the performance of counting methods using single cameras. The first approach is regarded as a direct approach and it attempts to segment and count each individual in the crowd. For such an aim, two head detectors trained with head images are employed: one based on support vector machines and another based on Adaboost perceptron. The second approach, regarded as an indirect approach employs learning algorithms and statistical analysis on the whole crowd to achieve counting. For such an aim, corner points are extracted from groups of people in a foreground image and computed by a learning algorithm which estimates the number of people in the scene. Both approaches count the number of people on the scene and not only on a given image or video frame of the scene. The experimental results obtained on the benchmark PETS2009 video dataset show that proposed indirect method surpasses other methods with improvements of up to 46.7% and provides accurate counting results for the crowded scenes. On the other hand, the direct method shows high error rates due to the fact that the latter has much more complex problems to solve, such as segmentation of heads.

##### Abstract (translated by Google)
本文提出了两种新颖的方法，用于在拥挤和开放的环境中进行人数统计，将多个视图收集的信息结合起来。多摄像头用于扩大视野范围，并减轻通常影响使用单摄像头计数方法性能的遮挡问题。第一种方法被认为是一种直接的方法，它试图分割和统计人群中的每一个人。为了达到这样的目的，采用了用头部图像训练的两个头部检测器：一个基于支持向量机，另一个基于Adaboost感知器。第二种方法被认为是一种间接方法，在整个人群中使用学习算法和统计分析来实现计数。为了这样的目标，从前景图像中的人群中提取角点并且通过估计场景中的人数的学习算法来计算角点。两种方法都可以计算场景中的人数，而不仅仅是场景中给定的图像或视频帧。基准PETS2009视频数据集的实验结果表明，提出的间接方法优于其他方法，提高了46.7％，为拥挤的场景提供了精确的计数结果。另一方面，直接法显示出较高的错误率，这是由于后者具有更复杂的问题需要解决，例如头部分割。

##### URL
[https://arxiv.org/abs/1704.00326](https://arxiv.org/abs/1704.00326)

##### PDF
[https://arxiv.org/pdf/1704.00326](https://arxiv.org/pdf/1704.00326)

