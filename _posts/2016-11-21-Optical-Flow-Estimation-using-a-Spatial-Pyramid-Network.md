---
layout: post
title: "Optical Flow Estimation using a Spatial Pyramid Network"
date: 2016-11-21 19:01:19
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Anurag Ranjan, Michael J. Black
mathjax: true
---

* content
{:toc}

##### Abstract
We learn to compute optical flow by combining a classical spatial-pyramid formulation with deep learning. This estimates large motions in a coarse-to-fine approach by warping one image of a pair at each pyramid level by the current flow estimate and computing an update to the flow. Instead of the standard minimization of an objective function at each pyramid level, we train one deep network per level to compute the flow update. Unlike the recent FlowNet approach, the networks do not need to deal with large motions; these are dealt with by the pyramid. This has several advantages. First, our Spatial Pyramid Network (SPyNet) is much simpler and 96% smaller than FlowNet in terms of model parameters. This makes it more efficient and appropriate for embedded applications. Second, since the flow at each pyramid level is small (< 1 pixel), a convolutional approach applied to pairs of warped images is appropriate. Third, unlike FlowNet, the learned convolution filters appear similar to classical spatio-temporal filters, giving insight into the method and how to improve it. Our results are more accurate than FlowNet on most standard benchmarks, suggesting a new direction of combining classical flow methods with deep learning.

##### Abstract (translated by Google)
我们学习通过结合经典的空间金字塔形式和深度学习来计算光流。这通过在每个金字塔等级上通过当前流量估计扭曲一对图像中的一个图像并且计算流量的更新来粗略地估计大的运动。我们不是每个金字塔等级的标准最小化目标函数，而是每个层次训练一个深度网络来计算流量更新。与最近的FlowNet方法不同，网络不需要处理大的运动;这些由金字塔处理。这有几个好处。首先，就模型参数而言，我们的空间金字塔网络（SPyNet）简单得多，比FlowNet小96％。这使得嵌入式应用程序更加高效和适用。其次，由于每个金字塔等级的流量都很小（<1个像素），所以应用于成对的扭曲图像的卷积方法是合适的。第三，与FlowNet不同，已知的卷积滤波器看起来与经典的时空滤波器类似，从而深入了解该方法以及如何改进。我们的结果在大多数标准基准上比FlowNet更精确，表明了经典流动方法与深度学习相结合的新方向。

##### URL
[https://arxiv.org/abs/1611.00850](https://arxiv.org/abs/1611.00850)

##### PDF
[https://arxiv.org/pdf/1611.00850](https://arxiv.org/pdf/1611.00850)

