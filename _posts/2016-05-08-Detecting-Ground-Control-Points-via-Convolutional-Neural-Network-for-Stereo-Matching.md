---
layout: post
title: "Detecting Ground Control Points via Convolutional Neural Network for Stereo Matching"
date: 2016-05-08 07:38:40
categories: arXiv_CV
tags: arXiv_CV Semi_Global CNN Optimization
author: Zhun Zhong, Songzhi Su, Donglin Cao, Shaozi Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel approach to detect ground control points (GCPs) for stereo matching problem. First of all, we train a convolutional neural network (CNN) on a large stereo set, and compute the matching confidence of each pixel by using the trained CNN model. Secondly, we present a ground control points selection scheme according to the maximum matching confidence of each pixel. Finally, the selected GCPs are used to refine the matching costs, and we apply the new matching costs to perform optimization with semi-global matching algorithm for improving the final disparity maps. We evaluate our approach on the KITTI 2012 stereo benchmark dataset. Our experiments show that the proposed approach significantly improves the accuracy of disparity maps.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的方法来检测地面控制点（GCPs）的立体匹配问题。首先，我们在一个大的立体声集上训练一个卷积神经网络（CNN），并使用训练的CNN模型计算每个像素的匹配置信度。其次，根据每个像素的最大匹配置信度给出一个地面控制点选择方案。最后，选取的GCP用于优化匹配成本，并将新的匹配成本应用于半全局匹配算法优化，以改善最终视差图。我们在KITTI 2012立体基准数据集上评估我们的方法。我们的实验表明，提出的方法显着提高了视差图的准确性。

##### URL
[https://arxiv.org/abs/1605.02289](https://arxiv.org/abs/1605.02289)

##### PDF
[https://arxiv.org/pdf/1605.02289](https://arxiv.org/pdf/1605.02289)

