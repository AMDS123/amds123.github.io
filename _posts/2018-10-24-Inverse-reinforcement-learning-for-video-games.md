---
layout: post
title: "Inverse reinforcement learning for video games"
date: 2018-10-24 20:00:50
categories: arXiv_AI
tags: arXiv_AI Adversarial Reinforcement_Learning Embedding
author: Aaron Tucker, Adam Gleave, Stuart Russell
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning achieves superhuman performance in a range of video game environments, but requires that a designer manually specify a reward function. It is often easier to provide demonstrations of a target behavior than to design a reward function describing that behavior. Inverse reinforcement learning (IRL) algorithms can infer a reward from demonstrations in low-dimensional continuous control environments, but there has been little work on applying IRL to high-dimensional video games. In our CNN-AIRL baseline, we modify the state-of-the-art adversarial IRL (AIRL) algorithm to use CNNs for the generator and discriminator. To stabilize training, we normalize the reward and increase the size of the discriminator training dataset. We additionally learn a low-dimensional state representation using a novel autoencoder architecture tuned for video game environments. This embedding is used as input to the reward network, improving the sample efficiency of expert demonstrations. Our method achieves high-level performance on the simple Catcher video game, substantially outperforming the CNN-AIRL baseline. We also score points on the Enduro Atari racing game, but do not match expert performance, highlighting the need for further work.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10593](https://arxiv.org/abs/1810.10593)

##### PDF
[https://arxiv.org/pdf/1810.10593](https://arxiv.org/pdf/1810.10593)

