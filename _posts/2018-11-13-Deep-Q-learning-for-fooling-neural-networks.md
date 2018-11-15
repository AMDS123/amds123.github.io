---
layout: post
title: "Deep Q learning for fooling neural networks"
date: 2018-11-13 20:23:37
categories: arXiv_AI
tags: arXiv_AI Adversarial Reinforcement_Learning Deep_Learning
author: Mandar Kulkarni
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models are vulnerable to external attacks. In this paper, we propose a Reinforcement Learning (RL) based approach to generate adversarial examples for the pre-trained (target) models. We assume a semi black-box setting where the only access an adversary has to the target model is the class probabilities obtained for the input queries. We train a Deep Q Network (DQN) agent which, with experience, learns to attack only a small portion of image pixels to generate non-targeted adversarial images. Initially, an agent explores an environment by sequentially modifying random sets of image pixels and observes its effect on the class probabilities. At the end of an episode, it receives a positive (negative) reward if it succeeds (fails) to alter the label of the image. Experimental results with MNIST, CIFAR-10 and Imagenet datasets demonstrate that our RL framework is able to learn an effective attack policy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05521](http://arxiv.org/abs/1811.05521)

##### PDF
[http://arxiv.org/pdf/1811.05521](http://arxiv.org/pdf/1811.05521)

