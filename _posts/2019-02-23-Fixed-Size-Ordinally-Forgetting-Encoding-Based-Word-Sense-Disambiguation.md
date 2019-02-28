---
layout: post
title: "Fixed-Size Ordinally Forgetting Encoding Based Word Sense Disambiguation"
date: 2019-02-23 00:22:58
categories: arXiv_CL
tags: arXiv_CL Embedding Classification Language_Model
author: Xi Zhu, Mingbin Xu, Hui Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present our method of using fixed-size ordinally forgetting encoding (FOFE) to solve the word sense disambiguation (WSD) problem. FOFE enables us to encode variable-length sequence of words into a theoretically unique fixed-size representation that can be fed into a feed forward neural network (FFNN), while keeping the positional information between words. In our method, a FOFE-based FFNN is used to train a pseudo language model over unlabelled corpus, then the pre-trained language model is capable of abstracting the surrounding context of polyseme instances in labelled corpus into context embeddings. Next, we take advantage of these context embeddings towards WSD classification. We conducted experiments on several WSD data sets, which demonstrates that our proposed method can achieve comparable performance to that of the state-of-the-art approach at the expense of much lower computational cost.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10246](http://arxiv.org/abs/1902.10246)

##### PDF
[http://arxiv.org/pdf/1902.10246](http://arxiv.org/pdf/1902.10246)

