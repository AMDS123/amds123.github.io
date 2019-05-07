---
layout: post
title: "Max-Margin Object Detection"
date: 2015-01-31 00:32:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Face_Detection
author: Davis E. King
mathjax: true
---

* content
{:toc}

##### Abstract
Most object detection methods operate by applying a binary classifier to sub-windows of an image, followed by a non-maximum suppression step where detections on overlapping sub-windows are removed. Since the number of possible sub-windows in even moderately sized image datasets is extremely large, the classifier is typically learned from only a subset of the windows. This avoids the computational difficulty of dealing with the entire set of sub-windows, however, as we will show in this paper, it leads to sub-optimal detector performance. In particular, the main contribution of this paper is the introduction of a new method, Max-Margin Object Detection (MMOD), for learning to detect objects in images. This method does not perform any sub-sampling, but instead optimizes over all sub-windows. MMOD can be used to improve any object detection method which is linear in the learned parameters, such as HOG or bag-of-visual-word models. Using this approach we show substantial performance gains on three publicly available datasets. Strikingly, we show that a single rigid HOG filter can outperform a state-of-the-art deformable part model on the Face Detection Data Set and Benchmark when the HOG filter is learned via MMOD.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1502.00046](https://arxiv.org/abs/1502.00046)

##### PDF
[https://arxiv.org/pdf/1502.00046](https://arxiv.org/pdf/1502.00046)

