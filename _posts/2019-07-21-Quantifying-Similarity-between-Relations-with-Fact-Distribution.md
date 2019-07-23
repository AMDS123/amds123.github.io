---
layout: post
title: "Quantifying Similarity between Relations with Fact Distribution"
date: 2019-07-21 09:22:50
categories: arXiv_AI
tags: arXiv_AI Knowledge Classification Relation
author: Weize Chen, Hao Zhu, Xu Han, Zhiyuan Liu, Maosong Sun
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a conceptually simple and effective method to quantify the similarity between relations in knowledge bases. Specifically, our approach is based on the divergence between the conditional probability distributions over entity pairs. In this paper, these distributions are parameterized by a very simple neural network. Although computing the exact similarity is in-tractable, we provide a sampling-based method to get a good approximation. We empirically show the outputs of our approach significantly correlate with human judgments. By applying our method to various tasks, we also find that (1) our approach could effectively detect redundant relations extracted by open information extraction (Open IE) models, that (2) even the most competitive models for relational classification still make mistakes among very similar relations, and that (3) our approach could be incorporated into negative sampling and softmax classification to alleviate these mistakes. The source code and experiment details of this paper can be obtained from https://github.com/thunlp/relation-similarity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08937](http://arxiv.org/abs/1907.08937)

##### PDF
[http://arxiv.org/pdf/1907.08937](http://arxiv.org/pdf/1907.08937)

