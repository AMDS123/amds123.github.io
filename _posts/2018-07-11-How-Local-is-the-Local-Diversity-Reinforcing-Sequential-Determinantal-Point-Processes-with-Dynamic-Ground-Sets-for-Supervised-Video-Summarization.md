---
layout: post
title: "How Local is the Local Diversity? Reinforcing Sequential Determinantal Point Processes with Dynamic Ground Sets for Supervised Video Summarization"
date: 2018-07-11 15:59:49
categories: arXiv_CV
tags: arXiv_CV Summarization Reinforcement_Learning
author: Yandong Li, liqiang Wang, Tianbao Yang, Boqing Gong
mathjax: true
---

* content
{:toc}

##### Abstract
The large volume of video content and high viewing frequency demand automatic video summarization algorithms, of which a key property is the capability of modeling diversity. If videos are lengthy like hours-long egocentric videos, it is necessary to track the temporal structures of the videos and enforce local diversity. The local diversity refers to that the shots selected from a short time duration are diverse but visually similar shots are allowed to co-exist in the summary if they appear far apart in the video. In this paper, we propose a novel probabilistic model, built upon SeqDPP, to dynamically control the time span of a video segment upon which the local diversity is imposed. In particular, we enable SeqDPP to learn to automatically infer how local the local diversity is supposed to be from the input video. The resulting model is extremely involved to train by the hallmark maximum likelihood estimation (MLE), which further suffers from the exposure bias and non-differentiable evaluation metrics. To tackle these problems, we instead devise a reinforcement learning algorithm for training the proposed model. Extensive experiments verify the advantages of our model and the new learning algorithm over MLE-based methods.

##### Abstract (translated by Google)
大量的视频内容和高观看频率需要自动视频摘要算法，其关键属性是建模多样性的能力。如果视频像长达数小时的自我中心视频一样冗长，则有必要跟踪视频的时间结构并强制执行本地多样性。本地多样性指的是从短时间段选择的镜头是多种多样的，但是如果它们在视频中看起来相距很远，则允许视觉上类似的镜头在摘要中共存。在本文中，我们提出了一种基于SeqDPP的新概率模型，用于动态控制视频片段的时间跨度，在该视频片段上施加局部多样性。特别是，我们使SeqDPP能够学习如何从输入视频中自动推断本地多样性应该是多么本地化。由此产生的模型极其涉及通过标记最大似然估计（MLE）进行训练，其进一步受到暴露偏差和不可微分的评估指标的影响。为了解决这些问题，我们设计了一种强化学习算法来训练所提出的模型。大量实验验证了我们的模型和新学习算法优于基于MLE的方法的优势。

##### URL
[http://arxiv.org/abs/1807.04219](http://arxiv.org/abs/1807.04219)

##### PDF
[http://arxiv.org/pdf/1807.04219](http://arxiv.org/pdf/1807.04219)

