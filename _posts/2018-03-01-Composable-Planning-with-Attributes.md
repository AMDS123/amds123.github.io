---
layout: post
title: "Composable Planning with Attributes"
date: 2018-03-01 17:21:03
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Amy Zhang, Adam Lerer, Sainbayar Sukhbaatar, Rob Fergus, Arthur Szlam
mathjax: true
---

* content
{:toc}

##### Abstract
The tasks that an agent will need to solve often are not known during training. However, if the agent knows which properties of the environment are important then, after learning how its actions affect those properties, it may be able to use this knowledge to solve complex tasks without training specifically for them. Towards this end, we consider a setup in which an environment is augmented with a set of user defined attributes that parameterize the features of interest. We propose a method that learns a policy for transitioning between "nearby" sets of attributes, and maintains a graph of possible transitions. Given a task at test time that can be expressed in terms of a target set of attributes, and a current state, our model infers the attributes of the current state and searches over paths through attribute space to get a high level plan, and then uses its low level policy to execute the plan. We show in 3D block stacking, grid-world games, and StarCraft that our model is able to generalize to longer, more complex tasks at test time by composing simpler learned policies.

##### Abstract (translated by Google)
培训期间，代理人经常需要解决的任务不得而知。然而，如果代理知道哪些环境属性是重要的，那么在了解其行为如何影响这些属性之后，它可以使用这些知识来解决复杂的任务，而无需专门为他们提供培训。为此，我们考虑一个设置，在该设置中，通过一组用户定义的属性来增强环境，从而对感兴趣的功能进行参数化。我们提出了一种方法，用于了解在“附近”属性集之间转换的策略，并维护可能转换的图形。给定一个测试时间的任务，可以用一组目标属性和一个当前状态来表示，我们的模型推断当前状态的属性，并通过属性空间搜索路径以获取高级计划，然后使用其低层政策执行计划。我们在3D块堆叠，网格世界游戏和星际争霸中展示我们的模型能够通过构建更简单的学习策略，在测试时间推广到更长，更复杂的任务。

##### URL
[http://arxiv.org/abs/1803.00512](http://arxiv.org/abs/1803.00512)

##### PDF
[http://arxiv.org/pdf/1803.00512](http://arxiv.org/pdf/1803.00512)

