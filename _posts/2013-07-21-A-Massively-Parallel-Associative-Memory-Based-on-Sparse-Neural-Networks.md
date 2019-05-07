---
layout: post
title: "A Massively Parallel Associative Memory Based on Sparse Neural Networks"
date: 2013-07-21 14:29:21
categories: arXiv_CV
tags: arXiv_CV Sparse Face Detection Recognition Face_Recognition
author: Zhe Yao, Vincent Gripon, Michael G. Rabbat
mathjax: true
---

* content
{:toc}

##### Abstract
Associative memories store content in such a way that the content can be later retrieved by presenting the memory with a small portion of the content, rather than presenting the memory with an address as in more traditional memories. Associative memories are used as building blocks for algorithms within database engines, anomaly detection systems, compression algorithms, and face recognition systems. A classical example of an associative memory is the Hopfield neural network. Recently, Gripon and Berrou have introduced an alternative construction which builds on ideas from the theory of error correcting codes and which greatly outperforms the Hopfield network in capacity, diversity, and efficiency. In this paper we implement a variation of the Gripon-Berrou associative memory on a general purpose graphical processing unit (GPU). The work of Gripon and Berrou proposes two retrieval rules, sum-of-sum and sum-of-max. The sum-of-sum rule uses only matrix-vector multiplication and is easily implemented on the GPU. The sum-of-max rule is much less straightforward to implement because it involves non-linear operations. However, the sum-of-max rule gives significantly better retrieval error rates. We propose a hybrid rule tailored for implementation on a GPU which achieves a 880-fold speedup without sacrificing any accuracy.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1303.7032](https://arxiv.org/abs/1303.7032)

##### PDF
[https://arxiv.org/pdf/1303.7032](https://arxiv.org/pdf/1303.7032)

