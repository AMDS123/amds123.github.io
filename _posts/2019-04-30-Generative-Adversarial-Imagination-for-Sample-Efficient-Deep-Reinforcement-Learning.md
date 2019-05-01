---
layout: post
title: "Generative Adversarial Imagination for Sample Efficient Deep Reinforcement Learning"
date: 2019-04-30 13:53:29
categories: arXiv_AI
tags: arXiv_AI Adversarial Reinforcement_Learning Deep_Learning
author: Kacper Kielak
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning has seen great advancements in the past five years. The successful introduction of deep learning in place of more traditional methods allowed reinforcement learning to scale to very complex domains achieving super-human performance in environments like the game of Go or numerous video games. Despite great successes in multiple domains, these new methods suffer from their own issues that make them often inapplicable to the real world problems. Extreme lack of data efficiency, together with huge variance and difficulty in enforcing safety constraints, is one of the three most prominent issues in the field. Usually, millions of data points sampled from the environment are necessary for these algorithms to converge to acceptable policies. 
 This thesis proposes novel Generative Adversarial Imaginative Reinforcement Learning algorithm. It takes advantage of the recent introduction of highly effective generative adversarial models, and Markov property that underpins reinforcement learning setting, to model dynamics of the real environment within the internal imagination module. Rollouts from the imagination are then used to artificially simulate the real environment in a standard reinforcement learning process to avoid, often expensive and dangerous, trial and error in the real environment. Experimental results show that the proposed algorithm more economically utilises experience from the real environment than the current state-of-the-art Rainbow DQN algorithm, and thus makes an important step towards sample efficient deep reinforcement learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.13255](http://arxiv.org/abs/1904.13255)

##### PDF
[http://arxiv.org/pdf/1904.13255](http://arxiv.org/pdf/1904.13255)

