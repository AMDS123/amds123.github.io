---
layout: post
title: "Auto-Keras: An Efficient Neural Architecture Search System"
date: 2019-03-26 04:38:37
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Haifeng Jin, Qingquan Song, Xia Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural architecture search (NAS) has been proposed to automatically tune deep neural networks, but existing search algorithms, e.g., NASNet, PNAS, usually suffer from expensive computational cost. Network morphism, which keeps the functionality of a neural network while changing its neural architecture, could be helpful for NAS by enabling more efficient training during the search. In this paper, we propose a novel framework enabling Bayesian optimization to guide the network morphism for efficient neural architecture search. The framework develops a neural network kernel and a tree-structured acquisition function optimization algorithm to efficiently explores the search space. Intensive experiments on real-world benchmark datasets have been done to demonstrate the superior performance of the developed framework over the state-of-the-art methods. Moreover, we build an open-source AutoML system based on our method, namely Auto-Keras. The system runs in parallel on CPU and GPU, with an adaptive search strategy for different GPU memory limits.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.10282](http://arxiv.org/abs/1806.10282)

##### PDF
[http://arxiv.org/pdf/1806.10282](http://arxiv.org/pdf/1806.10282)

