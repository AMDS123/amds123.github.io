---
layout: post
title: "Objects Localisation from Motion with Constraints"
date: 2018-03-28 09:14:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Paul Gay, Alessio Del Bue
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method to estimate the 3D object position and occupancy given a set of object detections in multiple images and calibrated cameras. This problem is modelled as the estimation of a set of quadrics given 2D conics fit to the object bounding boxes. Although a closed form solution has been recently proposed, the resulting quadrics can be inaccurate or even be non valid ellipsoids in presence of noisy and inaccurate detections. This effect is especially important in case of small baselines, resulting in dramatic failures. To cope with this problem, we propose a set of linear constraints by matching the centres of the reprojected quadrics with the centres of the observed conics. These constraints can be solved with a linear system thus providing a more computationally efficient solution with respect to a non-linear alternative. Experiments on real data show that the proposed approach improves significantly the accuracy and the validity of the ellipsoids.

##### Abstract (translated by Google)
本文介绍了一种方法来估计三维物体的位置和占用情况，给出一组对象在多幅图像和校准摄像机中的检测结果。这个问题被模拟为给定二维圆锥曲线拟合到对象边界框的一组二次曲面的估计。尽管最近已经提出了一种封闭形式的解决方案，但是由于检测到噪声和不准确，所产生的二次曲线可能不准确，甚至可能是无效的椭球。如果基线较小，这种影响尤其重要，导致严重故障。为了解决这个问题，我们通过将重投影二次曲面的中心与观察到的曲面的中心进行匹配来提出一组线性约束。这些约束可以用线性系统来解决，从而提供关于非线性替代方案的更高计算效率的解决方案。实际数据实验表明，该方法显着提高了椭球的精度和有效性。

##### URL
[https://arxiv.org/abs/1803.10474](https://arxiv.org/abs/1803.10474)

##### PDF
[https://arxiv.org/pdf/1803.10474](https://arxiv.org/pdf/1803.10474)

