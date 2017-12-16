---
layout: post
title: "A simple yet effective baseline for 3d human pose estimation"
date: 2017-08-04 18:36:24
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation CNN Detection
author: Julieta Martinez, Rayat Hossain, Javier Romero, James J. Little
mathjax: true
---

* content
{:toc}

##### Abstract
Following the success of deep convolutional networks, state-of-the-art methods for 3d human pose estimation have focused on deep end-to-end systems that predict 3d joint locations given raw image pixels. Despite their excellent performance, it is often not easy to understand whether their remaining error stems from a limited 2d pose (visual) understanding, or from a failure to map 2d poses into 3-dimensional positions. With the goal of understanding these sources of error, we set out to build a system that given 2d joint locations predicts 3d positions. Much to our surprise, we have found that, with current technology, "lifting" ground truth 2d joint locations to 3d space is a task that can be solved with a remarkably low error rate: a relatively simple deep feed-forward network outperforms the best reported result by about 30\% on Human3.6M, the largest publicly available 3d pose estimation benchmark. Furthermore, training our system on the output of an off-the-shelf state-of-the-art 2d detector (\ie, using images as input) yields state of the art results -- this includes an array of systems that have been trained end-to-end specifically for this task. Our results indicate that a large portion of the error of modern deep 3d pose estimation systems stems from their visual analysis, and suggests directions to further advance the state of the art in 3d human pose estimation.

##### Abstract (translated by Google)
深度卷积网络的成功之后，用于三维人体姿态估计的最先进的方法已经集中在深度端对端系统，该系统预测给定原始图像像素的三维关节位置。尽管他们表现出色，但是他们的剩余错误是否来源于有限的二维姿态（视觉）理解，或者是否无法将二维姿态映射到三维位置，通常并不容易理解。为了理解这些误差来源，我们着手建立一个给定二维联合位置预测三维位置的系统。令我们意外的是，我们发现，利用当前的技术，“提升”地面真实二维联合位置到三维空间是一个可以以非常低的误差率解决的任务：相对简单的深度前馈网络胜过最好的在人类3.6M上报告了大约30％的结果，这是最大的公开可用三维姿态估计基准。此外，在现成的最先进的二维探测器（即，使用图像作为输入）的输出上培训我们的系统产生最先进的结果 - 这包括一系列已经训练有素的端到端专门为此任务。我们的研究结果表明现代深度三维姿态估计系统的大部分误差源于他们的视觉分析，并且提出了进一步推进三维人体姿态估计的技术发展方向的方向。

##### URL
[https://arxiv.org/abs/1705.03098](https://arxiv.org/abs/1705.03098)

##### PDF
[https://arxiv.org/pdf/1705.03098](https://arxiv.org/pdf/1705.03098)

