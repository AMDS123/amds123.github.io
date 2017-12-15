---
layout: post
title: "Coupled Depth Learning"
date: 2016-02-09 16:27:35
categories: arXiv_CV
tags: arXiv_CV
author: Mohammad Haris Baig, Lorenzo Torresani
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a method for estimating depth from a single image using a coarse to fine approach. We argue that modeling the fine depth details is easier after a coarse depth map has been computed. We express a global (coarse) depth map of an image as a linear combination of a depth basis learned from training examples. The depth basis captures spatial and statistical regularities and reduces the problem of global depth estimation to the task of predicting the input-specific coefficients in the linear combination. This is formulated as a regression problem from a holistic representation of the image. Crucially, the depth basis and the regression function are {\bf coupled} and jointly optimized by our learning scheme. We demonstrate that this results in a significant improvement in accuracy compared to direct regression of depth pixel values or approaches learning the depth basis disjointly from the regression function. The global depth estimate is then used as a guidance by a local refinement method that introduces depth details that were not captured at the global level. Experiments on the NYUv2 and KITTI datasets show that our method outperforms the existing state-of-the-art at a considerably lower computational cost for both training and testing.

##### Abstract (translated by Google)
在本文中，我们提出了一种使用粗到细的方法从单个图像估计深度的方法。我们认为，在计算出粗糙的深度图之后，对精细的深度细节进行建模将变得更加容易。我们将图像的全局（粗糙）深度图表示为从训练示例中学习的深度基础的线性组合。深度基础捕捉空间和统计规律，并将全局深度估计的问题减少到预测线性组合中的输入特定系数的任务。这是从图像的整体表示形式的回归问题。关键是深度基础和回归函数是由我们的学习方案共同优化的。我们证明，与深度像素值的直接回归或者从回归函数中不相交地学习深度基础的方法相比，这导致准确度的显着提高。然后将全球深度估算用作本地求精方法的指导，该方法引入了在全球层面上未捕获的深度细节。对NYUv2和KITTI数据集进行的实验表明，我们的方法在训练和测试方面的性能优于现有技术，计算成本相当低。

##### URL
[https://arxiv.org/abs/1501.04537](https://arxiv.org/abs/1501.04537)

##### PDF
[https://arxiv.org/pdf/1501.04537](https://arxiv.org/pdf/1501.04537)

