---
layout: post
title: "TF-Replicator: Distributed Machine Learning for Researchers"
date: 2019-02-01 17:26:07
categories: arXiv_AI
tags: arXiv_AI GAN Reinforcement_Learning Classification
author: Peter Buchlovsky, David Budden, Dominik Grewe, Chris Jones, John Aslanides, Frederic Besse, Andy Brock, Aidan Clark, Sergio G&#xf3;mez Colmenarejo, Aedan Pope, Fabio Viola, Dan Belov
mathjax: true
---

* content
{:toc}

##### Abstract
We describe TF-Replicator, a framework for distributed machine learning designed for DeepMind researchers and implemented as an abstraction over TensorFlow. TF-Replicator simplifies writing data-parallel and model-parallel research code. The same models can be effortlessly deployed to different cluster architectures (i.e. one or many machines containing CPUs, GPUs or TPU accelerators) using synchronous or asynchronous training regimes. To demonstrate the generality and scalability of TF-Replicator, we implement and benchmark three very different models: (1) A ResNet-50 for ImageNet classification, (2) a SN-GAN for class-conditional ImageNet image generation, and (3) a D4PG reinforcement learning agent for continuous control. Our results show strong scalability performance without demanding any distributed systems expertise of the user. The TF-Replicator programming model will be open-sourced as part of TensorFlow 2.0 (see https://github.com/tensorflow/community/pull/25).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00465](http://arxiv.org/abs/1902.00465)

##### PDF
[http://arxiv.org/pdf/1902.00465](http://arxiv.org/pdf/1902.00465)

