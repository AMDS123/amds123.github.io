---
layout: post
title: "Goal-conditioned Imitation Learning"
date: 2019-06-13 17:39:52
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Yiming Ding, Carlos Florensa, Mariano Phielipp, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Designing rewards for Reinforcement Learning (RL) is challenging because it needs to convey the desired task, be efficient to optimize, and be easy to compute. The latter is particularly problematic when applying RL to robotics, where detecting whether the desired configuration is reached might require considerable supervision and instrumentation. Furthermore, we are often interested in being able to reach a wide range of configurations, hence setting up a different reward every time might be unpractical. Methods like Hindsight Experience Replay (HER) have recently shown promise to learn policies able to reach many goals, without the need of a reward. Unfortunately, without tricks like resetting to points along the trajectory, HER might take a very long time to discover how to reach certain areas of the state-space. In this work we investigate different approaches to incorporate demonstrations to drastically speed up the convergence to a policy able to reach any goal, also surpassing the performance of an agent trained with other Imitation Learning algorithms. Furthermore, our method can be used when only trajectories without expert actions are available, which can leverage kinestetic or third person demonstration. The code is available at this https URL .

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05838](https://arxiv.org/abs/1906.05838)

##### PDF
[https://arxiv.org/pdf/1906.05838](https://arxiv.org/pdf/1906.05838)

