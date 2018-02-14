---
layout: post
title: "Deep Neural Networks for Bot Detection"
date: 2018-02-12 19:00:15
categories: arXiv_AI
tags: arXiv_AI Sentiment RNN Classification Detection
author: Sneha Kudugunta, Emilio Ferrara
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of detecting bots, automated social media accounts governed by software but disguising as human users, has strong implications. For example, bots have been used to sway political elections by distorting online discourse, to manipulate the stock market, or to push anti-vaccine conspiracy theories that caused health epidemics. Most techniques proposed to date detect bots at the account level, by processing large amount of social media posts, and leveraging information from network structure, temporal dynamics, sentiment analysis, etc. 
 In this paper, we propose a deep neural network based on contextual long short-term memory (LSTM) architecture that exploits both content and metadata to detect bots at the tweet level: contextual features are extracted from user metadata and fed as auxiliary input to LSTM deep nets processing the tweet text. 
 Another contribution that we make is proposing a technique based on synthetic minority oversampling to generate a large labeled dataset, suitable for deep nets training, from a minimal amount of labeled data (roughly 3,000 examples of sophisticated Twitter bots). We demonstrate that, from just one single tweet, our architecture can achieve high classification accuracy (AUC &gt; 96%) in separating bots from humans. 
 We apply the same architecture to account-level bot detection, achieving nearly perfect classification accuracy (AUC &gt; 99%). Our system outperforms previous state of the art while leveraging a small and interpretable set of features yet requiring minimal training data.

##### Abstract (translated by Google)
检测僵尸程序的问题，自动社交媒体帐户由软件管理，但伪装成人类用户，这具有强烈的影响。例如，僵尸已被用于通过歪曲在线话语，操纵股票市场或推动引发健康流行病的反疫苗阴谋理论来影响政治选举。目前提出的大多数技术都是通过处理大量社交媒体帖子，并利用来自网络结构，时间动态，情感分析等的信息来检测帐户级别的僵尸工具。
 在本文中，我们提出了一种基于上下文长短期记忆（LSTM）架构的深度神经网络，该架构利用内容和元数据在推特级别检测僵尸工具：从用户元数据中提取上下文特征，并将其作为辅助输入提供给LSTM深层网络处理推文文本。
 我们提出的另一个贡献是提出一种基于合成少数过采样的技术，从少量标记数据（大约3000个复杂的Twitter机器人示例）中生成一个适用于深度网络训练的大型标记数据集。我们证明，从仅仅一条推文中，我们的架构可以实现将机器人从人类中分离出来的高分类准确率（AUC> 96％）。
 我们将相同的体系结构应用于帐户级别的机器人检测，实现了近乎完美的分类准确性（AUC> 99％）。我们的系统优于先前的技术水平，同时利用了一小部分可解释的功能，但只需要最少的培训数据。

##### URL
[http://arxiv.org/abs/1802.04289](http://arxiv.org/abs/1802.04289)

##### PDF
[http://arxiv.org/pdf/1802.04289](http://arxiv.org/pdf/1802.04289)

