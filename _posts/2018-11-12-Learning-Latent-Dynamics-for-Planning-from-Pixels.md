---
layout: post
title: "Learning Latent Dynamics for Planning from Pixels"
date: 2018-11-12 04:30:10
categories: arXiv_AI
tags: arXiv_AI Sparse Inference
author: Danijar Hafner, Timothy Lillicrap, Ian Fischer, Ruben Villegas, David Ha, Honglak Lee, James Davidson
mathjax: true
---

* content
{:toc}

##### Abstract
Planning has been very successful for control tasks with known environment dynamics. To leverage planning in unknown environments, the agent needs to learn the dynamics from interactions with the world. However, learning dynamics models that are accurate enough for planning has been a long-standing challenge, especially in image-based domains. We propose the Deep Planning Network (PlaNet), a purely model-based agent that learns the environment dynamics from pixels and chooses actions through online planning in latent space. To achieve high performance, the dynamics model must accurately predict the rewards ahead for multiple time steps. We approach this problem using a latent dynamics model with both deterministic and stochastic transition function and a generalized variational inference objective that we name latent overshooting. Using only pixel observations, our agent solves continuous control tasks with contact dynamics, partial observability, and sparse rewards. PlaNet uses significantly fewer episodes and reaches final performance close to and sometimes higher than top model-free algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04551](http://arxiv.org/abs/1811.04551)

##### PDF
[http://arxiv.org/pdf/1811.04551](http://arxiv.org/pdf/1811.04551)

