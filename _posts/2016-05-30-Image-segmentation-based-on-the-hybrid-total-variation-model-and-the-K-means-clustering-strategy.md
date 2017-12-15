---
layout: post
title: "Image segmentation based on the hybrid total variation model and the K-means clustering strategy"
date: 2016-05-30 06:50:31
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation
author: Baoli Shi, Zhi-Feng Pang, Jing Xu
mathjax: true
---

* content
{:toc}

##### Abstract
The performance of image segmentation highly relies on the original inputting image. When the image is contaminated by some noises or blurs, we can not obtain the efficient segmentation result by using direct segmentation methods. In order to efficiently segment the contaminated image, this paper proposes a two step method based on the hybrid total variation model with a box constraint and the K-means clustering method. In the first step, the hybrid model is based on the weighted convex combination between the total variation functional and the high-order total variation as the regularization term to obtain the original clustering data. In order to deal with non-smooth regularization term, we solve this model by employing the alternating split Bregman method. Then, in the second step, the segmentation can be obtained by thresholding this clustering data into different phases, where the thresholds can be given by using the K-means clustering method. Numerical comparisons show that our proposed model can provide more efficient segmentation results dealing with the noise image and blurring image.

##### Abstract (translated by Google)
图像分割的性能高度依赖于原始的输入图像。当图像被一些噪声或模糊所污染时，我们无法通过直接分割方法获得高效的分割结果。为了有效地分割被污染的图像，本文提出了一种基于箱约束的混合全变分模型和K均值聚类方法的两步法。在第一步中，混合模型基于总变差函数和高阶总变差之间的加权凸组合作为正则化项来获得原始聚类数据。为了处理非光滑的正则化项，我们采用交替分裂Bregman方法来解决这个模型。然后，在第二步中，可以通过将该聚类数据阈值化为不同的相位来获得分割，其中阈值可以通过使用K均值聚类方法给出。数值比较表明，本文提出的模型可以提供更高效的分割结果，处理噪声图像和模糊图像。

##### URL
[https://arxiv.org/abs/1605.09116](https://arxiv.org/abs/1605.09116)

##### PDF
[https://arxiv.org/pdf/1605.09116](https://arxiv.org/pdf/1605.09116)

