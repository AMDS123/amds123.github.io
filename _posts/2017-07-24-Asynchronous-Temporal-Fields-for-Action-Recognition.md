---
layout: post
title: "Asynchronous Temporal Fields for Action Recognition"
date: 2017-07-24 09:58:14
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Inference Classification Relation Recognition
author: Gunnar A. Sigurdsson, Santosh Divvala, Ali Farhadi, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Actions are more than just movements and trajectories: we cook to eat and we hold a cup to drink from it. A thorough understanding of videos requires going beyond appearance modeling and necessitates reasoning about the sequence of activities, as well as the higher-level constructs such as intentions. But how do we model and reason about these? We propose a fully-connected temporal CRF model for reasoning over various aspects of activities that includes objects, actions, and intentions, where the potentials are predicted by a deep network. End-to-end training of such structured models is a challenging endeavor: For inference and learning we need to construct mini-batches consisting of whole videos, leading to mini-batches with only a few videos. This causes high-correlation between data points leading to breakdown of the backprop algorithm. To address this challenge, we present an asynchronous variational inference method that allows efficient end-to-end training. Our method achieves a classification mAP of 22.4% on the Charades benchmark, outperforming the state-of-the-art (17.2% mAP), and offers equal gains on the task of temporal localization.

##### Abstract (translated by Google)
行动不仅仅是动作和轨迹：我们做饭吃，我们拿着一杯喝。彻底理解视频需要超越外观建模，并需要推理活动的顺序，以及更高层次的结构如意图。但是我们如何对这些进行建模和推理呢？我们提出了一个完全连接的时间CRF模型，用于对包括对象，动作和意图在内的活动的各个方面进行推理，其中潜能由深度网络预测。对这种结构化模型的端到端培训是一项具有挑战性的工作：为了进行推理和学习，我们需要构建由整个视频组成的小批量，导致只有少数视频的小批量。这导致数据点之间的高度相关性导致backprop算法的崩溃。为了应对这一挑战，我们提出了一种异步变分推理方法，可以进行有效的端到端培训。我们的方法在Charades基准测试中实现了22.4％的分类MAP，超越了最新的（17.2％的MAP），并且在时间本地化的任务上提供了同样的收益。

##### URL
[https://arxiv.org/abs/1612.06371](https://arxiv.org/abs/1612.06371)

##### PDF
[https://arxiv.org/pdf/1612.06371](https://arxiv.org/pdf/1612.06371)

