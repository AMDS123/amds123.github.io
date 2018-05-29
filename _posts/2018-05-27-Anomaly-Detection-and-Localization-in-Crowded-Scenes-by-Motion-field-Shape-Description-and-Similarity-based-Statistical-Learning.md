---
layout: post
title: "Anomaly Detection and Localization in Crowded Scenes by Motion-field Shape Description and Similarity-based Statistical Learning"
date: 2018-05-27 13:16:40
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Detection
author: Xinfeng Zhang, Su Yang, Xinjian Zhang, Weishan Zhang, Jiulong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In crowded scenes, detection and localization of abnormal behaviors is challenging in that high-density people make object segmentation and tracking extremely difficult. We associate the optical flows of multiple frames to capture short-term trajectories and introduce the histogram-based shape descriptor referred to as shape contexts to describe such short-term trajectories. Furthermore, we propose a K-NN similarity-based statistical model to detect anomalies over time and space, which is an unsupervised one-class learning algorithm requiring no clustering nor any prior assumption. Firstly, we retrieve the K-NN samples from the training set in regard to the testing sample, and then use the similarities between every pair of the K-NN samples to construct a Gaussian model. Finally, the probabilities of the similarities from the testing sample to the K-NN samples under the Gaussian model are calculated in the form of a joint probability. Abnormal events can be detected by judging whether the joint probability is below predefined thresholds in terms of time and space, separately. Such a scheme can adapt to the whole scene, since the probability computed as such is not affected by motion distortions arising from perspective distortion. We conduct experiments on real-world surveillance videos, and the results demonstrate that the proposed method can reliably detect and locate the abnormal events in the video sequences, outperforming the state-of-the-art approaches.

##### Abstract (translated by Google)
在拥挤的场景中，异常行为的检测和定位具有挑战性，因为高密度人群使得对象分割和跟踪极其困难。我们将多个帧的光流联系起来以获取短期轨迹，并引入基于直方图的形状描述符（称为形状上下文）来描述这种短期轨迹。此外，我们提出了一种基于K-NN相似度的统计模型来检测时间和空间的异常情况，这是一种无监督的单类学习算法，不需要任何聚类，也不需要任何先验假设。首先，从训练集中检索关于测试样本的K-NN样本，然后使用每对K-NN样本之间的相似性来构建高斯模型。最后，以联合概率的形式计算高斯模型下测试样本与K-NN样本相似度的概率。通过判断联合概率是否在时间和空间方面分别低于预定义的阈值来检测异常事件。这样的方案可以适应整个场景，因为这样计算的概率不受由透视失真引起的运动失真的影响。我们对现实世界的监控视频进行了实验，结果表明，所提出的方法能够可靠地检测和定位视频序列中的异常事件，超越了当前最先进的方法。

##### URL
[http://arxiv.org/abs/1805.10620](http://arxiv.org/abs/1805.10620)

##### PDF
[http://arxiv.org/pdf/1805.10620](http://arxiv.org/pdf/1805.10620)

