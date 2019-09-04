---
layout: post
title: "Commonsense Knowledge Mining from Pretrained Models"
date: 2019-09-02 01:41:00
categories: arXiv_CL
tags: arXiv_CL Knowledge Language_Model Relation
author: Joshua Feldman, Joe Davison, Alexander M. Rush
mathjax: true
---

* content
{:toc}

##### Abstract
Inferring commonsense knowledge is a key challenge in natural language processing, but due to the sparsity of training data, previous work has shown that supervised methods for commonsense knowledge mining underperform when evaluated on novel data. In this work, we develop a method for generating commonsense knowledge using a large, pre-trained bidirectional language model. By transforming relational triples into masked sentences, we can use this model to rank a triple's validity by the estimated pointwise mutual information between the two entities. Since we do not update the weights of the bidirectional model, our approach is not biased by the coverage of any one commonsense knowledge base. Though this method performs worse on a test set than models explicitly trained on a corresponding training set, it outperforms these methods when mining commonsense knowledge from new sources, suggesting that unsupervised techniques may generalize better than current supervised approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00505](http://arxiv.org/abs/1909.00505)

##### PDF
[http://arxiv.org/pdf/1909.00505](http://arxiv.org/pdf/1909.00505)

