---
layout: post
title: "Tuffy: Scaling up Statistical Inference in Markov Logic Networks using an RDBMS"
date: 2011-04-16 08:52:25
categories: arXiv_CV
tags: arXiv_CV Inference Relation
author: Feng Niu (University of Wisconsin-Madison), Christopher Ré (University of Wisconsin-Madison), AnHai Doan (University of Wisconsin-Madison), Jude Shavlik (University of Wisconsin-Madison)
mathjax: true
---

* content
{:toc}

##### Abstract
Markov Logic Networks (MLNs) have emerged as a powerful framework that combines statistical and logical reasoning; they have been applied to many data intensive problems including information extraction, entity resolution, and text mining. Current implementations of MLNs do not scale to large real-world data sets, which is preventing their wide-spread adoption. We present Tuffy that achieves scalability via three novel contributions: (1) a bottom-up approach to grounding that allows us to leverage the full power of the relational optimizer, (2) a novel hybrid architecture that allows us to perform AI-style local search efficiently using an RDBMS, and (3) a theoretical insight that shows when one can (exponentially) improve the efficiency of stochastic local search. We leverage (3) to build novel partitioning, loading, and parallel algorithms. We show that our approach outperforms state-of-the-art implementations in both quality and speed on several publicly available datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1104.3216](https://arxiv.org/abs/1104.3216)

##### PDF
[https://arxiv.org/pdf/1104.3216](https://arxiv.org/pdf/1104.3216)

