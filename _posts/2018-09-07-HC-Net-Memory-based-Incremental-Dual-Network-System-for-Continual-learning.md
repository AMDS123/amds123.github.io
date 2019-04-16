---
layout: post
title: "HC-Net: Memory-based Incremental Dual-Network System for Continual learning"
date: 2018-09-07 12:39:13
categories: arXiv_CV
tags: arXiv_CV Classification
author: Jangho Kim, Jeesoo Kim, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
Training a neural network for a classification task typically assumes that the data to train are given from the beginning. However, in the real world, additional data accumulate gradually and the model requires additional training without accessing the old training data. This usually leads to the catastrophic forgetting problem which is inevitable for the traditional training methodology of neural networks. In this paper, we propose a memory-based continual learning method that is able to learn additional tasks while retaining the performance of previously learned tasks. Composed of two complementary networks, the Hippocampus-net (H-net) and the Cortex-net (C-net), our model estimates the index of the corresponding task for an input sample and utilizes a particular portion of itself with the estimated index. The C-net guarantees no degradation in the performance of the previously learned tasks and the H-net shows high confidence in finding the origin of the input sample

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.02441](https://arxiv.org/abs/1809.02441)

##### PDF
[https://arxiv.org/pdf/1809.02441](https://arxiv.org/pdf/1809.02441)

