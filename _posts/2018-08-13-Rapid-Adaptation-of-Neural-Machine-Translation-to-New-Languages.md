---
layout: post
title: "Rapid Adaptation of Neural Machine Translation to New Languages"
date: 2018-08-13 13:06:24
categories: arXiv_CL
tags: arXiv_CL Regularization
author: Graham Neubig, Junjie Hu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper examines the problem of adapting neural machine translation systems to new, low-resourced languages (LRLs) as effectively and rapidly as possible. We propose methods based on starting with massively multilingual "seed models", which can be trained ahead-of-time, and then continuing training on data related to the LRL. We contrast a number of strategies, leading to a novel, simple, yet effective method of "similar-language regularization", where we jointly train on both a LRL of interest and a similar high-resourced language to prevent over-fitting to small LRL data. Experiments demonstrate that massively multilingual models, even without any explicit adaptation, are surprisingly effective, achieving BLEU scores of up to 15.5 with no data from the LRL, and that the proposed similar-language regularization method improves over other adaptation methods by 1.7 BLEU points average over 4 LRL settings. Code to reproduce experiments at https://github.com/neubig/rapid-adaptation

##### Abstract (translated by Google)
本文探讨了使神经机器翻译系统尽可能有效和快速地适应新的低资源语言（LRL）的问题。我们提出了基于大量多语种“种子模型”的方法，这些方法可以提前进行培训，然后继续培训与LRL相关的数据。我们对比了许多策略，导致了一种新颖，简单而有效的“类似语言正规化”方法，在这种方法中，我们联合培养感兴趣的LRL和类似的高资源语言，以防止过度拟合小LRL数据。实验证明，大规模多语言模型，即使没有任何明确的适应，也令人惊讶地有效，在没有来自LRL的数据的情况下达到BLEU得分高达15.5，并且所提出的相似语言正则化方法比其他适应方法提高了1.7 BLEU点平均值超过4个LRL设置。用于在https://github.com/neubig/rapid-adaptation上重现实验的代码

##### URL
[http://arxiv.org/abs/1808.04189](http://arxiv.org/abs/1808.04189)

##### PDF
[http://arxiv.org/pdf/1808.04189](http://arxiv.org/pdf/1808.04189)

