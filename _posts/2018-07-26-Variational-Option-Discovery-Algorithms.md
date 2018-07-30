---
layout: post
title: "Variational Option Discovery Algorithms"
date: 2018-07-26 18:05:45
categories: arXiv_AI
tags: arXiv_AI Inference
author: Joshua Achiam, Harrison Edwards, Dario Amodei, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
We explore methods for option discovery based on variational inference and make two algorithmic contributions. First: we highlight a tight connection between variational option discovery methods and variational autoencoders, and introduce Variational Autoencoding Learning of Options by Reinforcement (VALOR), a new method derived from the connection. In VALOR, the policy encodes contexts from a noise distribution into trajectories, and the decoder recovers the contexts from the complete trajectories. Second: we propose a curriculum learning approach where the number of contexts seen by the agent increases whenever the agent's performance is strong enough (as measured by the decoder) on the current set of contexts. We show that this simple trick stabilizes training for VALOR and prior variational option discovery methods, allowing a single agent to learn many more modes of behavior than it could with a fixed context distribution. Finally, we investigate other topics related to variational option discovery, including fundamental limitations of the general approach and the applicability of learned options to downstream tasks.

##### Abstract (translated by Google)
我们探索基于变分推理的选项发现方法，并做出两个算法贡献。第一：我们强调变分选项发现方法和变分自动编码器之间的紧密联系，并通过增强（VALOR）引入变体自动编码学习，这是一种从连接中派生出来的新方法。在VALOR中，策略将噪声分布的上下文编码为轨迹，并且解码器从完整轨迹中恢复上下文。第二：我们提出了一种课程学习方法，当代理的表现足够强大（由解码器测量）时，代理所看到的上下文数量会增加当前的一组上下文。我们证明了这个简单的技巧稳定了VALOR和先前的变分选项发现方法的训练，允许单个代理学习比固定上下文分布更多的行为模式。最后，我们研究了与变分选项发现相关的其他主题，包括一般方法的基本限制以及学习选项对下游任务的适用性。

##### URL
[http://arxiv.org/abs/1807.10299](http://arxiv.org/abs/1807.10299)

##### PDF
[http://arxiv.org/pdf/1807.10299](http://arxiv.org/pdf/1807.10299)

