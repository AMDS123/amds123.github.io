---
layout: post
title: "Deep Intrinsically Motivated Continuous Actor-Critic for Efficient Robotic Visuomotor Skill Learning"
date: 2018-10-26 15:32:32
categories: arXiv_AI
tags: arXiv_AI Sparse CNN
author: Muhammad Burhan Hafez, Cornelius Weber, Matthias Kerzel, Stefan Wermter
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a new intrinsically motivated actor-critic algorithm for learning continuous motor skills directly from raw visual input. Our neural architecture is composed of a critic and an actor network. Both networks receive the hidden representation of a deep convolutional autoencoder which is trained to reconstruct the visual input, while the centre-most hidden representation is also optimized to estimate the state value. Separately, an ensemble of predictive world models generates, based on its learning progress, an intrinsic reward signal which is combined with the extrinsic reward to guide the exploration of the actor-critic learner. Our approach is more data- efficient and inherently more stable than the existing actor-critic methods for continuous control from pixel data. We evaluate our algorithm for the task of learning robotic reaching and grasping skills on a realistic physics simulator and on a humanoid robot. The results show that the control policies learned with our approach can achieve better performance than the compared state-of-the-art and baseline algorithms in both dense-reward and challenging sparse-reward settings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11388](http://arxiv.org/abs/1810.11388)

##### PDF
[http://arxiv.org/pdf/1810.11388](http://arxiv.org/pdf/1810.11388)

