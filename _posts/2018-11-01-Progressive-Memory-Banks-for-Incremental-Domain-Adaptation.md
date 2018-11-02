---
layout: post
title: "Progressive Memory Banks for Incremental Domain Adaptation"
date: 2018-11-01 05:22:01
categories: arXiv_AI
tags: arXiv_AI Attention RNN
author: Nabiha Asghar, Lili Mou, Kira A. Selby, Kevin D. Pantasdo, Pascal Poupart, Xin Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of incremental domain adaptation (IDA). We assume each domain comes one after another, and that we could only access data in the current domain. The goal of IDA is to build a unified model performing well on all the domains that we have encountered. We propose to augment a recurrent neural network (RNN) with a directly parameterized memory bank, which is retrieved by an attention mechanism at each step of RNN transition. The memory bank provides a natural way of IDA: when adapting our model to a new domain, we progressively add new slots to the memory bank, which increases the number of parameters, and thus the model capacity. We learn the new memory slots and fine-tune existing parameters by back-propagation. Experimental results show that our approach achieves significantly better performance than fine-tuning alone, which suffers from the catastrophic forgetting problem. Compared with expanding hidden states, our approach is more robust for old domains, shown by both empirical and theoretical results. Our model also outperforms previous work of IDA including elastic weight consolidation (EWC) and the progressive neural network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00239](http://arxiv.org/abs/1811.00239)

##### PDF
[http://arxiv.org/pdf/1811.00239](http://arxiv.org/pdf/1811.00239)

