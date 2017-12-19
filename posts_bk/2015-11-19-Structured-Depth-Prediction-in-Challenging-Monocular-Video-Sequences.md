---
layout: post
title: "Structured Depth Prediction in Challenging Monocular Video Sequences"
date: 2015-11-19 06:42:45
categories: arXiv_CV
tags: arXiv_CV Optimization Inference Prediction Relation
author: Miaomiao Liu, Mathieu Salzmann, Xuming He
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we tackle the problem of estimating the depth of a scene from a monocular video sequence. In particular, we handle challenging scenarios, such as non-translational camera motion and dynamic scenes, where traditional structure from motion and motion stereo methods do not apply. To this end, we first study the problem of depth estimation from a single image. In this context, we exploit the availability of a pool of images for which the depth is known, and formulate monocular depth estimation as a discrete-continuous optimization problem, where the continuous variables encode the depth of the superpixels in the input image, and the discrete ones represent relationships between neighboring superpixels. The solution to this discrete-continuous optimization problem is obtained by performing inference in a graphical model using particle belief propagation. To handle video sequences, we then extend our single image model to a two-frame one that naturally encodes short-range temporal consistency and inherently handles dynamic objects. Based on the prediction of this model, we then introduce a fully-connected pairwise CRF that accounts for longer range spatio-temporal interactions throughout a video. We demonstrate the effectiveness of our model in both the indoor and outdoor scenarios.

##### Abstract (translated by Google)
在本文中，我们解决了从单眼视频序列估计场景深度的问题。特别是，我们处理具有挑战性的场景，例如非平移相机运动和动态场景，其中来自运动和运动立体方法的传统结构不适用。为此，我们首先从单个图像研究深度估计的问题。在这种情况下，我们利用已知深度的图像池的可用性，并将单目深度估计表示为离散连续优化问题，其中连续变量编码输入图像中超像素的深度，并且离散的表示相邻超级像素之间的关系。通过使用粒子置信传播在图形模型中执行推理来获得这个离散 - 连续优化问题的解决方案。为了处理视频序列，我们将我们的单一图像模型扩展为一个两帧的模型，它自然地编码了短程时间一致性，并固有地处理动态对象。基于这个模型的预测，我们将介绍一个完全连接的成对CRF，这个CRF在整个视频中占据了更长距离的时空交互作用。我们证明了我们的模型在室内和室外场景中的有效性。

##### URL
[https://arxiv.org/abs/1511.06070](https://arxiv.org/abs/1511.06070)

##### PDF
[https://arxiv.org/pdf/1511.06070](https://arxiv.org/pdf/1511.06070)

