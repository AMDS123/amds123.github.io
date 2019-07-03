---
layout: post
title: "Generalizing from a few environments in safety-critical reinforcement learning"
date: 2019-07-02 16:12:34
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Zachary Kenton, Angelos Filos, Owain Evans, Yarin Gal
mathjax: true
---

* content
{:toc}

##### Abstract
Before deploying autonomous agents in the real world, we need to be confident they will perform safely in novel situations. Ideally, we would expose agents to a very wide range of situations during training, allowing them to learn about every possible danger, but this is often impractical. This paper investigates safety and generalization from a limited number of training environments in deep reinforcement learning (RL). We find RL algorithms can fail dangerously on unseen test environments even when performing perfectly on training environments. Firstly, in a gridworld setting, we show that catastrophes can be significantly reduced with simple modifications, including ensemble model averaging and the use of a blocking classifier. In the more challenging CoinRun environment we find similar methods do not significantly reduce catastrophes. However, we do find that the uncertainty information from the ensemble is useful for predicting whether a catastrophe will occur within a few steps and hence whether human intervention should be requested.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01475](http://arxiv.org/abs/1907.01475)

##### PDF
[http://arxiv.org/pdf/1907.01475](http://arxiv.org/pdf/1907.01475)

