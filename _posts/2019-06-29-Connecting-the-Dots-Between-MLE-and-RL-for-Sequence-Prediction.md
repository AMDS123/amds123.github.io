---
layout: post
title: "Connecting the Dots Between MLE and RL for Sequence Prediction"
date: 2019-06-29 19:44:06
categories: arXiv_AI
tags: arXiv_AI Summarization Reinforcement_Learning Optimization Prediction
author: Bowen Tan, Zhiting Hu, Zichao Yang, Ruslan Salakhutdinov, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence prediction models can be learned from example sequences with a variety of training algorithms. Maximum likelihood learning is simple and efficient, yet can suffer from compounding error at test time. Reinforcement learning such as policy gradient addresses the issue but can have prohibitively poor exploration efficiency. A rich set of other algorithms such as RAML, SPG, and data noising, have also been developed from different perspectives. This paper establishes a formal connection between these algorithms. We present a generalized entropy regularized policy optimization formulation, and show that the apparently distinct algorithms can all be reformulated as special instances of the framework, with the only difference being the configurations of a reward function and a couple of hyperparameters. The unified interpretation offers a systematic view of the varying properties of exploration and learning efficiency. Besides, inspired from the framework, we present a new algorithm that dynamically interpolates among the family of algorithms for scheduled sequence model learning. Experiments on machine translation, text summarization, and game imitation learning demonstrate the superiority of the proposed algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09740](http://arxiv.org/abs/1811.09740)

##### PDF
[http://arxiv.org/pdf/1811.09740](http://arxiv.org/pdf/1811.09740)

