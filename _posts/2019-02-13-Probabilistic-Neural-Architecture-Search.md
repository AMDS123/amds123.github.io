---
layout: post
title: "Probabilistic Neural Architecture Search"
date: 2019-02-13 20:38:18
categories: arXiv_CV
tags: arXiv_CV NAS
author: Francesco Paolo Casale, Jonathan Gordon, Nicolo Fusi
mathjax: true
---

* content
{:toc}

##### Abstract
In neural architecture search (NAS), the space of neural network architectures is automatically explored to maximize predictive accuracy for a given task. Despite the success of recent approaches, most existing methods cannot be directly applied to large scale problems because of their prohibitive computational complexity or high memory usage. In this work, we propose a Probabilistic approach to neural ARchitecture SEarCh (PARSEC) that drastically reduces memory requirements while maintaining state-of-the-art computational complexity, making it possible to directly search over more complex architectures and larger datasets. Our approach only requires as much memory as is needed to train a single architecture from our search space. This is due to a memory-efficient sampling procedure wherein we learn a probability distribution over high-performing neural network architectures. Importantly, this framework enables us to transfer the distribution of architectures learnt on smaller problems to larger ones, further reducing the computational cost. We showcase the advantages of our approach in applications to CIFAR-10 and ImageNet, where our approach outperforms methods with double its computational cost and matches the performance of methods with costs that are three orders of magnitude larger.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1902.05116](https://arxiv.org/abs/1902.05116)

##### PDF
[https://arxiv.org/pdf/1902.05116](https://arxiv.org/pdf/1902.05116)

