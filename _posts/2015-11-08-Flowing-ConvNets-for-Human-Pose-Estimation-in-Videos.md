---
layout: post
title: "Flowing ConvNets for Human Pose Estimation in Videos"
date: 2015-11-08 16:52:59
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Prediction
author: Tomas Pfister, James Charles, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
The objective of this work is human pose estimation in videos, where multiple frames are available. We investigate a ConvNet architecture that is able to benefit from temporal context by combining information across the multiple frames using optical flow. To this end we propose a network architecture with the following novelties: (i) a deeper network than previously investigated for regressing heatmaps; (ii) spatial fusion layers that learn an implicit spatial model; (iii) optical flow is used to align heatmap predictions from neighbouring frames; and (iv) a final parametric pooling layer which learns to combine the aligned heatmaps into a pooled confidence map. We show that this architecture outperforms a number of others, including one that uses optical flow solely at the input layers, one that regresses joint coordinates directly, and one that predicts heatmaps without spatial fusion. The new architecture outperforms the state of the art by a large margin on three video pose estimation datasets, including the very challenging Poses in the Wild dataset, and outperforms other deep methods that don't use a graphical model on the single-image FLIC benchmark (and also Chen & Yuille and Tompson et al. in the high precision region).

##### Abstract (translated by Google)
这项工作的目的是在视频的人体姿态估计，其中有多个帧可用。我们研究了一种能够通过使用光流在多个帧中组合信息而从时间上下文获益的ConvNet架构。为此，我们提出了一个具有以下新颖性的网络体系结构：（i）比先前调查的回归热图更深的网络; （ii）学习隐式空间模型的空间融合层; （iii）使用光流来对齐来自相邻帧的热图预测;和（iv）最终参数化池层，其学习将排列的热图组合成汇集的信心图。我们表明，这种架构胜过其他一些，包括一个使用光流单独在输入层，一个直接退化联合坐标，一个预测没有空间融合的热图。新架构在三个视频姿态估计数据集（包括野外数据集中非常具有挑战性的姿势）上大大优于现有技术，并优于其他在单图FLIC基准测试中不使用图形模型的深度方法（以及Chen＆Yuille和Tompson等人在高精度领域）。

##### URL
[https://arxiv.org/abs/1506.02897](https://arxiv.org/abs/1506.02897)

##### PDF
[https://arxiv.org/pdf/1506.02897](https://arxiv.org/pdf/1506.02897)

