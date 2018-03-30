---
layout: post
title: "On the Importance of Stereo for Accurate Depth Estimation: An Efficient Semi-Supervised Deep Neural Network Approach"
date: 2018-03-26 17:19:40
categories: arXiv_CV
tags: arXiv_CV
author: Nikolai Smolyanskiy, Alexey Kamenev, Stan Birchfield
mathjax: true
---

* content
{:toc}

##### Abstract
We revisit the problem of visual depth estimation in the context of autonomous vehicles. Despite the progress on monocular depth estimation in recent years, we show that the gap between monocular and stereo depth accuracy remains large---a particularly relevant result due to the prevalent reliance upon monocular cameras by vehicles that are expected to be self-driving. We argue that the challenges of removing this gap are significant, owing to fundamental limitations of monocular vision. As a result, we focus our efforts on depth estimation by stereo. We propose a novel semi-supervised learning approach to training a deep stereo neural network, along with a novel architecture containing a machine-learned argmax layer and a custom runtime (that will be shared publicly) that enables a smaller version of our stereo DNN to run on an embedded GPU. Competitive results are shown on the KITTI 2015 stereo dataset. We also evaluate the recent progress of stereo algorithms by measuring the impact upon accuracy of various design criteria.

##### Abstract (translated by Google)
我们在自主车辆的背景下重新审视视觉深度估计问题。尽管近年来在单眼深度估计方面取得了进展，但我们发现单眼和立体视觉深度精度之间的差距仍然很大 - 这是由于普遍依赖预计会自行驾驶的车辆的单眼相机而导致的一个特别相关的结果。我们认为，由于单眼视觉的根本局限性，消除这种差距的挑战是显着的。因此，我们专注于立体声深度估计。我们提出了一种新的半监督学习方法来训练深度立体声神经网络，以及一个包含机器学习argmax层和定制运行时（将公开共享）的新颖架构，使我们的立体声DNN的较小版本能够在嵌入式GPU上运行。竞争结果显示在KITTI 2015立体数据集上。我们还通过测量各种设计标准对精度的影响来评估立体声算法的最新进展。

##### URL
[https://arxiv.org/abs/1803.09719](https://arxiv.org/abs/1803.09719)

##### PDF
[https://arxiv.org/pdf/1803.09719](https://arxiv.org/pdf/1803.09719)

