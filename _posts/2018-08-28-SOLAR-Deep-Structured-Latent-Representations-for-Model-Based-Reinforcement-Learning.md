---
layout: post
title: "SOLAR: Deep Structured Latent Representations for Model-Based Reinforcement Learning"
date: 2018-08-28 03:48:25
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Prediction
author: Marvin Zhang, Sharad Vikram, Laura Smith, Pieter Abbeel, Matthew J. Johnson, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Model-based reinforcement learning (RL) methods can be broadly categorized as global model methods, which depend on learning models that provide sensible predictions in a wide range of states, or local model methods, which iteratively refit simple models that are used for policy improvement. While predicting future states that will result from the current actions is difficult, local model methods only attempt to understand system dynamics in the neighborhood of the current policy, making it possible to produce local improvements without ever learning to predict accurately far into the future. The main idea in this paper is that we can learn representations that make it easy to retrospectively infer simple dynamics given the data from the current policy, thus enabling local models to be used for policy learning in complex systems. To that end, we focus on learning representations with probabilistic graphical model (PGM) structure, which allows us to devise an efficient local model method that infers dynamics from real-world rollouts with the PGM as a global prior. We compare our method to other model-based and model-free RL methods on a suite of robotics tasks, including manipulation tasks on a real Sawyer robotic arm directly from camera images. Videos of our results are available at https://sites.google.com/view/solar-iclips

##### Abstract (translated by Google)
基于模型的强化学习（RL）方法可以大致归类为全局模型方法，它依赖于在各种状态下提供合理预测的学习模型，或者本地模型方法，它们迭代地改进用于策略改进的简单模型。虽然预测当前行动将导致的未来状态很困难，但本地模型方法只是试图了解当前政策附近的系统动态，从而可以产生局部改进，而无需在未来学习准确预测。本文的主要思想是，我们可以学习表示，这些表示可以很容易地根据当前策略的数据回顾性地推断出简单的动态，从而使本地模型能够用于复杂系统中的策略学习。为此，我们专注于使用概率图形模型（PGM）结构学习表示，这使我们能够设计出一种有效的局部模型方法，该方法可以将PGM作为全局优先事项推断出真实世界推出的动态。我们将方法与其他基于模型和无模型的RL方法在一套机器人任务上进行比较，包括直接从摄像机图像在真正的Sawyer机器人手臂上进行操作任务。我们的结果视频可在https://sites.google.com/view/solar-iclips上找到

##### URL
[http://arxiv.org/abs/1808.09105](http://arxiv.org/abs/1808.09105)

##### PDF
[http://arxiv.org/pdf/1808.09105](http://arxiv.org/pdf/1808.09105)

