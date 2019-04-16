---
layout: post
title: "Improving Distantly-supervised Entity Typing with Compact Latent Space Clustering"
date: 2019-04-13 03:52:56
categories: arXiv_AI
tags: arXiv_AI Embedding Classification
author: Bo Chen, Xiaotao Gu, Yufeng Hu, Siliang Tang, Guoping Hu, Yueting Zhuang, Xiang Ren
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, distant supervision has gained great success on Fine-grained Entity Typing (FET). Despite its efficiency in reducing manual labeling efforts, it also brings the challenge of dealing with false entity type labels, as distant supervision assigns labels in a context agnostic manner. Existing works alleviated this issue with partial-label loss, but usually suffer from confirmation bias, which means the classifier fit a pseudo data distribution given by itself. In this work, we propose to regularize distantly supervised models with Compact Latent Space Clustering (CLSC) to bypass this problem and effectively utilize noisy data yet. Our proposed method first dynamically constructs a similarity graph of different entity mentions; infer the labels of noisy instances via label propagation. Based on the inferred labels, mention embeddings are updated accordingly to encourage entity mentions with close semantics to form a compact cluster in the embedding space,thus leading to better classification performance. Extensive experiments on standard benchmarks show that our CLSC model consistently outperforms state-of-the-art distantly supervised entity typing systems by a significant margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06475](http://arxiv.org/abs/1904.06475)

##### PDF
[http://arxiv.org/pdf/1904.06475](http://arxiv.org/pdf/1904.06475)

