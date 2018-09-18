---
layout: post
title: "Evaluating Merging Strategies for Sampling-based Uncertainty Techniques in Object Detection"
date: 2018-09-17 03:16:03
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Classification Detection
author: Dimity Miller, Feras Dayoub, Michael Milford, Niko S&#xfc;nderhauf
mathjax: true
---

* content
{:toc}

##### Abstract
There has been a recent emergence of sampling-based techniques for estimating epistemic uncertainty in deep neural networks. While these methods can be applied to classification or semantic segmentation tasks by simply averaging samples, this is not the case for object detection, where detection sample bounding boxes must be accurately associated and merged. A weak merging strategy can significantly degrade the performance of the detector and yield an unreliable uncertainty measure. This paper provides the first in-depth investigation of the effect of different association and merging strategies. We compare different combinations of three spatial and two semantic affinity measures with four clustering methods for MC Dropout with a Single Shot Multi-Box Detector. Our results show that the correct choice of affinity-clustering combinations can greatly improve the effectiveness of the classification and spatial uncertainty estimation and the resulting object detection performance. We base our evaluation on a new mix of datasets that emulate near open-set conditions (semantically similar unknown classes), distant open-set conditions (semantically dissimilar unknown classes) and the common closed-set conditions (only known classes).

##### Abstract (translated by Google)
最近出现了基于抽样的技术，用于估计深度神经网络中的认知不确定性。虽然这些方法可以通过简单地平均样本来应用于分类或语义分割任务，但是对于物体检测不是这种情况，其中必须准确地关联和合并检测样本边界框。弱合并策略会显着降低检测器的性能并产生不可靠的不确定性测量。本文首次深入研究了不同关联和融合策略的效果。我们将三种空间和两种语义亲和度测量的不同组合与使用单次射击多盒检测器的MC Dropout的四种聚类方法进行比较。我们的结果表明，正确选择亲和 - 聚类组合可以大大提高分类和空间不确定性估计的有效性以及由此产生的对象检测性能。我们的评估基于一种新的数据集组合，它们模拟接近开放条件（语义上类似的未知类），远程开放条件（语义上不同的未知类）和常见的闭集条件（仅已知类）。

##### URL
[http://arxiv.org/abs/1809.06006](http://arxiv.org/abs/1809.06006)

##### PDF
[http://arxiv.org/pdf/1809.06006](http://arxiv.org/pdf/1809.06006)

