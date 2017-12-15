---
layout: post
title: "A Simple, Fast Diverse Decoding Algorithm for Neural Generation"
date: 2016-12-22 16:31:52
categories: arXiv_CL
tags: arXiv_CL Summarization Reinforcement_Learning
author: Jiwei Li, Will Monroe, Dan Jurafsky
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a simple, fast decoding algorithm that fosters diversity in neural generation. The algorithm modifies the standard beam search algorithm by adding an inter-sibling ranking penalty, favoring choosing hypotheses from diverse parents. We evaluate the proposed model on the tasks of dialogue response generation, abstractive summarization and machine translation. We find that diverse decoding helps across all tasks, especially those for which reranking is needed. We further propose a variation that is capable of automatically adjusting its diversity decoding rates for different inputs using reinforcement learning (RL). We observe a further performance boost from this RL technique. This paper includes material from the unpublished script "Mutual Information and Diverse Decoding Improve Neural Machine Translation" (Li and Jurafsky, 2016).

##### Abstract (translated by Google)
在本文中，我们提出了一种简单，快速的解码算法，促进神经生成的多样性。该算法通过增加一个兄弟之间的排序惩罚修改标准的射束搜索算法，有利于从不同的父母选择假设。我们评估提出的对话模型，对话反应生成，抽象概括和机器翻译。我们发现各种解码有助于跨所有任务，尤其是那些需要重新排序的解码。我们进一步提出一种能够使用强化学习（RL）自动调整不同输入的分集解码速率的变体。我们观察到这种RL技术的进一步性能提升。本文包括未发表的脚本“互信息和多样解码改进神经机器翻译”（Li和Jurafsky，2016）。

##### URL
[https://arxiv.org/abs/1611.08562](https://arxiv.org/abs/1611.08562)

##### PDF
[https://arxiv.org/pdf/1611.08562](https://arxiv.org/pdf/1611.08562)

