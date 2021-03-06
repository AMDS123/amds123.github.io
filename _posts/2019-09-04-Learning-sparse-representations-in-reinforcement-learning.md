---
layout: post
title: "Learning sparse representations in reinforcement learning"
date: 2019-09-04 06:58:32
categories: arXiv_AI
tags: arXiv_AI Sparse GAN Reinforcement_Learning
author: Jacob Rafati, David C. Noelle
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning (RL) algorithms allow artificial agents to improve their selection of actions to increase rewarding experiences in their environments. Temporal Difference (TD) Learning -- a model-free RL method -- is a leading account of the midbrain dopamine system and the basal ganglia in reinforcement learning. These algorithms typically learn a mapping from the agent's current sensed state to a selected action (known as a policy function) via learning a value function (expected future rewards). TD Learning methods have been very successful on a broad range of control tasks, but learning can become intractably slow as the state space of the environment grows. This has motivated methods that learn internal representations of the agent's state, effectively reducing the size of the state space and restructuring state representations in order to support generalization. However, TD Learning coupled with an artificial neural network, as a function approximator, has been shown to fail to learn some fairly simple control tasks, challenging this explanation of reward-based learning. We hypothesize that such failures do not arise in the brain because of the ubiquitous presence of lateral inhibition in the cortex, producing sparse distributed internal representations that support the learning of expected future reward. The sparse conjunctive representations can avoid catastrophic interference while still supporting generalization. We provide support for this conjecture through computational simulations, demonstrating the benefits of learned sparse representations for three problematic classic control tasks: Puddle-world, Mountain-car, and Acrobot.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01575](http://arxiv.org/abs/1909.01575)

##### PDF
[http://arxiv.org/pdf/1909.01575](http://arxiv.org/pdf/1909.01575)

