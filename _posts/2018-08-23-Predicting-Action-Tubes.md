---
layout: post
title: "Predicting Action Tubes"
date: 2018-08-23 12:11:06
categories: arXiv_AI
tags: arXiv_AI Classification Prediction Quantitative Detection
author: Gurkirt Singh, Suman Saha, Fabio Cuzzolin
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present a method to predict an entire `action tube' (a set of temporally linked bounding boxes) in a trimmed video just by observing a smaller subset of it. Predicting where an action is going to take place in the near future is essential to many computer vision based applications such as autonomous driving or surgical robotics. Importantly, it has to be done in real-time and in an online fashion. We propose a Tube Prediction network (TPnet) which jointly predicts the past, present and future bounding boxes along with their action classification scores. At test time TPnet is used in a (temporal) sliding window setting, and its predictions are put into a tube estimation framework to construct/predict the video long action tubes not only for the observed part of the video but also for the unobserved part. Additionally, the proposed action tube predictor helps in completing action tubes for unobserved segments of the video. We quantitatively demonstrate the latter ability, and the fact that TPnet improves state-of-the-art detection performance, on one of the standard action detection benchmarks - J-HMDB-21 dataset.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种方法，通过观察它的一个较小的子集，在修剪的视频中预测整个“动作管”（一组时间上相关的边界框）。预测在不久的将来将采取行动的位置对于许多基于计算机视觉的应用（例如自动驾驶或手术机器人）是必不可少的。重要的是，它必须以实时和在线方式完成。我们提出了一个管预测网络（TPnet），它共同预测过去，现在和未来的边界框以及它们的动作分类分数。在测试时，TPnet用于（时间）滑动窗口设置，并且其预测被放入管估计框架中以构建/预测视频长动作管，不仅用于观察到的视频部分而且用于未观察到的部分。此外，建议的动作管预测器有助于完成视频未观察到的片段的动作管。我们在标准动作检测基准--J-HMDB-21数据集之一上定量地展示了后者的能力，以及TPnet提高了最先进的检测性能的事实。

##### URL
[http://arxiv.org/abs/1808.07712](http://arxiv.org/abs/1808.07712)

##### PDF
[http://arxiv.org/pdf/1808.07712](http://arxiv.org/pdf/1808.07712)

