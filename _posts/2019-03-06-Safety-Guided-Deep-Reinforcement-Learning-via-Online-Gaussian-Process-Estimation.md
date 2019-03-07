---
layout: post
title: "Safety-Guided Deep Reinforcement Learning via Online Gaussian Process Estimation"
date: 2019-03-06 18:02:08
categories: arXiv_AI
tags: arXiv_AI Face Reinforcement_Learning
author: Jiameng Fan, Wenchao Li
mathjax: true
---

* content
{:toc}

##### Abstract
An important facet of reinforcement learning (RL) has to do with how the agent goes about exploring the environment. Traditional exploration strategies typically focus on efficiency and ignore safety. However, for practical applications, ensuring safety of the agent during exploration is crucial since performing an unsafe action or reaching an unsafe state could result in irreversible damage to the agent. The main challenge of safe exploration is that characterizing the unsafe states and actions is difficult for large continuous state or action spaces and unknown environments. In this paper, we propose a novel approach to incorporate estimations of safety to guide exploration and policy search in deep reinforcement learning. By using a cost function to capture trajectory-based safety, our key idea is to formulate the state-action value function of this safety cost as a candidate Lyapunov function and extend control-theoretic results to approximate its derivative using online Gaussian Process (GP) estimation. We show how to use these statistical models to guide the agent in unknown environments to obtain high-performance control policies with provable stability certificates.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02526](http://arxiv.org/abs/1903.02526)

##### PDF
[http://arxiv.org/pdf/1903.02526](http://arxiv.org/pdf/1903.02526)

