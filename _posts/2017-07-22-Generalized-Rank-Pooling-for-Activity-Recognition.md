---
layout: post
title: "Generalized Rank Pooling for Activity Recognition"
date: 2017-07-22 04:22:16
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Optimization Classification Recognition
author: Anoop Cherian, Basura Fernando, Mehrtash Harandi, Stephen Gould
mathjax: true
---

* content
{:toc}

##### Abstract
Most popular deep models for action recognition split video sequences into short sub-sequences consisting of a few frames; frame-based features are then pooled for recognizing the activity. Usually, this pooling step discards the temporal order of the frames, which could otherwise be used for better recognition. Towards this end, we propose a novel pooling method, generalized rank pooling (GRP), that takes as input, features from the intermediate layers of a CNN that is trained on tiny sub-sequences, and produces as output the parameters of a subspace which (i) provides a low-rank approximation to the features and (ii) preserves their temporal order. We propose to use these parameters as a compact representation for the video sequence, which is then used in a classification setup. We formulate an objective for computing this subspace as a Riemannian optimization problem on the Grassmann manifold, and propose an efficient conjugate gradient scheme for solving it. Experiments on several activity recognition datasets show that our scheme leads to state-of-the-art performance.

##### Abstract (translated by Google)
最流行的动作识别深层模型将视频序列分割成由几帧组成的短子序列;然后汇集基于帧的特征来识别活动。通常，这个合并步骤丢弃帧的时间顺序，否则这些顺序可以用于更好的识别。为此，我们提出了一种新的池化方法 - 广义秩池（GRP），它以CNN的中间层为输入，在微小的子序列上进行训练，产生一个子空间的参数（i）提供对特征的低秩近似和（ii）保持它们的时间顺序。我们建议使用这些参数作为视频序列的紧凑表示，然后将其用于分类设置。在Grassmann流形上，我们制定了一个计算这个子空间的黎曼优化问题的目标，并提出了一个有效的共轭梯度方法来解决这个问题。在几个活动识别数据集上的实验表明，我们的方案导致了最先进的性能。

##### URL
[https://arxiv.org/abs/1704.02112](https://arxiv.org/abs/1704.02112)

##### PDF
[https://arxiv.org/pdf/1704.02112](https://arxiv.org/pdf/1704.02112)

