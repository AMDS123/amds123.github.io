---
layout: post
title: "Distilled Wasserstein Learning for Word Embedding and Topic Modeling"
date: 2018-09-12 23:10:23
categories: arXiv_CL
tags: arXiv_CL Embedding Prediction Recommendation
author: Hongteng Xu, Wenlin Wang, Wei Liu, Lawrence Carin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel Wasserstein method with a distillation mechanism, yielding joint learning of word embeddings and topics. The proposed method is based on the fact that the Euclidean distance between word embeddings may be employed as the underlying distance in the Wasserstein topic model. The word distributions of topics, their optimal transports to the word distributions of documents, and the embeddings of words are learned in a unified framework. When learning the topic model, we leverage a distilled underlying distance matrix to update the topic distributions and smoothly calculate the corresponding optimal transports. Such a strategy provides the updating of word embeddings with robust guidance, improving the algorithmic convergence. As an application, we focus on patient admission records, in which the proposed method embeds the codes of diseases and procedures and learns the topics of admissions, obtaining superior performance on clinically-meaningful disease network construction, mortality prediction as a function of admission codes, and procedure recommendation.

##### Abstract (translated by Google)
我们提出了一种具有蒸馏机制的新型Wasserstein方法，可以实现单词嵌入和主题的联合学习。所提出的方法基于以下事实：可以将字嵌入之间的欧几里德距离用作Wasserstein主题模型中的基础距离。主题的分布，它们对文档的单词分布的最佳传输以及单词的嵌入是在统一的框架中学习的。在学习主题模型时，我们利用蒸馏的基础距离矩阵来更新主题分布并平滑地计算相应的最优传输。这种策略通过强大的指导提供了字嵌入的更新，提高了算法的收敛性。作为一种应用，我们关注患者入院记录，其中所提出的方法嵌入疾病和程序的代码并学习入院的主题，在临床有意义的疾病网络建设中获得优越的表现，作为入院代码的函数的死亡率预测，和程序建议。

##### URL
[http://arxiv.org/abs/1809.04705](http://arxiv.org/abs/1809.04705)

##### PDF
[http://arxiv.org/pdf/1809.04705](http://arxiv.org/pdf/1809.04705)

