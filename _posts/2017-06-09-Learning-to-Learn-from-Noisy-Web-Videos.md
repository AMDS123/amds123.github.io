---
layout: post
title: "Learning to Learn from Noisy Web Videos"
date: 2017-06-09 10:25:05
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning Action_Recognition Recognition
author: Serena Yeung, Vignesh Ramanathan, Olga Russakovsky, Liyue Shen, Greg Mori, Li Fei-Fei
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding the simultaneously very diverse and intricately fine-grained set of possible human actions is a critical open problem in computer vision. Manually labeling training videos is feasible for some action classes but doesn't scale to the full long-tailed distribution of actions. A promising way to address this is to leverage noisy data from web queries to learn new actions, using semi-supervised or "webly-supervised" approaches. However, these methods typically do not learn domain-specific knowledge, or rely on iterative hand-tuned data labeling policies. In this work, we instead propose a reinforcement learning-based formulation for selecting the right examples for training a classifier from noisy web search results. Our method uses Q-learning to learn a data labeling policy on a small labeled training dataset, and then uses this to automatically label noisy web data for new visual concepts. Experiments on the challenging Sports-1M action recognition benchmark as well as on additional fine-grained and newly emerging action classes demonstrate that our method is able to learn good labeling policies for noisy data and use this to learn accurate visual concept classifiers.

##### Abstract (translated by Google)
理解同时存在的非常多样化和复杂细化的可能的人类行为是计算机视觉中的一个重要的开放性问题。手动标注培训视频对于某些行动类别是可行的，但不能按比例分配到完整的长尾行为。解决这个问题的一个有希望的方法是利用网络查询的噪音数据来学习新的行为，使用半监督或“网络监督”的方法。但是，这些方法通常不会学习特定于领域的知识，或者依赖迭代的手工调整的数据标记策略。在这项工作中，我们提出了一个强化学习为基础的公式选择正确的例子来训练分类器从嘈杂的网络搜索结果。我们的方法使用Q学习在小型标记训练数据集上学习数据标记策略，然后使用它来自动标记噪声网络数据以获得新的视觉概念。对具有挑战性的Sports-1M动作识别基准以及其他细粒度和新出现的动作类的实验表明，我们的方法能够学习针对噪声数据的良好标签政策，并使用它来学习准确的视觉概念分类器。

##### URL
[https://arxiv.org/abs/1706.02884](https://arxiv.org/abs/1706.02884)

##### PDF
[https://arxiv.org/pdf/1706.02884](https://arxiv.org/pdf/1706.02884)

