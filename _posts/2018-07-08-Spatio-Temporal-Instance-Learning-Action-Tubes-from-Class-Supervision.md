---
layout: post
title: "Spatio-Temporal Instance Learning: Action Tubes from Class Supervision"
date: 2018-07-08 11:12:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Inference Detection
author: Pascal Mettes, Cees G. M. Snoek
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of this paper is spatio-temporal localization of human actions from their class labels only. The state-of-the-art casts the problem as Multiple Instance Learning, where the instances are a priori computed action proposals. Rather than disconnecting the localization from the learning, we propose a variant of Multiple Instance Learning that integrates the spatio-temporal localization during the learning. We make three contributions. First, we define model assumptions tailored to actions and propose a latent instance learning objective allowing for optimization at the box-level. Second, we propose a spatio-temporal box linking algorithm, exploiting box proposals from off-the-shelf person detectors, suitable for weakly-supervised learning. Third, we introduce tube- and video-level refinements at inference time to integrate long-term spatio-temporal action characteristics. Our experiments on three video datasets show the benefits of our contributions as well as its competitive results compared to state-of-the-art alternatives that localize actions from their class label only. Finally, our algorithm enables incorporating point and box supervision, allowing to benchmark, mix, and balance action localization performance versus annotation time.

##### Abstract (translated by Google)
本文的目标是仅从类标签中进行人类行为的时空定位。最先进的技术将问题归结为多实例学习，其中实例是先验计算的动作提议。我们提出了一种多实例学习的变体，它在学习过程中集成了时空本地化，而不是将本地化与学习断开。我们做了三个贡献。首先，我们定义针对行动量身定制的模型假设，并提出潜在的实例学习目标，允许在盒级进行优化。其次，我们提出了一种时空盒链接算法，利用现成人检测器的盒子提议，适用于弱监督学习。第三，我们在推理时引入了管视频级细化，以整合长期的时空动作特征。我们对三个视频数据集的实验显示了我们的贡献的好处以及与最先进的替代方案相比的竞争结果，这些替代方案仅仅是从其类别标签本地化行动。最后，我们的算法可以实现点和盒监督，允许基准，混合和平衡动作本地化性能与注释时间。

##### URL
[http://arxiv.org/abs/1807.02800](http://arxiv.org/abs/1807.02800)

##### PDF
[http://arxiv.org/pdf/1807.02800](http://arxiv.org/pdf/1807.02800)

