---
layout: post
title: "Human Pose Estimation using Deep Consensus Voting"
date: 2016-03-27 12:45:33
categories: arXiv_CV
tags: arXiv_CV Sparse Pose_Estimation CNN Prediction
author: Ita Lifshitz, Ethan Fetaya, Shimon Ullman
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we consider the problem of human pose estimation from a single still image. We propose a novel approach where each location in the image votes for the position of each keypoint using a convolutional neural net. The voting scheme allows us to utilize information from the whole image, rather than rely on a sparse set of keypoint locations. Using dense, multi-target votes, not only produces good keypoint predictions, but also enables us to compute image-dependent joint keypoint probabilities by looking at consensus voting. This differs from most previous methods where joint probabilities are learned from relative keypoint locations and are independent of the image. We finally combine the keypoints votes and joint probabilities in order to identify the optimal pose configuration. We show our competitive performance on the MPII Human Pose and Leeds Sports Pose datasets.

##### Abstract (translated by Google)
在本文中，我们考虑来自单个静止图像的人体姿态估计的问题。我们提出了一个新颖的方法，其中图像中的每个位置使用卷积神经网络投票每个关键点的位置。投票计划允许我们利用整个图像中的信息，而不是依赖于一组稀疏的关键点位置。使用密集的多目标投票，不仅可以产生良好的关键点预测，还可以通过查看共识投票来计算依赖于图像的联合关键点概率。这与大多数以前的方法不同，在这些方法中，从相对关键点位置学习联合概率，并独立于图像。我们最后结合关键点投票和联合概率，以确定最佳的姿势配置。我们展示了我们在MPII人体姿势和利兹运动姿势数据集上的竞争表现。

##### URL
[https://arxiv.org/abs/1603.08212](https://arxiv.org/abs/1603.08212)

##### PDF
[https://arxiv.org/pdf/1603.08212](https://arxiv.org/pdf/1603.08212)

