---
layout: post
title: "DF-Net: Unsupervised Joint Learning of Depth and Flow using Cross-Task Consistency"
date: 2018-09-05 17:58:25
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Yuliang Zou, Zelun Luo, Jia-Bin Huang
mathjax: true
---

* content
{:toc}

##### Abstract
We present an unsupervised learning framework for simultaneously training single-view depth prediction and optical flow estimation models using unlabeled video sequences. Existing unsupervised methods often exploit brightness constancy and spatial smoothness priors to train depth or flow models. In this paper, we propose to leverage geometric consistency as additional supervisory signals. Our core idea is that for rigid regions we can use the predicted scene depth and camera motion to synthesize 2D optical flow by backprojecting the induced 3D scene flow. The discrepancy between the rigid flow (from depth prediction and camera motion) and the estimated flow (from optical flow model) allows us to impose a cross-task consistency loss. While all the networks are jointly optimized during training, they can be applied independently at test time. Extensive experiments demonstrate that our depth and flow models compare favorably with state-of-the-art unsupervised methods.

##### Abstract (translated by Google)
我们提出了一种无监督学习框架，用于使用未标记的视频序列同时训练单视图深度预测和光流估计模型。现有的无监督方法通常利用亮度恒定性和空间平滑度先验来训练深度或流动模型。在本文中，我们建议利用几何一致性作为附加的监控信号。我们的核心思想是，对于刚性区域，我们可以使用预测的场景深度和相机运动来通过反投影诱导的3D场景流来合成2D光流。刚性流（来自深度预测和相机运动）与估计流量（来自光流模型）之间的差异使我们能够施加跨任务一致性损失。虽然所有网络在培训期间都是联合优化的，但它们可以在测试时独立应用。大量实验表明，我们的深度和流量模型与最先进的无监督方法相比具有优势。

##### URL
[http://arxiv.org/abs/1809.01649](http://arxiv.org/abs/1809.01649)

##### PDF
[http://arxiv.org/pdf/1809.01649](http://arxiv.org/pdf/1809.01649)

