---
layout: post
title: "Joint direct estimation of 3D geometry and 3D motion using spatio temporal gradients"
date: 2018-05-17 07:54:24
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Francisco Barranco, Cornelia Ferm&#xfc;ller, Yiannis Aloimonos, Eduardo Ros
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional image motion based structure from motion methods first compute optical flow, then solve for the 3D motion parameters based on the epipolar constraint, and finally recover the 3D geometry of the scene. However, errors in optical flow due to regularization can lead to large errors in 3D motion and structure. This paper investigates whether performance and consistency can be improved by avoiding optical flow estimation in the early stages of the structure from motion pipeline, and it proposes a new direct method based on image gradients (normal flow) only. The main idea lies in a reformulation of the positive-depth constraint, which allows the use of well-known minimization techniques to solve for 3D motion. The 3D motion estimate is then refined and structure estimated adding a regularization based on depth. Experimental comparisons on standard synthetic datasets and the real-world driving benchmark dataset KITTI using three different optic flow algorithms show that the method achieves better accuracy in all but one case. Furthermore, it outperforms existing normal flow based 3D motion estimation techniques. Finally, the recovered 3D geometry is shown to be also very accurate.

##### Abstract (translated by Google)
传统的基于运动方法的图像运动结构首先计算光流，然后基于极线约束求解三维运动参数，最终恢复场景的三维几何。然而，由于正则化造成的光流误差可能导致3D运动和结构中的较大误差。本文研究是否可以通过避免运动流水线结构早期光流估计来提高性能和一致性，并提出一种仅基于图像梯度（正常流）的新的直接方法。其主要思想在于正深度约束的重新表达，其允许使用众所周知的最小化技术来解决3D运动。然后对三维运动估计进行细化和结构估计，并根据深度添加正则化。使用三种不同的光流算法对标准合成数据集和实际驱动基准数据集KITTI进行实验比较表明，除一种情况外，该方法在所有情况下均可获得更好的精确度。此外，它优于现有的基于正常流量的3D运动估计技术。最后，显示恢复的3D几何图形也非常精确。

##### URL
[http://arxiv.org/abs/1805.06641](http://arxiv.org/abs/1805.06641)

##### PDF
[http://arxiv.org/pdf/1805.06641](http://arxiv.org/pdf/1805.06641)

