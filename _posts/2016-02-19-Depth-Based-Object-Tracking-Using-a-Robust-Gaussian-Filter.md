---
layout: post
title: "Depth-Based Object Tracking Using a Robust Gaussian Filter"
date: 2016-02-19 14:09:37
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Quantitative Detection
author: Jan Issac, Manuel Wüthrich, Cristina Garcia Cifuentes, Jeannette Bohg, Sebastian Trimpe, Stefan Schaal
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of model-based 3D-tracking of objects given dense depth images as input. Two difficulties preclude the application of a standard Gaussian filter to this problem. First of all, depth sensors are characterized by fat-tailed measurement noise. To address this issue, we show how a recently published robustification method for Gaussian filters can be applied to the problem at hand. Thereby, we avoid using heuristic outlier detection methods that simply reject measurements if they do not match the model. Secondly, the computational cost of the standard Gaussian filter is prohibitive due to the high-dimensional measurement, i.e. the depth image. To address this problem, we propose an approximation to reduce the computational complexity of the filter. In quantitative experiments on real data we show how our method clearly outperforms the standard Gaussian filter. Furthermore, we compare its performance to a particle-filter-based tracking method, and observe comparable computational efficiency and improved accuracy and smoothness of the estimates.

##### Abstract (translated by Google)
我们考虑以密集深度图像作为输入的对象的基于模型的3D跟踪的问题。两个困难排除了对这个问题应用标准的高斯滤波器。首先，深度传感器的特点是肥尾测量噪声。为了解决这个问题，我们展示了一个新近发布的用于高斯滤波器的鲁棒化方法可以如何应用于这个问题。因此，我们避免使用启发式异常值检测方法，如果它们与模型不匹配，它们只会拒绝测量。其次，由于高维测量，即深度图像，标准高斯滤波器的计算成本是禁止的。为了解决这个问题，我们提出了一个近似来降低滤波器的计算复杂度。在实际数据的定量实验中，我们展示了我们的方法如何明显优于标准高斯滤波器。此外，我们将其性能与基于粒子滤波器的跟踪方法进行比较，并观察可比较的计算效率，并提高估计的准确性和平滑性。

##### URL
[https://arxiv.org/abs/1602.06157](https://arxiv.org/abs/1602.06157)

##### PDF
[https://arxiv.org/pdf/1602.06157](https://arxiv.org/pdf/1602.06157)

