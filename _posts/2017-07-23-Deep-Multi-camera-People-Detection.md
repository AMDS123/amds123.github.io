---
layout: post
title: "Deep Multi-camera People Detection"
date: 2017-07-23 19:14:01
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Detection
author: Tatjana Chavdarova, François Fleuret
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of multi-view people occupancy map estimation. Existing solutions for this problem either operate per-view, or rely on a background subtraction pre-processing. Both approaches lessen the detection performance as scenes become more crowded. The former does not exploit joint information, whereas the latter deals with ambiguous input due to the foreground blobs becoming more and more interconnected as the number of targets increases. Although deep learning algorithms have proven to excel on remarkably numerous computer vision tasks, such a method has not been applied yet to this problem. In large part this is due to the lack of large-scale multi-camera data-set. The core of our method is an architecture which makes use of monocular pedestrian data-set, available at larger scale then the multi-view ones, applies parallel processing to the multiple video streams, and jointly utilises it. Our end-to-end deep learning method outperforms existing methods by large margins on the commonly used PETS 2009 data-set. Furthermore, we make publicly available a new three-camera HD data-set. Our source code and trained models will be made available under an open-source license.

##### Abstract (translated by Google)
本文解决了多视图人员占用图估计的问题。此问题的现有解决方案要么按照每个视图进行操作，要么依靠背景扣除预处理。随着场景变得更加拥挤，两种方法都降低了检测性能。前者不利用联合信息，后者处理模糊输入，因为随着目标数量的增加，前景斑点越来越相互联系。尽管深度学习算法已经被证明能够胜任大量的计算机视觉任务，但是这样的方法还没有被应用于这个问题。这在很大程度上是由于缺乏大规模的多摄像头数据集。我们方法的核心是利用单视图行人数据集的架构，可以在更大的范围内使用多视图的数据集，对多视频流进行并行处理并联合使用。我们的端到端深度学习方法在常用的PETS 2009数据集上大大优于现有的方法。此外，我们公开提供了一个新的三相机高清数据集。我们的源代码和训练有素的模型将在开源许可下提供。

##### URL
[https://arxiv.org/abs/1702.04593](https://arxiv.org/abs/1702.04593)

##### PDF
[https://arxiv.org/pdf/1702.04593](https://arxiv.org/pdf/1702.04593)

