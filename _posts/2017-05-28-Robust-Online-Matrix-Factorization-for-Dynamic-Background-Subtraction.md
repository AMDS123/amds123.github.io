---
layout: post
title: "Robust Online Matrix Factorization for Dynamic Background Subtraction"
date: 2017-05-28 23:09:29
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Hongwei Yong, Deyu Meng, Wangmeng Zuo, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an effective online background subtraction method, which can be robustly applied to practical videos that have variations in both foreground and background. Different from previous methods which often model the foreground as Gaussian or Laplacian distributions, we model the foreground for each frame with a specific mixture of Gaussians (MoG) distribution, which is updated online frame by frame. Particularly, our MoG model in each frame is regularized by the learned foreground/background knowledge in previous frames. This makes our online MoG model highly robust, stable and adaptive to practical foreground and background variations. The proposed model can be formulated as a concise probabilistic MAP model, which can be readily solved by EM algorithm. We further embed an affine transformation operator into the proposed model, which can be automatically adjusted to fit a wide range of video background transformations and make the method more robust to camera movements. With using the sub-sampling technique, the proposed method can be accelerated to execute more than 250 frames per second on average, meeting the requirement of real-time background subtraction for practical video processing tasks. The superiority of the proposed method is substantiated by extensive experiments implemented on synthetic and real videos, as compared with state-of-the-art online and offline background subtraction methods.

##### Abstract (translated by Google)
我们提出了一种有效的在线背景减法方法，它可以被鲁棒地应用于前景和背景都有变化的实际视频中。不同于往往将前景建模为高斯或拉普拉斯分布的方法，我们使用高斯（MoG）分布的特定混合对每个帧的前景进行建模，其逐帧在线更新。具体来说，我们在每个框架中的MoG模型是通过前面帧中学习到的前景/背景知识来规范化的。这使得我们的在线MoG模型具有高度的稳健性和稳定性，能够适应实际的前景和背景变化。该模型可以表示为一个简洁的概率MAP模型，可以通过EM算法很容易的解决。我们进一步将仿射变换算子嵌入到所提出的模型中，可以自动调整以适应各种各样的视频背景变换，并且使得该方法对于相机移动更稳健。通过使用子采样技术，所提出的方法可以加速平均每秒执行超过250帧，满足实时视频处理任务的实时背景减除的要求。与现有技术的在线和离线背景减法方法相比，所提出的方法的优越性通过在合成和实际视频上实施的大量实验得以证实。

##### URL
[https://arxiv.org/abs/1705.10000](https://arxiv.org/abs/1705.10000)

##### PDF
[https://arxiv.org/pdf/1705.10000](https://arxiv.org/pdf/1705.10000)

