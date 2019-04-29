---
layout: post
title: "Factored Contextual Policy Search with Bayesian Optimization"
date: 2019-04-26 11:04:26
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Robert Pinsler, Peter Karkus, Andras Kupcsik, David Hsu, Wee Sun Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Scarce data is a major challenge to scaling robot learning to truly complex tasks, as we need to generalize locally learned policies over different task contexts. Contextual policy search offers data-efficient learning and generalization by explicitly conditioning the policy on a parametric context space. In this paper, we further structure the contextual policy representation. We propose to factor contexts into two components: target contexts that describe the task objectives, e.g. target position for throwing a ball; and environment contexts that characterize the environment, e.g. initial position or mass of the ball. Our key observation is that experience can be directly generalized over target contexts. We show that this can be easily exploited in contextual policy search algorithms. In particular, we apply factorization to a Bayesian optimization approach to contextual policy search both in sampling-based and active learning settings. Our simulation results show faster learning and better generalization in various robotic domains. See our supplementary video: https://youtu.be/MNTbBAOufDY.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11761](http://arxiv.org/abs/1904.11761)

##### PDF
[http://arxiv.org/pdf/1904.11761](http://arxiv.org/pdf/1904.11761)

