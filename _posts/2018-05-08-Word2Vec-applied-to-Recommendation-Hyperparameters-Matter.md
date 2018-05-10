---
layout: post
title: "Word2Vec applied to Recommendation: Hyperparameters Matter"
date: 2018-05-08 19:30:18
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
使用反向采样的Skip-gram是Word2vec的一个流行版本，它最初是为自然语言处理而设计和调整以创建词语嵌入的，已用于创建项目嵌入，并在推荐中使用成功的应用程序。虽然这些字段不共享相同类型的数据，但既不评估相同的任务，推荐应用程序倾向于使用相同的已调优的超参数值，即使最佳的超参数值通常被认为是数据和任务相关的。因此，我们通过对各种数据集进行大型超参数网格搜索来调查每个超参数在推荐设置中的边际重要性。结果显示，优化被忽略的超参数，即负抽样分布，时期数目，子采样参数和窗口大小，可显着提高推荐任务的性能，并可将其提高一个数量级。重要的是，我们发现自然语言处理任务和推荐任务的最优超参数配置明显不同。

##### URL
[http://arxiv.org/abs/1804.04212](http://arxiv.org/abs/1804.04212)

##### PDF
[http://arxiv.org/pdf/1804.04212](http://arxiv.org/pdf/1804.04212)

