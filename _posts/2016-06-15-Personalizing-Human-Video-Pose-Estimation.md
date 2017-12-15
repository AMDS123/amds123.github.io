---
layout: post
title: "Personalizing Human Video Pose Estimation"
date: 2016-06-15 11:05:05
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: James Charles, Tomas Pfister, Derek Magee, David Hogg, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a personalized ConvNet pose estimator that automatically adapts itself to the uniqueness of a person's appearance to improve pose estimation in long videos. We make the following contributions: (i) we show that given a few high-precision pose annotations, e.g. from a generic ConvNet pose estimator, additional annotations can be generated throughout the video using a combination of image-based matching for temporally distant frames, and dense optical flow for temporally local frames; (ii) we develop an occlusion aware self-evaluation model that is able to automatically select the high-quality and reject the erroneous additional annotations; and (iii) we demonstrate that these high-quality annotations can be used to fine-tune a ConvNet pose estimator and thereby personalize it to lock on to key discriminative features of the person's appearance. The outcome is a substantial improvement in the pose estimates for the target video using the personalized ConvNet compared to the original generic ConvNet. Our method outperforms the state of the art (including top ConvNet methods) by a large margin on two standard benchmarks, as well as on a new challenging YouTube video dataset. Furthermore, we show that training from the automatically generated annotations can be used to improve the performance of a generic ConvNet on other benchmarks.

##### Abstract (translated by Google)
我们提出了一个个性化的ConvNet姿势估计器，它自动适应一个人的外观的独特性，以改善长视频中的姿态估计。我们做出以下贡献：（i）我们表明，给定一些高精度姿态注释，例如从通用的ConvNet姿态估计器，可以使用时间上遥远的帧的基于图像的匹配和时间上局部帧的密集光流的组合来在整个视频中生成额外的注释; （ii）我们开发了一个遮挡感知自我评估模型，能够自动选择高质量并拒绝错误的附加注释; （iii）我们证明这些高质量的注释可以用来微调ConvNet姿态估计器，从而将其个性化以锁定人的外观的关键区分特征。与最初的通用ConvNet相比，使用个性化ConvNet的目标视频的姿态估计的结果是显着的改进。我们的方法在两个标准基准上以及新的具有挑战性的YouTube视频数据集上大大优于现有技术（包括顶级ConvNet方法）。此外，我们表明，从自动生成的注释培训可以用来改善其他基准上的通用ConvNet的性能。

##### URL
[https://arxiv.org/abs/1511.06676](https://arxiv.org/abs/1511.06676)

##### PDF
[https://arxiv.org/pdf/1511.06676](https://arxiv.org/pdf/1511.06676)

