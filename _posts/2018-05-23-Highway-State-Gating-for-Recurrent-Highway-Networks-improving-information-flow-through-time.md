---
layout: post
title: "Highway State Gating for Recurrent Highway Networks: improving information flow through time"
date: 2018-05-23 15:53:10
categories: arXiv_AI
tags: arXiv_AI RNN
author: Ron Shoham, Haim Permuter
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNNs) play a major role in the field of sequential learning, and have outperformed traditional algorithms on many benchmarks. Training deep RNNs still remains a challenge, and most of the state-of-the-art models are structured with a transition depth of 2-4 layers. Recurrent Highway Networks (RHNs) were introduced in order to tackle this issue. These have achieved state-of-the-art performance on a few benchmarks using a depth of 10 layers. However, the performance of this architecture suffers from a bottleneck, and ceases to improve when an attempt is made to add more layers. In this work, we analyze the causes for this, and postulate that the main source is the way that the information flows through time. We introduce a novel and simple variation for the RHN cell, called Highway State Gating (HSG), which allows adding more layers, while continuing to improve performance. By using a gating mechanism for the state, we allow the net to "choose" whether to pass information directly through time, or to gate it. This mechanism also allows the gradient to back-propagate directly through time and, therefore, results in a slightly faster convergence. We use the Penn Treebank (PTB) dataset as a platform for empirical proof of concept. Empirical results show that the improvement due to Highway State Gating is for all depths, and as the depth increases, the improvement also increases.

##### Abstract (translated by Google)
递归神经网络（RNN）在顺序学习领域发挥重要作用，并且在许多基准测试中超越了传统算法。深度RNN的训练仍然是一个挑战，大部分最先进的模型都是以2-4层的转换深度构成的。引入经常性高速公路网络（RHNs）是为了解决这个问题。这些已经在一些基准测试中达到了最高性能，使用了10层深度。然而，这种架构的性能受到瓶颈的影响，并且在尝试添加更多层时停止改进。在这项工作中，我们分析其原因，并假设主要来源是信息流经时间的方式。我们为RHN单元引入了一种新颖而简单的变体，叫做Highway State Gating（HSG），它允许增加更多层，同时继续提高性能。通过使用国家的门控机制，我们允许网络“选择”是直接通过时间传递信息还是通过门禁。该机制还允许梯度直接通过时间反向传播，因此会导致稍微更快的收敛。我们使用Penn Treebank（PTB）数据集作为经验证明概念的平台。实证结果表明，由于公路状态门控的改善是针对所有深度的，随着深度的增加，改善也会增加。

##### URL
[http://arxiv.org/abs/1805.09238](http://arxiv.org/abs/1805.09238)

##### PDF
[http://arxiv.org/pdf/1805.09238](http://arxiv.org/pdf/1805.09238)

