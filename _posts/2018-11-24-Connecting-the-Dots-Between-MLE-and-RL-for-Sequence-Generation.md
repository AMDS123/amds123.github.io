---
layout: post
title: "Connecting the Dots Between MLE and RL for Sequence Generation"
date: 2018-11-24 01:33:39
categories: arXiv_AI
tags: arXiv_AI Summarization Reinforcement_Learning Optimization
author: Bowen Tan, Zhiting Hu, Zichao Yang, Ruslan Salakhutdinov, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence generation models such as recurrent networks can be trained with a diverse set of learning algorithms. For example, maximum likelihood learning is simple and efficient, yet suffers from the exposure bias problem. Reinforcement learning like policy gradient addresses the problem but can have prohibitively poor exploration efficiency. A variety of other algorithms such as RAML, SPG, and data noising, have also been developed from different perspectives. This paper establishes a formal connection between these algorithms. We present a generalized entropy regularized policy optimization formulation, and show that the apparently divergent algorithms can all be reformulated as special instances of the framework, with the only difference being the configurations of reward function and a couple of hyperparameters. The unified interpretation offers a systematic view of the varying properties of exploration and learning efficiency. Besides, based on the framework, we present a new algorithm that dynamically interpolates among the existing algorithms for improved learning. Experiments on machine translation and text summarization demonstrate the superiority of the proposed algorithm.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.09740](https://arxiv.org/abs/1811.09740)

##### PDF
[https://arxiv.org/pdf/1811.09740](https://arxiv.org/pdf/1811.09740)

