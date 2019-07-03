---
layout: post
title: "Conservative Q-Improvement: Reinforcement Learning for an Interpretable Decision-Tree Policy"
date: 2019-07-02 05:51:04
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Aaron M. Roth, Nicholay Topin, Pooyan Jamshidi, Manuela Veloso
mathjax: true
---

* content
{:toc}

##### Abstract
There is a growing desire in the field of reinforcement learning (and machine learning in general) to move from black-box models toward more "interpretable AI." We improve interpretability of reinforcement learning by increasing the utility of decision tree policies learned via reinforcement learning. These policies consist of a decision tree over the state space, which requires fewer parameters to express than traditional policy representations. Existing methods for creating decision tree policies via reinforcement learning focus on accurately representing an action-value function during training, but this leads to much larger trees than would otherwise be required. To address this shortcoming, we propose a novel algorithm which only increases tree size when the estimated discounted future reward of the overall policy would increase by a sufficient amount. Through evaluation in a simulated environment, we show that its performance is comparable or superior to traditional tree-based approaches and that it yields a more succinct policy. Additionally, we discuss tuning parameters to control the tradeoff between optimizing for smaller tree size or for overall reward.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01180](http://arxiv.org/abs/1907.01180)

##### PDF
[http://arxiv.org/pdf/1907.01180](http://arxiv.org/pdf/1907.01180)

