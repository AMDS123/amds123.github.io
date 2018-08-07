---
layout: post
title: "DeepTAM: Deep Tracking and Mapping"
date: 2018-08-06 13:43:31
categories: arXiv_CV
tags: arXiv_CV Tracking Deep_Learning Prediction
author: Huizhong Zhou, Benjamin Ummenhofer, Thomas Brox
mathjax: true
---

* content
{:toc}

##### Abstract
We present a system for keyframe-based dense camera tracking and depth map estimation that is entirely learned. For tracking, we estimate small pose increments between the current camera image and a synthetic viewpoint. This significantly simplifies the learning problem and alleviates the dataset bias for camera motions. Further, we show that generating a large number of pose hypotheses leads to more accurate predictions. For mapping, we accumulate information in a cost volume centered at the current depth estimate. The mapping network then combines the cost volume and the keyframe image to update the depth prediction, thereby effectively making use of depth measurements and image-based priors. Our approach yields state-of-the-art results with few images and is robust with respect to noisy camera poses. We demonstrate that the performance of our 6 DOF tracking competes with RGB-D tracking algorithms. We compare favorably against strong classic and deep learning powered dense depth algorithms.

##### Abstract (translated by Google)
我们提出了一个完全学习的基于关键帧的密集相机跟踪和深度图估计的系统。对于跟踪，我们估计当前相机图像和合成视点之间的小姿势增量。这显着简化了学习问题并减轻了相机运动的数据集偏差。此外，我们表明，生成大量的姿势假设可以产生更准确的预测。对于映射，我们在以当前深度估计为中心的成本量中累积信息。然后，映射网络组合成本量和关键帧图像以更新深度预测，从而有效地利用深度测量和基于图像的先验。我们的方法使用很少的图像产生最先进的结果，并且对于嘈杂的相机姿势而言是稳健的。我们证明了我们的6自由度跟踪的性能与RGB-D跟踪算法竞争。我们比较强大的经典和深度学习驱动的密集深度算法。

##### URL
[https://arxiv.org/abs/1808.01900](https://arxiv.org/abs/1808.01900)

##### PDF
[https://arxiv.org/pdf/1808.01900](https://arxiv.org/pdf/1808.01900)

