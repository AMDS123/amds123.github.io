---
layout: post
title: "Multi-Passage Machine Reading Comprehension with Cross-Passage Answer Verification"
date: 2018-05-06 14:26:35
categories: arXiv_CL
tags: arXiv_CL
author: Yizhong Wang, Kai Liu, Jing Liu, Wei He, Yajuan Lyu, Hua Wu, Sujian Li, Haifeng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Machine reading comprehension (MRC) on real web data usually requires the machine to answer a question by analyzing multiple passages retrieved by search engine. Compared with MRC on a single passage, multi-passage MRC is more challenging, since we are likely to get multiple confusing answer candidates from different passages. To address this problem, we propose an end-to-end neural model that enables those answer candidates from different passages to verify each other based on their content representations. Specifically, we jointly train three modules that can predict the final answer based on three factors: the answer boundary, the answer content and the cross-passage answer verification. The experimental results show that our method outperforms the baseline by a large margin and achieves the state-of-the-art performance on the English MS-MARCO dataset and the Chinese DuReader dataset, both of which are designed for MRC in real-world settings.

##### Abstract (translated by Google)
对真实网络数据的机器阅读理解（MRC）通常需要机器通过分析搜索引擎检索到的多个段落来回答问题。与MRC相比，多通道MRC更具挑战性，因为我们可能会从不同的段落中得到多个令人困惑的答案候选人。为了解决这个问题，我们提出了一个端到端的神经模型，使得来自不同段落的候选答案能够根据他们的内容表示来相互验证。具体而言，我们共同培训三个模块，可以根据三个因素预测最终答案：答案边界，答案内容和跨通道答案验证。实验结果表明，我们的方法大大超过了基线，并且在英文MS-MARCO数据集和中文DuReader数据集上达到了最先进的性能，这两个数据集都是为真实环境中的MRC设计的。

##### URL
[http://arxiv.org/abs/1805.02220](http://arxiv.org/abs/1805.02220)

##### PDF
[http://arxiv.org/pdf/1805.02220](http://arxiv.org/pdf/1805.02220)

