---
layout: post
title: "An Imitation Learning Approach to Unsupervised Parsing"
date: 2019-06-05 19:45:21
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Reinforcement_Learning Inference RNN Language_Model
author: Bowen Li, Lili Mou, Frank Keller
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, there has been an increasing interest in unsupervised parsers that optimize semantically oriented objectives, typically using reinforcement learning. Unfortunately, the learned trees often do not match actual syntax trees well. Shen et al. (2018) propose a structured attention mechanism for language modeling (PRPN), which induces better syntactic structures but relies on ad hoc heuristics. Also, their model lacks interpretability as it is not grounded in parsing actions. In our work, we propose an imitation learning approach to unsupervised parsing, where we transfer the syntactic knowledge induced by the PRPN to a Tree-LSTM model with discrete parsing actions. Its policy is then refined by Gumbel-Softmax training towards a semantically oriented objective. We evaluate our approach on the All Natural Language Inference dataset and show that it achieves a new state of the art in terms of parsing $F$-score, outperforming our base models, including the PRPN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02276](http://arxiv.org/abs/1906.02276)

##### PDF
[http://arxiv.org/pdf/1906.02276](http://arxiv.org/pdf/1906.02276)

