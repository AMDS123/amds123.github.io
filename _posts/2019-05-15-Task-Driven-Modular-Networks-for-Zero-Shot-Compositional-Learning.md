---
layout: post
title: "Task-Driven Modular Networks for Zero-Shot Compositional Learning"
date: 2019-05-15 01:29:08
categories: arXiv_CV
tags: arXiv_CV Knowledge Classification
author: Senthil Purushwalkam, Maximilian Nickel, Abhinav Gupta, Marc&#x27;Aurelio Ranzato
mathjax: true
---

* content
{:toc}

##### Abstract
One of the hallmarks of human intelligence is the ability to compose learned knowledge into novel concepts which can be recognized without a single training example. In contrast, current state-of-the-art methods require hundreds of training examples for each possible category to build reliable and accurate classifiers. To alleviate this striking difference in efficiency, we propose a task-driven modular architecture for compositional reasoning and sample efficient learning. Our architecture consists of a set of neural network modules, which are small fully connected layers operating in semantic concept space. These modules are configured through a gating function conditioned on the task to produce features representing the compatibility between the input image and the concept under consideration. This enables us to express tasks as a combination of sub-tasks and to generalize to unseen categories by reweighting a set of small modules. Furthermore, the network can be trained efficiently as it is fully differentiable and its modules operate on small sub-spaces. We focus our study on the problem of compositional zero-shot classification of object-attribute categories. We show in our experiments that current evaluation metrics are flawed as they only consider unseen object-attribute pairs. When extending the evaluation to the generalized setting which accounts also for pairs seen during training, we discover that naive baseline methods perform similarly or better than current approaches. However, our modular network is able to outperform all existing approaches on two widely-used benchmark datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.05908](http://arxiv.org/abs/1905.05908)

##### PDF
[http://arxiv.org/pdf/1905.05908](http://arxiv.org/pdf/1905.05908)

