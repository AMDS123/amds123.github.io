---
layout: post
title: "Repurposing Entailment for Multi-Hop Question Answering Tasks"
date: 2019-04-20 00:30:26
categories: arXiv_AI
tags: arXiv_AI QA
author: Harsh Trivedi, Heeyoung Kwon, Tushar Khot, Ashish Sabharwal, Niranjan Balasubramanian
mathjax: true
---

* content
{:toc}

##### Abstract
Question Answering (QA) naturally reduces to an entailment problem, namely, verifying whether some text entails the answer to a question. However, for multi-hop QA tasks, which require reasoning with multiple sentences, it remains unclear how best to utilize entailment models pre-trained on large scale datasets such as SNLI, which are based on sentence pairs. We introduce Multee, a general architecture that can effectively use entailment models for multi-hop QA tasks. Multee uses (i) a local module that helps locate important sentences, thereby avoiding distracting information, and (ii) a global module that aggregates information by effectively incorporating importance weights. Importantly, we show that both modules can use entailment functions pre-trained on a large scale NLI datasets. We evaluate performance on MultiRC and OpenBookQA, two multihop QA datasets. When using an entailment function pre-trained on NLI datasets, Multee outperforms QA models trained only on the target QA datasets and the OpenAI transformer models. The code is available at https://github.com/StonyBrookNLP/multee.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09380](http://arxiv.org/abs/1904.09380)

##### PDF
[http://arxiv.org/pdf/1904.09380](http://arxiv.org/pdf/1904.09380)

