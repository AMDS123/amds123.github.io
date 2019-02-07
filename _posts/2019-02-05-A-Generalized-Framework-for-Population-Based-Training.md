---
layout: post
title: "A Generalized Framework for Population Based Training"
date: 2019-02-05 20:11:17
categories: arXiv_AI
tags: arXiv_AI
author: Ang Li, Ola Spyra, Sagi Perel, Valentin Dalibard, Max Jaderberg, Chenjie Gu, David Budden, Tim Harley, Pramod Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Population Based Training (PBT) is a recent approach that jointly optimizes neural network weights and hyperparameters which periodically copies weights of the best performers and mutates hyperparameters during training. Previous PBT implementations have been synchronized glass-box systems. We propose a general, black-box PBT framework that distributes many asynchronous "trials" (a small number of training steps with warm-starting) across a cluster, coordinated by the PBT controller. The black-box design does not make assumptions on model architectures, loss functions or training procedures. Our system supports dynamic hyperparameter schedules to optimize both differentiable and non-differentiable metrics. We apply our system to train a state-of-the-art WaveNet generative model for human voice synthesis. We show that our PBT system achieves better accuracy, less sensitivity and faster convergence compared to existing methods, given the same computational resource.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01894](http://arxiv.org/abs/1902.01894)

##### PDF
[http://arxiv.org/pdf/1902.01894](http://arxiv.org/pdf/1902.01894)

