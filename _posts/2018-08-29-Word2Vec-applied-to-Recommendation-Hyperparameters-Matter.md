---
layout: post
title: "Word2Vec applied to Recommendation: Hyperparameters Matter"
date: 2018-08-29 15:16:08
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model Recommendation
author: Hugo Caselles-Dupr&#xe9;, Florian Lesaint, Jimena Royo-Letelier
mathjax: true
---

* content
{:toc}

##### Abstract
Skip-gram with negative sampling, a popular variant of Word2vec originally designed and tuned to create word embeddings for Natural Language Processing, has been used to create item embeddings with successful applications in recommendation. While these fields do not share the same type of data, neither evaluate on the same tasks, recommendation applications tend to use the same already tuned hyperparameters values, even if optimal hyperparameters values are often known to be data and task dependent. We thus investigate the marginal importance of each hyperparameter in a recommendation setting through large hyperparameter grid searches on various datasets. Results reveal that optimizing neglected hyperparameters, namely negative sampling distribution, number of epochs, subsampling parameter and window-size, significantly improves performance on a recommendation task, and can increase it by an order of magnitude. Importantly, we find that optimal hyperparameters configurations for Natural Language Processing tasks and Recommendation tasks are noticeably different.

##### Abstract (translated by Google)
带有负抽样的Skip-gram是最初设计和调整为自然语言处理创建单词嵌入的Word2vec的流行变体，已被用于创建项目嵌入，并在推荐中成功应用。虽然这些字段不共享相同类型的数据，但都不评估相同的任务，推荐应用程序倾向于使用相同的已调整的超参数值，即使通常已知最佳超参数值是数据和任务相关的。因此，我们通过对各种数据集进行大型超参数网格搜索，在推荐设置中研究每个超参数的边际重要性。结果表明，优化被忽略的超参数，即负采样分布，时期数，子采样参数和窗口大小，显着提高了推荐任务的性能，并且可以将其增加一个数量级。重要的是，我们发现自然语言处理任务和推荐任务的最佳超参数配置明显不同。

##### URL
[http://arxiv.org/abs/1804.04212](http://arxiv.org/abs/1804.04212)

##### PDF
[http://arxiv.org/pdf/1804.04212](http://arxiv.org/pdf/1804.04212)

