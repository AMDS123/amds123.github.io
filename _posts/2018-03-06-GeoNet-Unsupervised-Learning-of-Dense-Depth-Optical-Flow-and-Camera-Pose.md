---
layout: post
title: "GeoNet: Unsupervised Learning of Dense Depth, Optical Flow and Camera Pose"
date: 2018-03-06 16:09:21
categories: arXiv_CV
tags: arXiv_CV Prediction Relation
author: Zhichao Yin, Jianping Shi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose GeoNet, a jointly unsupervised learning framework for monocular depth, optical flow and ego-motion estimation from videos. The three components are coupled by the nature of 3D scene geometry, jointly learned by our framework in an end-to-end manner. Specifically, geometric relationships are extracted over the predictions of individual modules and then combined as an image reconstruction loss, reasoning about static and dynamic scene parts separately. Furthermore, we propose an adaptive geometric consistency loss to increase robustness towards outliers and non-Lambertian regions, which resolves occlusions and texture ambiguities effectively. Experimentation on the KITTI driving dataset reveals that our scheme achieves state-of-the-art results in all of the three tasks, performing better than previously unsupervised methods and comparably with supervised ones.

##### Abstract (translated by Google)
我们提出GeoNet，一个联合无监督学习框架，用于单眼深度，视频的光流和自我运动估计。这三个组件通过3D场景几何的本质相结合，由我们的框架以端对端的方式共同学习。具体而言，在各个模块的预测中提取几何关系，然后将其组合为图像重建损失，分别推导静态和动态场景部分。此外，我们提出了自适应几何一致性损失，以增加对异常值和非朗伯区域的鲁棒性，从而有效地解决了遮挡和纹理模糊。对KITTI驾驶数据集的实验表明，我们的方案在所有三项任务中都达到了最新的结果，比之前的无监督方法执行得更好，并与监督方法相比。

##### URL
[http://arxiv.org/abs/1803.02276](http://arxiv.org/abs/1803.02276)

##### PDF
[http://arxiv.org/pdf/1803.02276](http://arxiv.org/pdf/1803.02276)

