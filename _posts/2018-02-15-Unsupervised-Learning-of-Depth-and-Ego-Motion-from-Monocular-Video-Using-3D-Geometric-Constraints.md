---
layout: post
title: "Unsupervised Learning of Depth and Ego-Motion from Monocular Video Using 3D Geometric Constraints"
date: 2018-02-15 13:33:21
categories: arXiv_CV
tags: arXiv_CV
author: Reza Mahjourian, Martin Wicke, Anelia Angelova
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel approach for unsupervised learning of depth and ego-motion from monocular video. Unsupervised learning removes the need for separate supervisory signals (depth or ego-motion ground truth, or multi-view video). Prior work in unsupervised depth learning uses pixel-wise or gradient-based losses, which only consider pixels in small local neighborhoods. Our main contribution is to explicitly consider the inferred 3D geometry of the scene, enforcing consistency of the estimated 3D point clouds and ego-motion across consecutive frames. This is a challenging task and is solved by a novel (approximate) backpropagation algorithm for aligning 3D structures. We combine this novel 3D-based loss with 2D losses based on photometric quality of frame reconstructions using estimated depth and ego-motion from adjacent frames. We also incorporate validity masks to avoid penalizing areas in which no useful information exists. We test our algorithm on the KITTI dataset and on a video dataset captured on an uncalibrated mobile phone camera. Our proposed approach consistently improves depth estimates on both datasets, and outperforms the state-of-the-art for both depth and ego-motion. Because we only require a simple video, learning depth and ego-motion on large and varied datasets becomes possible. We demonstrate this by training on the low quality uncalibrated video dataset and evaluating on KITTI, ranking among top performing prior methods which are trained on KITTI itself.

##### Abstract (translated by Google)
我们提出了一种无监督学习单眼视频的深度和自我运动的新方法。无监督学习不需要单独的监控信号（深度或自我运动地面实况或多视点视频）。无监督深度学习的先前工作使用基于像素或基于梯度的损失，它只考虑小本地邻域中的像素。我们的主要贡献是明确考虑场景的推断三维几何，强化估计的三维点云与连续帧之间的自我运动的一致性。这是一项具有挑战性的任务，并且通过用于对齐3D结构的新颖（近似）反向传播算法来解决。我们将这种新颖的基于3D的损失与基于帧估计的光度质量的2D损失相结合，使用估计的深度和来自相邻帧的自我运动。我们还纳入有效性面具，以避免惩罚没有有用信息的地区。我们在KITTI数据集和未校准的手机摄像头上捕获的视频数据集上测试我们的算法。我们提出的方法不断改善两个数据集的深度估计，并且在深度和自我运动方面均优于最新技术。因为我们只需要一个简单的视频，就可以在大型和各种数据集上学习深度和自我运动。我们通过对低质量未经校准的视频数据集进行培训并对KITTI进行评估来证明这一点，这是KITTI本身训练过的表现最佳的先前方法之一。

##### URL
[https://arxiv.org/abs/1802.05522](https://arxiv.org/abs/1802.05522)

##### PDF
[https://arxiv.org/pdf/1802.05522](https://arxiv.org/pdf/1802.05522)

