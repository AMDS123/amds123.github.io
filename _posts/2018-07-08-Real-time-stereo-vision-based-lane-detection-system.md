---
layout: post
title: "Real-time stereo vision-based lane detection system"
date: 2018-07-08 04:21:28
categories: arXiv_CV
tags: arXiv_CV Face Detection
author: Rui Fan, Naim Dahnoun
mathjax: true
---

* content
{:toc}

##### Abstract
The detection of multiple curved lane markings on a non-flat road surface is still a challenging task for automotive applications. To make an improvement, the depth information can be used to greatly enhance the robustness of the lane detection systems. The proposed system in this paper is developed from our previous work where the dense vanishing point Vp is estimated globally to assist the detection of multiple curved lane markings. However, the outliers in the optimal solution may severely affect the accuracy of the least squares fitting when estimating Vp. Therefore, in this paper we use Random Sample Consensus to update the inliers and outliers iteratively until the fraction of the number of inliers versus the total number exceeds our pre-set threshold. This significantly helps the system to overcome some suddenly changing conditions. Furthermore, we propose a novel lane position validation approach which provides a piecewise weight based on Vp and the gradient to reduce the gradient magnitude of the non-lane candidates. Then, we compute the energy of each possible solution and select all satisfying lane positions for visualisation. The proposed system is implemented on a heterogeneous system which consists of an Intel Core i7-4720HQ CPU and a NVIDIA GTX 970M GPU. A processing speed of 143 fps has been achieved, which is over 38 times faster than our previous work. Also, in order to evaluate the detection precision, we tested 2495 frames with 5361 lanes from the KITTI database (1637 lanes more than our previous experiment). It is shown that the overall successful detection rate is improved from 98.7% to 99.5%.

##### Abstract (translated by Google)
在非平坦路面上检测多个弯曲车道标记对于汽车应用来说仍然是一项具有挑战性的任务。为了进行改进，深度信息可用于极大地增强车道检测系统的鲁棒性。本文提出的系统是从我们以前的工作开发的，其中全局估计密集消失点Vp，以帮助检测多个弯曲车道标记。然而，在估计Vp时，最优解中的异常值可能严重影响最小二乘拟合的精度。因此，在本文中，我们使用随机样本共识来迭代地更新内点和异常值，直到内部数量与总数的比例超过我们的预设阈值。这显着有助于系统克服一些突然变化的条件。此外，我们提出了一种新颖的车道位置验证方法，该方法基于Vp和梯度提供分段权重以减小非车道候选者的梯度大小。然后，我们计算每种可能解决方案的能量，并选择所有令人满意的车道位置以进行可视化。所提出的系统在异构系统上实现，该系统由Intel Core i7-4720HQ CPU和NVIDIA GTX 970M GPU组成。处理速度达到143 fps，比以前的工作速度快38倍。此外，为了评估检测精度，我们使用来自KITTI数据库的5361个泳道测试了2495个帧（比我们之前的实验多1637个泳道）。结果表明，总体成功检测率从98.7％提高到99.5％。

##### URL
[http://arxiv.org/abs/1807.02752](http://arxiv.org/abs/1807.02752)

##### PDF
[http://arxiv.org/pdf/1807.02752](http://arxiv.org/pdf/1807.02752)

