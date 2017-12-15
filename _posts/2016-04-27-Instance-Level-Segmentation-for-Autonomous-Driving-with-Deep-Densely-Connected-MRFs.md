---
layout: post
title: "Instance-Level Segmentation for Autonomous Driving with Deep Densely Connected MRFs"
date: 2016-04-27 00:37:05
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Inference Prediction
author: Ziyu Zhang, Sanja Fidler, Raquel Urtasun
mathjax: true
---

* content
{:toc}

##### Abstract
Our aim is to provide a pixel-wise instance-level labeling of a monocular image in the context of autonomous driving. We build on recent work [Zhang et al., ICCV15] that trained a convolutional neural net to predict instance labeling in local image patches, extracted exhaustively in a stride from an image. A simple Markov random field model using several heuristics was then proposed in [Zhang et al., ICCV15] to derive a globally consistent instance labeling of the image. In this paper, we formulate the global labeling problem with a novel densely connected Markov random field and show how to encode various intuitive potentials in a way that is amenable to efficient mean field inference [Kr\"ahenb\"uhl et al., NIPS11]. Our potentials encode the compatibility between the global labeling and the patch-level predictions, contrast-sensitive smoothness as well as the fact that separate regions form different instances. Our experiments on the challenging KITTI benchmark [Geiger et al., CVPR12] demonstrate that our method achieves a significant performance boost over the baseline [Zhang et al., ICCV15].

##### Abstract (translated by Google)
我们的目标是在自主驾驶环境中提供单眼图像的像素级实例级标签。我们建立在最近的工作[张等人，ICCV15]，训练一个卷积神经网络预测实例标签在局部图像补丁，从图像的步幅穷举提取。然后在[Zhang等人，ICCV15]中提出了使用多种启发式的简单马尔可夫随机场模型以导出图像的全局一致实例标记。在本文中，我们用一个新的密集连接的马尔可夫随机场来制定全局标记问题，并展示如何以适合于有效的平均场推断的方式来编码各种直觉电位[Kr \'ahenb \'uhl等人，NIPS11 ]。我们的潜力编码了全局标签和补丁级预测之间的兼容性，对比度敏感的平滑性以及单独区域形成不同实例的事实。我们在具有挑战性的KITTI基准[Geiger等人，CVPR12]上的实验证明，我们的方法在基线上获得显着的性能提升[Zhang等人，ICCV15]。

##### URL
[https://arxiv.org/abs/1512.06735](https://arxiv.org/abs/1512.06735)

##### PDF
[https://arxiv.org/pdf/1512.06735](https://arxiv.org/pdf/1512.06735)

