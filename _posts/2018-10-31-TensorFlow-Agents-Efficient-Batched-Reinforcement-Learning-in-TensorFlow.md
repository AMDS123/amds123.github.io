---
layout: post
title: "TensorFlow Agents: Efficient Batched Reinforcement Learning in TensorFlow"
date: 2018-10-31 20:11:05
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Danijar Hafner, James Davidson, Vincent Vanhoucke
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce TensorFlow Agents, an efficient infrastructure paradigm for building parallel reinforcement learning algorithms in TensorFlow. We simulate multiple environments in parallel, and group them to perform the neural network computation on a batch rather than individual observations. This allows the TensorFlow execution engine to parallelize computation, without the need for manual synchronization. Environments are stepped in separate Python processes to progress them in parallel without interference of the global interpreter lock. As part of this project, we introduce BatchPPO, an efficient implementation of the proximal policy optimization algorithm. By open sourcing TensorFlow Agents, we hope to provide a flexible starting point for future projects that accelerates future research in the field.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.02878](http://arxiv.org/abs/1709.02878)

##### PDF
[http://arxiv.org/pdf/1709.02878](http://arxiv.org/pdf/1709.02878)

