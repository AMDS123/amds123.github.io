---
layout: post
title: "RedSync : Reducing Synchronization Traffic for Distributed Deep Learning"
date: 2019-07-22 09:48:26
categories: arXiv_CV
tags: arXiv_CV Attention Image_Classification Optimization Classification Deep_Learning Language_Model
author: Jiarui Fang, Haohuan Fu, Guangwen Yang, Cho-Jui Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
Data parallelism has become a dominant method to scale Deep Neural Network (DNN) training across multiple nodes. Since synchronizing a large number of gradients of the local model can be a bottleneck for large-scale distributed training, compressing communication data has gained widespread attention recently. Among several recent proposed compression algorithms, Residual Gradient Compression (RGC) is one of the most successful approaches---it can significantly compress the transmitting message size (0.1\% of the gradient size) of each node and still achieve correct accuracy and the same convergence speed. However, the literature on compressing deep networks focuses almost exclusively on achieving good theoretical compression rate, while the efficiency of RGC in real distributed implementation has been less investigated. In this paper, we develop an RGC-based system that is able to reduce the end-to-end training time on real-world multi-GPU systems. Our proposed design called RedSync, which introduces a set of optimizations to reduce communication bandwidth requirement while introducing limited overhead. We evaluate the performance of RedSync on two different multiple GPU platforms, including 128 GPUs of a supercomputer and an 8-GPU server. Our test cases include image classification tasks on Cifar10 and ImageNet, and language modeling tasks on Penn Treebank and Wiki2 datasets. For DNNs featured with high communication to computation ratio, which have long been considered with poor scalability, RedSync brings significant performance improvements.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.04357](http://arxiv.org/abs/1808.04357)

##### PDF
[http://arxiv.org/pdf/1808.04357](http://arxiv.org/pdf/1808.04357)

