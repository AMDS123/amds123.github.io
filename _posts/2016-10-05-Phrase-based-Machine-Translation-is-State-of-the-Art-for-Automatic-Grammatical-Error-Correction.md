---
layout: post
title: "Phrase-based Machine Translation is State-of-the-Art for Automatic Grammatical Error Correction"
date: 2016-10-05 08:42:23
categories: arXiv_CL
tags: arXiv_CL Sparse
author: Marcin Junczys-Dowmunt, Roman Grundkiewicz
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we study parameter tuning towards the M^2 metric, the standard metric for automatic grammar error correction (GEC) tasks. After implementing M^2 as a scorer in the Moses tuning framework, we investigate interactions of dense and sparse features, different optimizers, and tuning strategies for the CoNLL-2014 shared task. We notice erratic behavior when optimizing sparse feature weights with M^2 and offer partial solutions. We find that a bare-bones phrase-based SMT setup with task-specific parameter-tuning outperforms all previously published results for the CoNLL-2014 test set by a large margin (46.37% M^2 over previously 41.75%, by an SMT system with neural features) while being trained on the same, publicly available data. Our newly introduced dense and sparse features widen that gap, and we improve the state-of-the-art to 49.49% M^2.

##### Abstract (translated by Google)
在这项工作中，我们研究了针对M ^ 2度量的参数调整，这是衡量自动语法纠错（GEC）任务的标准度量。在Moses调整框架中作为记分员实施M ^ 2之后，我们调查CoNLL-2014共享任务的密集和稀疏特征的交互，不同的优化器和调整策略。当用M ^ 2优化稀疏特征权重时，我们注意到不规则行为，并提供部分解决方案。我们发现，基于短语的SMT设置与任务特定的参数调整优于CoNLL-2014测试集的所有先前发布的结果（46.37％M ^ 2比之前的41.75％，SMT系统与神经功能），同时在公开的数据相同的训练。我们新引入的密集和稀疏特征扩大了这一差距，我们将现有技术水平提高到了49.49％M ^ 2。

##### URL
[https://arxiv.org/abs/1605.06353](https://arxiv.org/abs/1605.06353)

##### PDF
[https://arxiv.org/pdf/1605.06353](https://arxiv.org/pdf/1605.06353)

