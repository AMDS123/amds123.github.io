---
layout: post
title: "Stochastic Latent Actor-Critic: Deep Reinforcement Learning with a Latent Variable Model"
date: 2019-07-01 17:45:09
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Represenation_Learning
author: Alex X. Lee, Anusha Nagabandi, Pieter Abbeel, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning (RL) algorithms can use high-capacity deep networks to learn directly from image observations. However, these kinds of observation spaces present a number of challenges in practice, since the policy must now solve two problems: a representation learning problem, and a task learning problem. In this paper, we aim to explicitly learn representations that can accelerate reinforcement learning from images. We propose the stochastic latent actor-critic (SLAC) algorithm: a sample-efficient and high-performing RL algorithm for learning policies for complex continuous control tasks directly from high-dimensional image inputs. SLAC learns a compact latent representation space using a stochastic sequential latent variable model, and then learns a critic model within this latent space. By learning a critic within a compact state space, SLAC can learn much more efficiently than standard RL methods. The proposed model improves performance substantially over alternative representations as well, such as variational autoencoders. In fact, our experimental evaluation demonstrates that the sample efficiency of our resulting method is comparable to that of model-based RL methods that directly use a similar type of model for control. Furthermore, our method outperforms both model-free and model-based alternatives in terms of final performance and sample efficiency, on a range of difficult image-based control tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00953](http://arxiv.org/abs/1907.00953)

##### PDF
[http://arxiv.org/pdf/1907.00953](http://arxiv.org/pdf/1907.00953)

