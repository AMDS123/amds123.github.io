---
layout: post
title: "Robust Distant Supervision Relation Extraction via Deep Reinforcement Learning"
date: 2018-05-24 22:32:55
categories: arXiv_CL
tags: arXiv_CL Relation_Extraction Attention Reinforcement_Learning Relation
author: Pengda Qin, Weiran Xu, William Yang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Distant supervision has become the standard method for relation extraction. However, even though it is an efficient method, it does not come at no cost---The resulted distantly-supervised training samples are often very noisy. To combat the noise, most of the recent state-of-the-art approaches focus on selecting one-best sentence or calculating soft attention weights over the set of the sentences of one specific entity pair. However, these methods are suboptimal, and the false positive problem is still a key stumbling bottleneck for the performance. We argue that those incorrectly-labeled candidate sentences must be treated with a hard decision, rather than being dealt with soft attention weights. To do this, our paper describes a radical solution---We explore a deep reinforcement learning strategy to generate the false-positive indicator, where we automatically recognize false positives for each relation type without any supervised information. Unlike the removal operation in the previous studies, we redistribute them into the negative examples. The experimental results show that the proposed strategy significantly improves the performance of distant supervision comparing to state-of-the-art systems.

##### Abstract (translated by Google)
远程监督已成为关系提取的标准方法。然而，即使它是一种有效的方法，它也不会付出代价---所产生的远程监督训练样本通常非常嘈杂。为了对抗噪声，最近的大多数最先进的方法着重于选择一个最佳句子或计算一个特定实体对的句子集合上的软注意力权重。然而，这些方法并不理想，并且误报问题仍然是性能的关键瓶颈。我们认为，那些错误标记的候选句子必须以艰难的决定来处理，而不是处理软注意力的权重。为此，我们的论文描述了一个激进的解决方案---我们探索一个深度强化学习策略来产生假阳性指标，我们可以在没有任何监督信息的情况下自动识别每种关系类型的误报。与之前研究中的移除操作不同，我们将它们重新分配到反面示例中。实验结果表明，与最先进的系统相比，所提出的策略显着提高了远程监督的性能。

##### URL
[http://arxiv.org/abs/1805.09927](http://arxiv.org/abs/1805.09927)

##### PDF
[http://arxiv.org/pdf/1805.09927](http://arxiv.org/pdf/1805.09927)

