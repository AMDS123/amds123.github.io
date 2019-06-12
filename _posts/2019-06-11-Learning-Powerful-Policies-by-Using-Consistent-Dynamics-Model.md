---
layout: post
title: "Learning Powerful Policies by Using Consistent Dynamics Model"
date: 2019-06-11 02:31:38
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Relation
author: Shagun Sodhani, Anirudh Goyal, Tristan Deleu, Yoshua Bengio, Sergey Levine, Jian Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Model-based Reinforcement Learning approaches have the promise of being sample efficient. Much of the progress in learning dynamics models in RL has been made by learning models via supervised learning. But traditional model-based approaches lead to `compounding errors' when the model is unrolled step by step. Essentially, the state transitions that the learner predicts (by unrolling the model for multiple steps) and the state transitions that the learner experiences (by acting in the environment) may not be consistent. There is enough evidence that humans build a model of the environment, not only by observing the environment but also by interacting with the environment. Interaction with the environment allows humans to carry out experiments: taking actions that help uncover true causal relationships which can be used for building better dynamics models. Analogously, we would expect such interactions to be helpful for a learning agent while learning to model the environment dynamics. In this paper, we build upon this intuition by using an auxiliary cost function to ensure consistency between what the agent observes (by acting in the real world) and what it imagines (by acting in the `learned' world). We consider several tasks - Mujoco based control tasks and Atari games - and show that the proposed approach helps to train powerful policies and better dynamics models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04355](http://arxiv.org/abs/1906.04355)

##### PDF
[http://arxiv.org/pdf/1906.04355](http://arxiv.org/pdf/1906.04355)

