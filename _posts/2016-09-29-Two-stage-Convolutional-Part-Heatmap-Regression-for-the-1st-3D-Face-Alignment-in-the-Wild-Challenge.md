---
layout: post
title: "Two-stage Convolutional Part Heatmap Regression for the 1st 3D Face Alignment in the Wild Challenge"
date: 2016-09-29 23:07:01
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Adrian Bulat, Georgios Tzimiropoulos
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes our submission to the 1st 3D Face Alignment in the Wild (3DFAW) Challenge. Our method builds upon the idea of convolutional part heatmap regression [1], extending it for 3D face alignment. Our method decomposes the problem into two parts: (a) X,Y (2D) estimation and (b) Z (depth) estimation. At the first stage, our method estimates the X,Y coordinates of the facial landmarks by producing a set of 2D heatmaps, one for each landmark, using convolutional part heatmap regression. Then, these heatmaps, alongside the input RGB image, are used as input to a very deep subnetwork trained via residual learning for regressing the Z coordinate. Our method ranked 1st in the 3DFAW Challenge, surpassing the second best result by more than 22%.

##### Abstract (translated by Google)
本文介绍了我们提交给第一次3D面部对齐（3DFAW）的挑战。我们的方法建立在卷积零件热图回归的思想上[1]，扩展到3D面对齐。我们的方法将问题分解为两部分：（a）X，Y（2D）估计和（b）Z（深度）估计。在第一阶段，我们的方法通过使用卷积部分热图回归生成一组二维热图，每个地标一个估计面部地标的X，Y坐标。然后，将这些热图与输入的RGB图像一起用作通过残差学习训练的非常深的子网络的输入，用于回归Z坐标。我们的方法在3DFAW挑战赛中名列第一，超过第二名的22％以上。

##### URL
[https://arxiv.org/abs/1609.09545](https://arxiv.org/abs/1609.09545)

##### PDF
[https://arxiv.org/pdf/1609.09545](https://arxiv.org/pdf/1609.09545)

