---
layout: post
title: "Head Pose Estimation of Occluded Faces using Regularized Regression"
date: 2016-02-02 16:27:18
categories: arXiv_CV
tags: arXiv_CV Regularization Face Pose_Estimation Classification
author: Amit Kumar, Rishabh Bindal, Soumya Indela, Michael Rotkowitz
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents regression methods for estimation of head pose from occluded 2-D face images. The process primarily involves reconstructing a face from its occluded image, followed by classification. Typical methods for reconstruction assume that the pixel errors of the occluded regions are independent. However, such an assumption is not true in the case of occlusion, because of its inherent contiguous nature. Hence, we use nuclear norm as a metric that can describe well the structure of the error. We also use LASSO Regression based l1 - regularization to improve reconstruction. Next, we implement Nuclear Norm Regularized Regression (NR), and also our proposed method, for reconstruction and subsequent classification. Finally, we compare the performance of the methods in terms of accuracy of head pose estimation of occluded faces.

##### Abstract (translated by Google)
本文提出了从被遮挡的二维人脸图像估计头部姿态的回归方法。这个过程主要涉及从被遮挡的图像重建一张脸，然后进行分类。典型的重建方法假设遮挡区域的像素误差是独立的。然而，这种假设在遮挡的情况下是不正确的，因为它具有固有的连续性。因此，我们使用核范数作为一个度量标准，可以很好地描述错误的结构。我们还使用基于LASSO回归的l1  - 正则化来改善重建。接下来，我们实施核范数正则回归（NR），以及我们提出的方法，用于重建和随后的分类。最后，我们比较了方法在遮挡人脸头部姿态估计精度方面的性能。

##### URL
[https://arxiv.org/abs/1602.00997](https://arxiv.org/abs/1602.00997)

##### PDF
[https://arxiv.org/pdf/1602.00997](https://arxiv.org/pdf/1602.00997)

