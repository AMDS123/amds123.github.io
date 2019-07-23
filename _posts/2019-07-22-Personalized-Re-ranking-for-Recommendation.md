---
layout: post
title: "Personalized Re-ranking for Recommendation"
date: 2019-07-22 06:02:13
categories: arXiv_AI
tags: arXiv_AI Attention Embedding Relation Recommendation
author: Changhua Pei, Yi Zhang, Yongfeng Zhang, Fei Sun, Xiao Lin, Hanxiao Sun, Jian Wu, Peng Jiang, Wenwu Ou, Dan Pei
mathjax: true
---

* content
{:toc}

##### Abstract
Ranking is a core task in recommender systems, which aims at providing an ordered list of items to users. Typically, a ranking function is learned from the labeled dataset to optimize the global performance, which produces a ranking score for each individual item. However, it may be sub-optimal because the scoring function applies to each item individually and does not explicitly consider the mutual influence between items, as well as the differences of users' preferences or intents. Therefore, we propose a personalized re-ranking model for recommender systems. The proposed re-ranking model can be easily deployed as a follow-up modular after any ranking algorithm, by directly using the existing ranking feature vectors. It directly optimizes the whole recommendation list by employing a transformer structure to efficiently encode the information of all items in the list. Specifically, the Transformer applies a self-attention mechanism that directly models the global relationships between any pair of items in the whole list. We confirm that the performance can be further improved by introducing pre-trained embedding to learn personalized encoding functions for different users. Experimental results on both offline benchmarks and real-world online e-commerce systems demonstrate the significant improvements of the proposed re-ranking model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06813](http://arxiv.org/abs/1904.06813)

##### PDF
[http://arxiv.org/pdf/1904.06813](http://arxiv.org/pdf/1904.06813)

