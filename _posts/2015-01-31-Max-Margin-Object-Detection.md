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
大多数对象检测方法是通过将二进制分类器应用于图像的子窗口，然后进行非最大抑制步骤，其中重叠子窗口上的检测被去除。由于即使是中等大小的图像数据集中可能的子窗口的数量是非常大的，分类器通常仅从窗口的子集中学习。这样避免了处理整个子窗口的计算难度，但是，正如我们在本文中所展示的那样，这会导致次优的检测器性能。特别是，本文的主要贡献是引入了一种新的方法，最大值 - 边缘对象检测（MMOD），用于学习检测图像中的对象。此方法不执行任何子采样，而是优化所有子窗口。 MMOD可以用于改进任何在学习参数上线性的对象检测方法，例如HOG或视觉词袋模型（bag-of-visual-word models）。使用这种方法，我们在三个公开可用的数据集上显示出显着的性能增益引人注目的是，当通过MMOD学习HOG滤波器时，我们证明单个刚性HOG滤波器可以胜过人脸检测数据集和基准中的最新可变形部分模型。

##### URL
[https://arxiv.org/abs/1502.00046](https://arxiv.org/abs/1502.00046)

##### PDF
[https://arxiv.org/pdf/1502.00046](https://arxiv.org/pdf/1502.00046)

