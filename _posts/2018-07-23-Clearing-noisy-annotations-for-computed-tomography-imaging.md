---
layout: post
title: "Clearing noisy annotations for computed tomography imaging"
date: 2018-07-23 16:42:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification Prediction
author: Roman Khudorozhkov, Alexander Koryagin, Alexey Kozhevin
mathjax: true
---

* content
{:toc}

##### Abstract
One of the problems on the way to successful implementation of neural networks is the quality of annotation. For instance, different annotators can annotate images in a different way and very often their decisions do not match exactly and in extreme cases are even mutually exclusive which results in noisy annotations and, consequently, inaccurate predictions. To avoid that problem in the task of computed tomography (CT) imaging segmentation we propose a clearing algorithm for annotations. It consists of 3 stages: - annotators scoring, which assigns a higher confidence level to better annotators; - nodules scoring, which assigns a higher confidence level to nodules confirmed by good annotators; - nodules merging, which aggregates annotations according to nodules confidence. In general, the algorithm can be applied to many different tasks (namely, binary and multi-class semantic segmentation, and also with trivial adjustments to classification and regression) where there are several annotators labeling each image.

##### Abstract (translated by Google)
成功实现神经网络的方法之一是注释的质量。例如，不同的注释器可以以不同的方式注释图像，并且通常它们的决定不完全匹配，并且在极端情况下甚至是相互排斥的，这导致嘈杂的注释，并且因此导致不准确的预测。为了避免计算机断层扫描（CT）成像分割任务中的这个问题，我们提出了一种用于注释的清除算法。它由3个阶段组成： - 注释器评分，为更好的注释者分配更高的置信度; - 结节评分，为良好的注释者确认的结节分配更高的置信水平; - 结节合并，根据结节置信度汇总注释。通常，该算法可以应用于许多不同的任务（即，二进制和多类语义分段，以及对分类和回归的微不足道的调整），其中有几个注释器标记每个图像。

##### URL
[https://arxiv.org/abs/1807.09151](https://arxiv.org/abs/1807.09151)

##### PDF
[https://arxiv.org/pdf/1807.09151](https://arxiv.org/pdf/1807.09151)

