---
layout: post
title: "Coherent Dialogue with Attention-based Language Models"
date: 2016-11-21 20:25:19
categories: arXiv_CL
tags: arXiv_CL Attention RNN Language_Model
author: Hongyuan Mei, Mohit Bansal, Matthew R. Walter
mathjax: true
---

* content
{:toc}

##### Abstract
We model coherent conversation continuation via RNN-based dialogue models equipped with a dynamic attention mechanism. Our attention-RNN language model dynamically increases the scope of attention on the history as the conversation continues, as opposed to standard attention (or alignment) models with a fixed input scope in a sequence-to-sequence model. This allows each generated word to be associated with the most relevant words in its corresponding conversation history. We evaluate the model on two popular dialogue datasets, the open-domain MovieTriples dataset and the closed-domain Ubuntu Troubleshoot dataset, and achieve significant improvements over the state-of-the-art and baselines on several metrics, including complementary diversity-based metrics, human evaluation, and qualitative visualizations. We also show that a vanilla RNN with dynamic attention outperforms more complex memory models (e.g., LSTM and GRU) by allowing for flexible, long-distance memory. We promote further coherence via topic modeling-based reranking.

##### Abstract (translated by Google)
我们通过配备动态关注机制的基于RNN的对话模型来建立连贯的对话延续模型。我们的注意-RNN语言模型在对话继续时动态地增加对历史的关注范围，与在序列到序列模型中具有固定输入范围的标准注意（或对齐）模型相反。这允许每个生成的单词与其对应的对话历史中最相关的单词相关联。我们评估了两个流行的对话数据集（开放域MovieTriples数据集和封闭域Ubuntu故障排除数据集）上的模型，并在几个度量标准上对最先进的基线进行了重大改进，其中包括基于互补的基于多样性的度量标准，人类评估和定性可视化。我们还表明，具有动态关注的香草RNN通过考虑灵活的远距离记忆而优于更复杂的记忆模型（例如，LSTM和GRU）。我们通过基于主题建模的重新排名来进一步提高一致性。

##### URL
[https://arxiv.org/abs/1611.06997](https://arxiv.org/abs/1611.06997)

##### PDF
[https://arxiv.org/pdf/1611.06997](https://arxiv.org/pdf/1611.06997)

