---
layout: post
title: "Meta-Tracker: Fast and Robust Online Adaptation for Visual Object Trackers"
date: 2018-01-09 17:38:10
categories: arXiv_CV
tags: arXiv_CV Tracking Deep_Learning Detection Relation
author: Eunbyung Park, Alexander C. Berg
mathjax: true
---

* content
{:toc}

##### Abstract
This paper improves state-of-the-art on-line trackers that use deep learning. Such trackers train a deep network to pick a specified object out from the background in an initial frame (initialization) and then keep training the model as tracking proceeds (updates). Our core contribution is a meta-learning-based method to adjust deep networks for tracking using off-line training. First, we learn initial parameters and per-parameter coefficients for fast online adaptation. Second, we use training signal from future frames for robustness to target appearance variations and environment changes. The resulting networks train significantly faster during the initialization, while improving robustness and accuracy. We demonstrate this approach on top of the current highest accuracy tracking approach, tracking-by-detection based MDNet and close competitor, the correlation-based CREST. Experimental results on both standard benchmarks, OTB and VOT2016, show improvements in speed, accuracy, and robustness on both trackers.

##### Abstract (translated by Google)
本文改进了使用深度学习的最先进的在线跟踪器。这种跟踪器训练一个深层网络，在初始帧（初始化）中从背景中选出一个指定的对象，然后在跟踪继续（更新）时继续训练模型。我们的核心贡献是一种基于元学习的方法来调整使用离线训练进行跟踪的深度网络。首先，我们学习初始参数和每个参数系数以实现快速在线适应。其次，我们使用来自未来帧的训练信号来保持鲁棒性，以便目标外观变化和环境变化。生成的网络在初始化过程中训练速度明显加快，同时提高了鲁棒性和准确性。我们在目前最高的准确性跟踪方法，基于跟踪的MDNet和紧密的竞争对手（基于相关的CREST）之上展示了这种方法。标准基准OTB和VOT2016的实验结果显示，两种跟踪器的速度，精度和鲁棒性都有所提高。

##### URL
[http://arxiv.org/abs/1801.03049](http://arxiv.org/abs/1801.03049)

##### PDF
[http://arxiv.org/pdf/1801.03049](http://arxiv.org/pdf/1801.03049)

