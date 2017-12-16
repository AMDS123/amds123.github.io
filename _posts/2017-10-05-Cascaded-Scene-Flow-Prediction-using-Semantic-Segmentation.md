---
layout: post
title: "Cascaded Scene Flow Prediction using Semantic Segmentation"
date: 2017-10-05 22:52:31
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Semantic_Segmentation Classification Prediction
author: Zhile Ren, Deqing Sun, Jan Kautz, Erik B. Sudderth
mathjax: true
---

* content
{:toc}

##### Abstract
Given two consecutive frames from a pair of stereo cameras, 3D scene flow methods simultaneously estimate the 3D geometry and motion of the observed scene. Many existing approaches use superpixels for regularization, but may predict inconsistent shapes and motions inside rigidly moving objects. We instead assume that scenes consist of foreground objects rigidly moving in front of a static background, and use semantic cues to produce pixel-accurate scene flow estimates. Our cascaded classification framework accurately models 3D scenes by iteratively refining semantic segmentation masks, stereo correspondences, 3D rigid motion estimates, and optical flow fields. We evaluate our method on the challenging KITTI autonomous driving benchmark, and show that accounting for the motion of segmented vehicles leads to state-of-the-art performance.

##### Abstract (translated by Google)
给定来自一对立体相机的两个连续的帧，3D场景流动方法同时估计观察场景的3D几何形状和运动。许多现有的方法使用超像素进行正则化，但是可以预测刚性移动物体内部的不一致的形状和运动。我们假设场景由在静态背景之前刚性移动的前景对象组成，并且使用语义提示来产生像素精确的场景流量估计。我们的级联分类框架通过迭代地改进语义分割掩模，立体对应，3D刚体运动估计和光学流场来精确模拟3D场景。我们对具有挑战性的KITTI自主驾驶基准评估我们的方法，并显示对分段车辆运动的考虑导致了最先进的性能。

##### URL
[https://arxiv.org/abs/1707.08313](https://arxiv.org/abs/1707.08313)

##### PDF
[https://arxiv.org/pdf/1707.08313](https://arxiv.org/pdf/1707.08313)

