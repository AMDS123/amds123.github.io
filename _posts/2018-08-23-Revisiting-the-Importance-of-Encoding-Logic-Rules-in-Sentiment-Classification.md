---
layout: post
title: "Revisiting the Importance of Encoding Logic Rules in Sentiment Classification"
date: 2018-08-23 13:03:55
categories: arXiv_CL
tags: arXiv_CL Sentiment Sentiment_Classification Embedding Classification
author: Kalpesh Krishna, Preethi Jyothi, Mohit Iyyer
mathjax: true
---

* content
{:toc}

##### Abstract
We analyze the performance of different sentiment classification models on syntactically complex inputs like A-but-B sentences. The first contribution of this analysis addresses reproducible research: to meaningfully compare different models, their accuracies must be averaged over far more random seeds than what has traditionally been reported. With proper averaging in place, we notice that the distillation model described in <a href="https://export.arxiv.org/abs/1603.06318">arXiv:1603.06318v4</a> [cs.LG], which incorporates explicit logic rules for sentiment classification, is ineffective. In contrast, using contextualized ELMo embeddings (<a href="https://export.arxiv.org/abs/1802.05365">arXiv:1802.05365v2</a> [cs.CL]) instead of logic rules yields significantly better performance. Additionally, we provide analysis and visualizations that demonstrate ELMo's ability to implicitly learn logic rules. Finally, a crowdsourced analysis reveals how ELMo outperforms baseline models even on sentences with ambiguous sentiment labels.

##### Abstract (translated by Google)
我们分析了不同情绪分类模型在语法复杂输入（如A-but-B句子）上的表现。该分析的第一个贡献涉及可重复的研究：为了有意义地比较不同的模型，它们的准确度必须在比传统报告的更随机的种子上取平均值。通过适当的平均，我们注意到<a href="https://export.arxiv.org/abs/1603.06318"> arXiv：1603.06318v4 </a> [cs.LG]中描述的蒸馏模型，其中包含情感分类的明确逻辑规则是无效的。相比之下，使用上下文化ELMo嵌入（<a href="https://export.arxiv.org/abs/1802.05365"> arXiv：1802.05365v2 </a> [cs.CL]）而不是逻辑规则可以显着提高性能。此外，我们还提供分析和可视化，以展示ELMo隐式学习逻辑规则的能力。最后，众包分析揭示了ELMo甚至在具有模糊情绪标签的句子上也优于基线模型。

##### URL
[http://arxiv.org/abs/1808.07733](http://arxiv.org/abs/1808.07733)

##### PDF
[http://arxiv.org/pdf/1808.07733](http://arxiv.org/pdf/1808.07733)

