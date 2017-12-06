---
layout: post
title: 'Image Decomposition Using a Robust Regression Approach'
date: 2017-12-05 21:10:17
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Shervin Minaee, Yao Wang
---

* content
{:toc}

##### Abstract
This paper considers how to separate text and/or graphics from smooth background in screen content and mixed content images and proposes an algorithm to perform this segmentation task. The proposed methods make use of the fact that the background in each block is usually smoothly varying and can be modeled well by a linear combination of a few smoothly varying basis functions, while the foreground text and graphics create sharp discontinuity. This algorithm separates the background and foreground pixels by trying to fit pixel values in the block into a smooth function using a robust regression method. The inlier pixels that can be well represented with the smooth model will be considered as background, while remaining outlier pixels will be considered foreground. We have also created a dataset of screen content images extracted from HEVC standard test sequences for screen content coding with their ground truth segmentation result which can be used for this task. The proposed algorithm has been tested on the dataset mentioned above and is shown to have superior performance over other methods, such as the hierarchical k-means clustering algorithm, shape primitive extraction and coding, and the least absolute deviation fitting scheme for foreground segmentation.

##### Abstract (translated by Google)
本文考虑如何将平滑的背景中的文本和/或图形与屏幕内容和混合的内容图像分开，并提出一种执行该分割任务的算法。所提出的方法利用了这样的事实，即每个块中的背景通常是平滑变化的，并且可以通过几个平滑变化的基函数的线性组合来良好地建模，而前景文本和图形产生急剧的不连续性。该算法通过尝试使用稳健的回归方法将块中的像素值合并为平滑函数来分离背景和前景像素。可以用光滑模型很好地表示的内部像素将被视为背景，而剩余的异常像素将被视为前景。我们还创建了从HEVC标准测试序列中提取的屏幕内容图像的数据集，用于屏幕内容编码，其地面真实分割结果可用于此任务。该算法已经在上述数据集上进行了测试，并且表现出优于其他方法的性能，如分层k均值聚类算法，形状基元提取和编码以及用于前景分割的最小绝对偏差拟合方案。

##### URL
[http://arxiv.org/abs/1609.03874](http://arxiv.org/abs/1609.03874)

