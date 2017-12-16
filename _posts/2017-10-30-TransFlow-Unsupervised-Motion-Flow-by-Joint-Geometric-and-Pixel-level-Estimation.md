---
layout: post
title: "TransFlow: Unsupervised Motion Flow by Joint Geometric and Pixel-level Estimation"
date: 2017-10-30 09:34:47
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Stefano Alletto, Davide Abati, Simone Calderara, Rita Cucchiara, Luca Rigazio
mathjax: true
---

* content
{:toc}

##### Abstract
We address unsupervised optical flow estimation for ego-centric motion. We argue that optical flow can be cast as a geometrical warping between two successive video frames and devise a deep architecture to estimate such transformation in two stages. First, a dense pixel-level flow is computed with a geometric prior imposing strong spatial constraints. Such prior is typical of driving scenes, where the point of view is coherent with the vehicle motion. We show how such global transformation can be approximated with an homography and how spatial transformer layers can be employed to compute the flow field implied by such transformation. The second stage then refines the prediction feeding a second deeper network. A final reconstruction loss compares the warping of frame X(t) with the subsequent frame X(t+1) and guides both estimates. The model, which we named TransFlow, performs favorably compared to other unsupervised algorithms, and shows better generalization compared to supervised methods with a 3x reduction in error on unseen data.

##### Abstract (translated by Google)
我们针对以自我为中心运动的无监督光流估计。我们认为，光流可以作为两个连续的视频帧之间的几何翘曲，并设计一个深层次的体系结构来估计这个转换分两个阶段。首先，计算一个密集的像素级流，其中几何先前强加空间约束。这种先验是典型的驾驶场景，其视角与车辆运动一致。我们展示了这种全局变换如何用单应矩阵来近似，以及如何利用空间变换器层来计算这种变换所隐含的流场。然后，第二阶段进一步细化预测，进入第二个更深的网络。最终的重建损失将帧X（t）的翘曲与随后的帧X（t + 1）进行比较，并且指导两个估计。与其他无监督算法相比，我们命名为TransFlow的模型性能更好，与未监督的方法相比，显示出更好的泛化能力，对未知数据的误差减少了3倍。

##### URL
[https://arxiv.org/abs/1706.00322](https://arxiv.org/abs/1706.00322)

##### PDF
[https://arxiv.org/e-print/1706.00322](https://arxiv.org/e-print/1706.00322)

