---
layout: post
title: "Discrete Potts Model for Generating Superpixels on Noisy Images"
date: 2018-03-20 10:32:55
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization Recognition
author: Ruobing Shen, Xiaoyu Chen, Xiangrui Zheng, Gerhard Reinelt
mathjax: true
---

* content
{:toc}

##### Abstract
Many computer vision applications, such as object recognition and segmentation, increasingly build on superpixels. However, there have been so far few superpixel algorithms that systematically deal with noisy images. We propose to first decompose the image into equal-sized rectangular patches, which also sets the maximum superpixel size. Within each patch, a Potts model for simultaneous segmentation and denoising is applied, that guarantees connected and non-overlapping superpixels and also produces a denoised image. The corresponding optimization problem is formulated as a mixed integer linear program (MILP), and solved by a commercial solver. Extensive experiments on the BSDS500 dataset images with noises are compared with other state-of-the-art superpixel methods. Our method achieves the best result in terms of a combined score (OP) composed of the under-segmentation error, boundary recall and compactness.

##### Abstract (translated by Google)
许多计算机视觉应用，如物体识别和分割，越来越多地建立在超像素上。然而，迄今为止很少有超像素算法系统地处理噪声图像。我们建议首先将图像分解成大小相等的矩形块，并设置最大超像素大小。在每个补丁中，应用了用于同时分割和去噪的Potts模型，这保证了连接和非重叠的超像素，并且还产生了去噪图像。相应的优化问题被表述为混合整数线性规划（MILP），并由商业求解器解决。将带有噪声的BSDS500数据集图像的大量实验与其他最先进的超像素方法进行比较。我们的方法在由分割误差，边界回忆和紧凑性组成的组合分数（OP）方面达到最佳结果。

##### URL
[http://arxiv.org/abs/1803.07351](http://arxiv.org/abs/1803.07351)

##### PDF
[http://arxiv.org/pdf/1803.07351](http://arxiv.org/pdf/1803.07351)

