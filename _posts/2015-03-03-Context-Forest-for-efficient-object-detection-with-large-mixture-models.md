---
layout: post
title: "Context Forest for efficient object detection with large mixture models"
date: 2015-03-03 00:20:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Davide Modolo, Alexander Vezhnevets, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We present Context Forest (ConF), a technique for predicting properties of the objects in an image based on its global appearance. Compared to standard nearest-neighbour techniques, ConF is more accurate, fast and memory efficient. We train ConF to predict which aspects of an object class are likely to appear in a given image (e.g. which viewpoint). This enables to speed-up multi-component object detectors, by automatically selecting the most relevant components to run on that image. This is particularly useful for detectors trained from large datasets, which typically need many components to fully absorb the data and reach their peak performance. ConF provides a speed-up of 2x for the DPM detector [1] and of 10x for the EE-SVM detector [2]. To show ConF's generality, we also train it to predict at which locations objects are likely to appear in an image. Incorporating this information in the detector score improves mAP performance by about 2% by removing false positive detections in unlikely locations.

##### Abstract (translated by Google)
我们提出上下文森林（ConF），一种基于全局外观预测图像中对象属性的技术。与标准最近邻技术相比，ConF更加准确，快速和高效。我们训练ConF来预测对象类的哪些方面可能出现在给定图像中（例如哪个视点）。这样可以通过自动选择最相关的组件来在该图像上运行，从而加速多组分物体检测器。这对于从大型数据集训练的检测器特别有用，通常需要很多组件来充分吸收数据并达到最佳性能。 ConF为DPM检测器[1]提供2倍的加速度，为EE-SVM检测器提供10倍的加速度[2]。为了显示ConF的一般性，我们还训练它来预测对象可能出现在图像中的哪个位置。将这些信息合并到检测器分数中，通过消除不可能的位置上的误报检测，可将MAP性能提高大约2％。

##### URL
[https://arxiv.org/abs/1503.00787](https://arxiv.org/abs/1503.00787)

