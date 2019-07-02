---
layout: post
title: "Few-Shot Representation Learning for Out-Of-Vocabulary Words"
date: 2019-07-01 00:43:45
categories: arXiv_CL
tags: arXiv_CL Attention Embedding Represenation_Learning
author: Ziniu Hu, Ting Chen, Kai-Wei Chang, Yizhou Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Existing approaches for learning word embeddings often assume there are sufficient occurrences for each word in the corpus, such that the representation of words can be accurately estimated from their contexts. However, in real-world scenarios, out-of-vocabulary (a.k.a. OOV) words that do not appear in training corpus emerge frequently. It is challenging to learn accurate representations of these words with only a few observations. In this paper, we formulate the learning of OOV embeddings as a few-shot regression problem, and address it by training a representation function to predict the oracle embedding vector (defined as embedding trained with abundant observations) based on limited observations. Specifically, we propose a novel hierarchical attention-based architecture to serve as the neural regression function, with which the context information of a word is encoded and aggregated from K observations. Furthermore, our approach can leverage Model-Agnostic Meta-Learning (MAML) for adapting the learned model to the new corpus fast and robustly. Experiments show that the proposed approach significantly outperforms existing methods in constructing accurate embeddings for OOV words, and improves downstream tasks where these embeddings are utilized.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00505](http://arxiv.org/abs/1907.00505)

##### PDF
[http://arxiv.org/pdf/1907.00505](http://arxiv.org/pdf/1907.00505)

