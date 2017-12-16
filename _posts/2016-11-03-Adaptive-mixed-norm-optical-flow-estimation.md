---
layout: post
title: "Adaptive mixed norm optical flow estimation"
date: 2016-11-03 11:32:46
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge
author: Vania V. Estrela, Matthias O. Franz, Ricardo T. Lopes, G. P. De Araujo
mathjax: true
---

* content
{:toc}

##### Abstract
The pel-recursive computation of 2-D optical flow has been extensively studied in computer vision to estimate motion from image sequences, but it still raises a wealth of issues, such as the treatment of outliers, motion discontinuities and occlusion. It relies on spatio-temporal brightness variations due to motion. Our proposed adaptive regularized approach deals with these issues within a common framework. It relies on the use of a data-driven technique called Mixed Norm (MN) to estimate the best motion vector for a given pixel. In our model, various types of noise can be handled, representing different sources of error. The motion vector estimation takes into consideration local image properties and it results from the minimization of a mixed norm functional with a regularization parameter depending on the kurtosis. This parameter determines the relative importance of the fourth norm and makes the functional convex. The main advantage of the developed procedure is that no knowledge of the noise distribution is necessary. Experiments indicate that this approach provides robust estimates of the optical flow.

##### Abstract (translated by Google)
二维光流的像素递推计算已经在计算机视觉中被广泛研究，以估计来自图像序列的运动，但是它仍然引起诸多问题，诸如异常值的处理，运动不连续性和遮挡。它依赖于运动引起的时空亮度变化。我们提出的适应性正则化方法在一个共同的框架内处理这些问题。它依赖于使用称为混合范数（MN）的数据驱动技术来估计给定像素的最佳运动矢量。在我们的模型中，可以处理各种类型的噪声，代表不同的误差来源。运动矢量估计考虑了局部图像特性，并且其是由具有取决于峰度的正则化参数的混合范数函数的最小化而得到的。这个参数决定了第四范数的相对重要性，并使函数凸起。所开发的程序的主要优点是不需要知道噪声分布。实验表明，这种方法提供了强大的光流估计。

##### URL
[https://arxiv.org/abs/1611.00960](https://arxiv.org/abs/1611.00960)

##### PDF
[https://arxiv.org/pdf/1611.00960](https://arxiv.org/pdf/1611.00960)

