---
layout: post
title: "Memory Augmented Neural Network Adaptive Controllers: Performance and Stability"
date: 2019-05-07 22:40:30
categories: arXiv_CV
tags: arXiv_CV
author: Deepan Muthirayan, Pramod P. Khargonekar
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel control architecture, inspired from neuroscience, for adaptive control of continuous-time systems. The proposed architecture, in the setting of standard neural network (NN) based adaptive control, augments an external working memory to the NN. The external working memory, through a write operation, stores certain recently observed feature vectors from the hidden layer of the NN. It retrieves relevant vectors from the working memory to modify the final control signal generated by the controller. The use of external working memory is aimed at improving the context thereby inducing the learning system to search in a particular direction. This directed learning allows the learning system to find a good approximation of the unknown function even after abrupt changes quickly. A key objective explored in this paper is to design control architectures and algorithms that can learn and adapt quickly to changes that are even abrupt. We consider two classes of controllers for concrete development of our ideas (i) a model reference NN adaptive controller for linear systems with matched uncertainty (ii) robot arm controller. We prove that the resulting controllers lead to Uniformly Ulitmately Bounded (UUB) stable closed loop systems. We provide a detailed illustration of the working of this learning mechanism through a simple example. Through extensive simulations and specific metrics we also show that memory augmentation improves learning significantly even when the system undergoes sudden changes. Importantly, we also provide evidence for the proposed mechanism by which this specific memory augmentation improves learning.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.02832](https://arxiv.org/abs/1905.02832)

##### PDF
[https://arxiv.org/pdf/1905.02832](https://arxiv.org/pdf/1905.02832)

