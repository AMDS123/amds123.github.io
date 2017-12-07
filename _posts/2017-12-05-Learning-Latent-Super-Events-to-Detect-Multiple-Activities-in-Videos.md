---
layout: post
title: "Learning Latent Super-Events to Detect Multiple Activities in Videos"
date: 2017-12-05 21:40:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN Detection
author: AJ Piergiovanni, Michael S. Ryoo
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce the concept of learning latent \emph{super-events} from activity videos, and present how it benefits activity detection in continuous videos. We define a super-event as a set of multiple events occurring together in videos with a particular temporal organization; it is the opposite concept of sub-events. Real-world videos contain multiple activities and are rarely segmented (e.g., surveillance videos), and learning latent super-events allows the model to capture how the events are temporally related in videos. We design \emph{temporal structure filters} that enables the model to focus on particular sub-intervals of the videos, and use them together with a soft attention mechanism to learn representations of latent super-events. Super-event representations are combined with per-frame or per-segment CNNs to provide frame-level annotations. Our approach is designed to be fully differentiable, enabling an end-to-end learning of latent super-event representations jointly with the activity detector using them. Our experiments with multiple public video datasets confirm that the proposed concept of latent super-event learning significantly benefits activity detection, advancing the state-of-the-arts.

##### Abstract (translated by Google)
在本文中，我们介绍了从活动视频中学习潜在活动{超级活动}的概念，并介绍了如何在活动视频中检测活动。我们将超级事件定义为一组多个事件在具有特定时间组织的视频中一起发生;这是子事件的相反概念。真实世界的视频包含多个活动并且很少被分割（例如，监视视频），并且学习潜在的超级事件使得模型能够捕捉视频中的事件在时间上是如何相关的。我们设计使得模型能够专注于视频的特定子区间的\ emph {时间结构过滤器}，并且将它们与软注意机制一起用来学习潜在超级事件的表示。超级事件表示与每帧或每段CNN结合以提供帧级注释。我们的方法被设计为完全可区分的，使得能够与使用它们的活动检测器一起端到端地学习潜在的超事件表示。我们对多个公共视频数据集进行的实验证实，提出的潜在超级事件学习的概念显着地有利于活动检测，提高了现有技术水平。

##### URL
[http://arxiv.org/abs/1712.01938](http://arxiv.org/abs/1712.01938)

##### PDF
[http://arxiv.org/pdf/1712.01938](http://arxiv.org/pdf/1712.01938)

