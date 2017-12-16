---
layout: post
title: "Semi-Supervised Deep Learning for Monocular Depth Map Prediction"
date: 2017-05-09 21:58:52
categories: arXiv_CV
tags: arXiv_CV Sparse Deep_Learning Prediction
author: Yevhen Kuznietsov, Jörg Stückler, Bastian Leibe
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised deep learning often suffers from the lack of sufficient training data. Specifically in the context of monocular depth map prediction, it is barely possible to determine dense ground truth depth images in realistic dynamic outdoor environments. When using LiDAR sensors, for instance, noise is present in the distance measurements, the calibration between sensors cannot be perfect, and the measurements are typically much sparser than the camera images. In this paper, we propose a novel approach to depth map prediction from monocular images that learns in a semi-supervised way. While we use sparse ground-truth depth for supervised learning, we also enforce our deep network to produce photoconsistent dense depth maps in a stereo setup using a direct image alignment loss. In experiments we demonstrate superior performance in depth map prediction from single images compared to the state-of-the-art methods.

##### Abstract (translated by Google)
受监督的深度学习常常缺乏足够的训练数据。具体而言，在单目深度图预测的情况下，在现实的动态室外环境中确定密集的地面真实深度图像几乎是不可能的。例如，当使用LiDAR传感器时，距离测量中存在噪声，传感器之间的校准不能完美，测量通常比相机图像稀疏。在本文中，我们提出了一个新的方法来深入地图预测单眼图像学习在半监督的方式。虽然我们使用稀疏的地面真实深度监督学习，我们也执行我们的深层网络产生立体设置使用直接图像对齐损失光子一致密集的深度图。在实验中，我们证明了与最先进的方法相比，单幅图像在深度图预测方面的优越性能。

##### URL
[https://arxiv.org/abs/1702.02706](https://arxiv.org/abs/1702.02706)

##### PDF
[https://arxiv.org/pdf/1702.02706](https://arxiv.org/pdf/1702.02706)

