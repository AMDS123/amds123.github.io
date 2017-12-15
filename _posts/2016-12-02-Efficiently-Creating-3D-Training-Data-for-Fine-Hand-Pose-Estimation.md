---
layout: post
title: "Efficiently Creating 3D Training Data for Fine Hand Pose Estimation"
date: 2016-12-02 15:45:38
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Markus Oberweger, Gernot Riegler, Paul Wohlhart, Vincent Lepetit
mathjax: true
---

* content
{:toc}

##### Abstract
While many recent hand pose estimation methods critically rely on a training set of labelled frames, the creation of such a dataset is a challenging task that has been overlooked so far. As a result, existing datasets are limited to a few sequences and individuals, with limited accuracy, and this prevents these methods from delivering their full potential. We propose a semi-automated method for efficiently and accurately labeling each frame of a hand depth video with the corresponding 3D locations of the joints: The user is asked to provide only an estimate of the 2D reprojections of the visible joints in some reference frames, which are automatically selected to minimize the labeling work by efficiently optimizing a sub-modular loss function. We then exploit spatial, temporal, and appearance constraints to retrieve the full 3D poses of the hand over the complete sequence. We show that this data can be used to train a recent state-of-the-art hand pose estimation method, leading to increased accuracy. The code and dataset can be found on our website this https URL

##### Abstract (translated by Google)
尽管许多最近的手姿态估计方法严格地依赖于标记帧的训练集，但是创建这样的数据集是迄今为止被忽略的具有挑战性的任务。因此，现有的数据集仅限于少数几个序列和个体，准确性有限，这使得这些方法无法充分发挥其潜力。我们提出了一种半自动化的方法，用于有效和精确地标记手深度视频的每个帧和关节的相应3D位置：要求用户只提供一些参考帧中可见关节的二维重新投影的估计值，通过有效地优化子模块化损失功能来自动选择这些标签以最小化贴标签工作。然后，我们利用空间，时间和外观约束来检索完整序列的完整3D手势。我们表明，这个数据可以用来训练最近的最先进的姿态估计方法，从而提高准确性。代码和数据集可以在我们的网站上找到这个https网址

##### URL
[https://arxiv.org/abs/1605.03389](https://arxiv.org/abs/1605.03389)

##### PDF
[https://arxiv.org/pdf/1605.03389](https://arxiv.org/pdf/1605.03389)

