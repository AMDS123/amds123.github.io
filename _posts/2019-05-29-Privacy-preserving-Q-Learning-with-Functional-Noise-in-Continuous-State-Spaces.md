---
layout: post
title: "Privacy-preserving Q-Learning with Functional Noise in Continuous State Spaces"
date: 2019-05-29 07:36:18
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Baoxiang Wang, Nidhi Hegde
mathjax: true
---

* content
{:toc}

##### Abstract
We consider differentially private algorithms for reinforcement learning in continuous state spaces, such that neighboring reward functions are indistinguishable. Existing studies that guarantee differential privacy are not extendable to infinite state spaces, since the noise level to ensure privacy will scale accordingly to infinity. Our aim is to protect the privacy for the value function approximator, without regard to the number of states queried to the function. We add functional noise to the value function iteratively in the training. We show rigorous privacy guarantees by a series of analyses on the kernel of the noise space, the probabilistic bound of such noise samples, and the composition of the noise. We gain insight into the utility analysis by proving the algorithm's approximate optimality, under the discrete state space setting. Experiments corroborate our theoretical findings and show improvement over existing methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10634](http://arxiv.org/abs/1901.10634)

##### PDF
[http://arxiv.org/pdf/1901.10634](http://arxiv.org/pdf/1901.10634)

