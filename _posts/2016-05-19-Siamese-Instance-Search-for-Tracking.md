---
layout: post
title: "Siamese Instance Search for Tracking"
date: 2016-05-19 09:24:40
categories: arXiv_CV
tags: arXiv_CV Re-identification Tracking Detection
author: Ran Tao, Efstratios Gavves, Arnold W.M. Smeulders
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a tracker, which is radically different from state-of-the-art trackers: we apply no model updating, no occlusion detection, no combination of trackers, no geometric matching, and still deliver state-of-the-art tracking performance, as demonstrated on the popular online tracking benchmark (OTB) and six very challenging YouTube videos. The presented tracker simply matches the initial patch of the target in the first frame with candidates in a new frame and returns the most similar patch by a learned matching function. The strength of the matching function comes from being extensively trained generically, i.e., without any data of the target, using a Siamese deep neural network, which we design for tracking. Once learned, the matching function is used as is, without any adapting, to track previously unseen targets. It turns out that the learned matching function is so powerful that a simple tracker built upon it, coined Siamese INstance search Tracker, SINT, which only uses the original observation of the target from the first frame, suffices to reach state-of-the-art performance. Further, we show the proposed tracker even allows for target re-identification after the target was absent for a complete video shot.

##### Abstract (translated by Google)
在本文中，我们介绍一种跟踪器，它与最先进的跟踪器完全不同：我们不使用模型更新，没有遮挡检测，没有跟踪器的组合，没有几何匹配，仍然提供最先进的跟踪器。艺术跟踪表现，如流行的在线跟踪基准（OTB）和六个非常具有挑战性的YouTube视频所示。所呈现的跟踪器简单地将第一帧中的目标的初始片与新帧中的候选匹配，并且通过学习的匹配函数返回最相似的片。匹配函数的强度来自广泛的广泛训练，即没有任何目标数据，使用我们设计用于跟踪的Siamese深层神经网络。一旦学习完毕，匹配功能可以按原样使用，无需任何调整，即可跟踪以前看不见的目标。事实证明，学习到的匹配函数是如此强大以至于一个简单的跟踪器建立在它之上，创造了仅仅使用从第一帧的目标的原始观察的连体实例搜索跟踪器（SINT），足以达到最先进的，艺术表演。此外，我们展示了所提出的跟踪器甚至允许在完成视频拍摄目标缺席之后的目标重新识别。

##### URL
[https://arxiv.org/abs/1605.05863](https://arxiv.org/abs/1605.05863)

##### PDF
[https://arxiv.org/pdf/1605.05863](https://arxiv.org/pdf/1605.05863)

