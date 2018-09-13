---
layout: post
title: "Learning structure-from-motionfrom motion"
date: 2018-09-12 14:10:35
categories: arXiv_CV
tags: arXiv_CV Inference Prediction
author: Cl&#xe9;ment Pinard, Laure Chevalley, Antoine Manzanera, David Filliat
mathjax: true
---

* content
{:toc}

##### Abstract
This work is based on a questioning of the quality metrics used by deep neural networks performing depth prediction from a single image, and then of the usability of recently published works on unsupervised learning of depth from videos. To overcome their limitations, we propose to learn in the same unsupervised manner a depth map inference system from monocular videos that takes a pair of images as input. This algorithm actually learns structure-from-motion from motion, and not only structure from context appearance. The scale factor issue is explicitly treated, and the absolute depth map can be estimated from camera displacement magnitude, which can be easily measured from cheap external sensors. Our solution is also much more robust with respect to domain variation and adaptation via fine tuning, because it does not rely entirely in depth from context. Two use cases are considered, unstabilized moving camera videos, and stabilized ones. This choice is motivated by the UAV (for Unmanned Aerial Vehicle) use case that generally provides reliable orientation measurement. We provide a set of experiments showing that, used in real conditions where only speed can be known, our network outperforms competitors for most depth quality measures. Results are given on the well known KITTI dataset, which provides robust stabilization for our second use case, but also contains moving scenes which are very typical of the in-car road context. We then present results on a synthetic dataset that we believe to be more representative of typical UAV scenes. Lastly, we present two domain adaptation use cases showing superior robustness of our method compared to single view depth algorithms, which indicates that it is better suited for highly variable visual contexts.

##### Abstract (translated by Google)
这项工作基于对深度神经网络从单个图像执行深度预测所使用的质量度量的质疑，以及最近发表的关于视频深度无监督学习的工作的可用性。为了克服它们的局限性，我们建议以相同的无监督方式学习单眼视频的深度图推理系统，该系统将一对图像作为输入。该算法实际上从运动中学习运动结构，而不仅仅从上下文外观中学习结构。明确地处理了比例因子问题，并且可以根据相机位移幅度来估计绝对深度图，其可以从便宜的外部传感器容易地测量。我们的解决方案在域变化和通过微调的适应方面也更加强大，因为它不完全依赖于上下文。考虑两个用例，不稳定的移动摄像机视频和稳定的视频。这种选择是由无人机（用于无人驾驶飞行器）的用例推动的，该用例通常提供可靠的定向测量。我们提供了一组实验，表明，在只能知道速度的真实条件下，我们的网络在大多数深度质量测量方面都优于竞争对手。结果在众所周知的KITTI数据集上给出，该数据集为我们的第二个用例提供稳健的稳定性，但也包含非常典型的车内道路环境的移动场景。然后，我们在合成数据集上呈现结果，我们认为这些数据集更能代表典型的无人机场景。最后，我们提出了两个域自适应用例，与单视图深度算法相比，我们的方法具有更强的鲁棒性，这表明它更适合于高度可变的视觉上下文。

##### URL
[http://arxiv.org/abs/1809.04471](http://arxiv.org/abs/1809.04471)

##### PDF
[http://arxiv.org/pdf/1809.04471](http://arxiv.org/pdf/1809.04471)

