---
layout: post
title: "Mixed Membership Word Embeddings for Computational Social Science"
date: 2017-05-25 03:12:35
categories: arXiv_CL
tags: arXiv_CL Embedding Relation
author: James Foulds
mathjax: true
---

* content
{:toc}

##### Abstract
Word embeddings improve the performance of NLP systems by revealing the hidden structural relationships between words. These models have recently risen in popularity due to the performance of scalable algorithms trained in the big data setting. Despite their success, word embeddings have seen very little use in computational social science NLP tasks, presumably due to their reliance on big data, and to a lack of interpretability. I propose a probabilistic model-based word embedding method which can recover interpretable embeddings, without big data. The key insight is to leverage the notion of mixed membership modeling, in which global representations are shared, but individual entities (i.e. dictionary words) are free to use these representations to uniquely differing degrees. Leveraging connections to topic models, I show how to train these models in high dimensions using a combination of state-of-the-art techniques for word embeddings and topic modeling. Experimental results show an improvement in predictive performance of up to 63% in MRR over the skip-gram on small datasets. The models are interpretable, as embeddings of topics are used to encode embeddings for words (and hence, documents) in a model-based way. I illustrate this with two computational social science case studies, on NIPS articles and State of the Union addresses.

##### Abstract (translated by Google)
词嵌入通过揭示词之间隐藏的结构关系来改善NLP系统的性能。由于在大数据设置中训练的可伸缩算法的性能，这些模型最近受到欢迎。尽管他们的成功，词嵌入已经很少用于计算社会科学NLP任务，可能是由于他们依赖大数据，并缺乏可解释性。我提出了一种基于概率模型的词嵌入方法，可以在没有大数据的情况下恢复可解释的嵌入。关键的洞察力是利用混合成员资格建模的概念，其中全局表示是共享的，但是单个实体（即字典单词）可以自由地使用这些表示以独特的不同程度。利用与主题模型的连接，我将展示如何使用结合最先进的词嵌入和主题建模技术来高维地训练这些模型。实验结果显示，在小数据集上，MRR的预测性能比在跳跃式数据库中的预测性能提高高达63％。模型是可解释的，因为主题的嵌入被用于以基于模型的方式对单词（以及因此文档）的嵌入进行编码。我用两个计算社会科学案例研究，NIPS文章和国情咨文说明了这一点。

##### URL
[https://arxiv.org/abs/1705.07368](https://arxiv.org/abs/1705.07368)

##### PDF
[https://arxiv.org/pdf/1705.07368](https://arxiv.org/pdf/1705.07368)

