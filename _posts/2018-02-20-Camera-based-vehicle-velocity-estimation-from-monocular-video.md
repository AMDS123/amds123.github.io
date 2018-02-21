---
layout: post
title: "Camera-based vehicle velocity estimation from monocular video"
date: 2018-02-20 12:54:39
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Moritz Kampelm&#xfc;hler, Michael G. M&#xfc;ller, Christoph Feichtenhofer
mathjax: true
---

* content
{:toc}

##### Abstract
This paper documents the winning entry at the CVPR2017 vehicle velocity estimation challenge. Velocity estimation is an emerging task in autonomous driving which has not yet been thoroughly explored. The goal is to estimate the relative velocity of a specific vehicle from a sequence of images. In this paper, we present a light-weight approach for directly regressing vehicle velocities from their trajectories using a multilayer perceptron. Another contribution is an explorative study of features for monocular vehicle velocity estimation. We find that light-weight trajectory based features outperform depth and motion cues extracted from deep ConvNets, especially for far-distance predictions where current disparity and optical flow estimators are challenged significantly. Our light-weight approach is real-time capable on a single CPU and outperforms all competing entries in the velocity estimation challenge. On the test set, we report an average error of 1.12 m/s which is comparable to a (ground-truth) system that combines LiDAR and radar techniques to achieve an error of around 0.71 m/s.

##### Abstract (translated by Google)
本文记录了CVPR2017车速估算挑战中的获胜条目。速度估算是自动驾驶中的一项新兴工作，目前尚未完全探索。目标是从一系列图像中估计特定车辆的相对速度。在本文中，我们提出了一种使用多层感知器从车辆轨迹直接回归车辆速度的轻量级方法。另一个贡献是单眼车辆速度估计的特征的探索性研究。我们发现，基于轻量级轨迹的特征优于深度提取的深度和运动提示，特别是对于当前视差和光流估计器受到严重挑战的远距离预测。我们的轻量级方法在单个CPU上具有实时功能，并且在速度估算挑战中胜过所有竞争条目。在测试集上，我们报告的平均误差为1.12 m / s，这与一个结合LiDAR和雷达技术的（地面实况）系统相当，可以实现约0.71 m / s的误差。

##### URL
[http://arxiv.org/abs/1802.07094](http://arxiv.org/abs/1802.07094)

##### PDF
[http://arxiv.org/pdf/1802.07094](http://arxiv.org/pdf/1802.07094)

