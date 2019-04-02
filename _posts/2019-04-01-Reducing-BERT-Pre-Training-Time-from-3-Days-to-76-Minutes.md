---
layout: post
title: "Reducing BERT Pre-Training Time from 3 Days to 76 Minutes"
date: 2019-04-01 16:53:35
categories: arXiv_AI
tags: arXiv_AI Optimization Deep_Learning
author: Yang You, Jing Li, Jonathan Hseu, Xiaodan Song, James Demmel, Cho-Jui Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
Large-batch training is key to speeding up deep neural network training in large distributed systems. However, large-batch training is difficult because it produces a generalization gap. Straightforward optimization often leads to accuracy loss on the test set. BERT \cite{devlin2018bert} is a state-of-the-art deep learning model that builds on top of deep bidirectional transformers for language understanding. Previous large-batch training techniques do not perform well for BERT when we scale the batch size (e.g. beyond 8192). BERT pre-training also takes a long time to finish (around three days on 16 TPUv3 chips). To solve this problem, we propose the LAMB optimizer, which helps us to scale the batch size to 65536 without losing accuracy. LAMB is a general optimizer that works for both small and large batch sizes and does not need hyper-parameter tuning besides the learning rate. The baseline BERT-Large model needs 1 million iterations to finish pre-training, while LAMB with batch size 65536/32768 only needs 8599 iterations. We push the batch size to the memory limit of a TPUv3 pod and can finish BERT training in 76 minutes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00962](http://arxiv.org/abs/1904.00962)

##### PDF
[http://arxiv.org/pdf/1904.00962](http://arxiv.org/pdf/1904.00962)

