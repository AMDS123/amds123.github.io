---
layout: post
title: "Learning Multi-touch Conversion Attribution with Dual-attention Mechanisms for Online Advertising"
date: 2018-08-11 01:58:19
categories: arXiv_AI
tags: arXiv_AI Attention RNN Prediction Quantitative
author: Kan Ren, Yuchen Fang, Weinan Zhang, Shuhao Liu, Jiajun Li, Ya Zhang, Yong Yu, Jun Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In online advertising, the Internet users may be exposed to a sequence of different ad campaigns, i.e., display ads, search, or referrals from multiple channels, before led up to any final sales conversion and transaction. For both campaigners and publishers, it is fundamentally critical to estimate the contribution from ad campaign touch-points during the customer journey (conversion funnel) and assign the right credit to the right ad exposure accordingly. However, the existing research on the multi-touch attribution problem lacks a principled way of utilizing the users' pre-conversion actions (i.e., clicks), and quite often fails to model the sequential patterns among the touch points from a user's behavior data. To make it worse, the current industry practice is merely employing a set of arbitrary rules as the attribution model, e.g., the popular last-touch model assigns 100% credit to the final touch-point regardless of actual attributions. In this paper, we propose a Dual-attention Recurrent Neural Network (DARNN) for the multi-touch attribution problem. It learns the attribution values through an attention mechanism directly from the conversion estimation objective. To achieve this, we utilize sequence-to-sequence prediction for user clicks, and combine both post-view and post-click attribution patterns together for the final conversion estimation. To quantitatively benchmark attribution models, we also propose a novel yet practical attribution evaluation scheme through the proxy of budget allocation (under the estimated attributions) over ad channels. The experimental results on two real datasets demonstrate the significant performance gains of our attribution model against the state of the art.

##### Abstract (translated by Google)
在在线广告中，在引导至任何最终销售转换和交易之前，互联网用户可能暴露于一系列不同的广告活动，即，显示广告，搜索或来自多个渠道的推荐。对于活动家和发布商而言，从客户旅程（转换渠道）中估算广告系列接触点的贡献并相应地为正确的广告曝光分配正确的信用额度至关重要。然而，现有的关于多点触摸属性问题的研究缺乏利用用户的转换前动作（即点击）的原理方式，并且经常无法根据用户的行为数据对触摸点之间的顺序模式进行建模。更糟糕的是，当前的行业惯例仅仅是采用一组任意规则作为归因模型，例如，流行的最后触摸模型为最终接触点分配100％的信用，而不管实际属性如何。在本文中，我们提出了一个双注意递归神经网络（DARNN）的多点触摸属性问题。它直接从转化估算目标通过关注机制来学习归因值。为实现此目的，我们利用用户点击的序列到序列预测，并将后视图和后点击归因模式结合在一起，以进行最终的转化估算。为了定量地对归因模型进行基准测试，我们还通过广告渠道的预算分配（在估计的归因下）代理，提出了一种新颖但实用的归因评估方案。两个真实数据集的实验结果证明了我们的归因模型对现有技术的显着性能提升。

##### URL
[http://arxiv.org/abs/1808.03737](http://arxiv.org/abs/1808.03737)

##### PDF
[http://arxiv.org/pdf/1808.03737](http://arxiv.org/pdf/1808.03737)

