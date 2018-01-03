---
layout: post
title: "Deep Reinforcement Learning for Unsupervised Video Summarization with Diversity-Representativeness Reward"
date: 2017-12-29 22:51:36
categories: arXiv_CV
tags: arXiv_CV Summarization Reinforcement_Learning
author: Kaiyang Zhou, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
Video summarization aims to facilitate large-scale video browsing by producing short, concise summaries that are diverse and representative of original videos. In this paper, we formulate video summarization as a sequential decision-making process and develop a deep summarization network (DSN) to summarize videos. DSN predicts for each video frame a probability, which indicates how likely a frame is selected, and then takes actions based on the probability distributions to select frames, forming video summaries. To train our DSN, we propose an end-to-end, reinforcement learning-based framework, where we design a novel reward function that jointly accounts for diversity and representativeness of generated summaries and does not rely on labels or user interactions at all. During training, the reward function judges how diverse and representative the generated summaries are, while DSN strives for earning higher rewards by learning to produce more diverse and more representative summaries. Since labels are not required, our method can be fully unsupervised. Extensive experiments on two benchmark datasets show that our unsupervised method not only outperforms other state-of-the-art unsupervised methods, but also is comparable to or even superior than most of published supervised approaches.

##### Abstract (translated by Google)
视频摘要旨在通过制作简短，简明的摘要来促进大规模的视频浏览，这些摘要是多种多样的，并且代表了原始视频。在本文中，我们将视频摘要制定为一个连续的决策过程，并开发一个深度摘要网络（DSN）来总结视频。 DSN为每个视频帧预测一个概率，该概率表示一个帧被选择的可能性，然后根据概率分布采取行动来选择帧，形成视频摘要。为了训练我们的DSN，我们提出了一个端到端的，基于强化学习的框架，在这个框架中，我们设计了一个新颖的奖励函数，共同解释生成的摘要的多样性和代表性，而且完全不依赖标签或用户交互。在培训期间，奖励功能可以判断生成的摘要的多样性和代表性，而DSN通过学习产生更多样化和更具代表性的摘要，努力获得更高的回报。由于标签不是必需的，我们的方法可以完全不受监督。在两个基准数据集上进行的大量实验表明，我们的无监督方法不仅胜过其他最先进的无监督方法，而且与大多数已发布的监督方法相比甚至更胜一筹。

##### URL
[http://arxiv.org/abs/1801.00054](http://arxiv.org/abs/1801.00054)

##### PDF
[http://arxiv.org/pdf/1801.00054](http://arxiv.org/pdf/1801.00054)

