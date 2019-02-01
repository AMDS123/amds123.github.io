---
layout: post
title: "Visual Hindsight Experience Replay"
date: 2019-01-31 18:50:44
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Himanshu Sahni, Toby Buckley, Pieter Abbeel, Ilya Kuzovkin
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement Learning algorithms typically require millions of environment interactions to learn successful policies in sparse reward settings. Hindsight Experience Replay (HER) was introduced as a technique to increase sample efficiency through re-imagining unsuccessful trajectories as successful ones by replacing the originally intended goals. However, this method is not applicable to visual domains where the goal configuration is unknown and must be inferred from observation. In this work, we show how unsuccessful visual trajectories can be hallucinated to be successful using a generative model trained on relatively few snapshots of the goal. As far as we are aware, this is the first work that does so with the agent policy conditioned solely on its state. We then apply this model to training reinforcement learning agents in discrete and continuous settings. We show results on a navigation and pick-and-place task in a 3D environment and on a simulated robotics application. Our method shows marked improvement over standard RL algorithms and baselines derived from prior work.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11529](http://arxiv.org/abs/1901.11529)

##### PDF
[http://arxiv.org/pdf/1901.11529](http://arxiv.org/pdf/1901.11529)

