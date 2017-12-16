---
layout: post
title: "Learning to look around"
date: 2017-09-01 23:34:29
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Inference
author: Dinesh Jayaraman, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
Visual perception requires not only making inferences from observations, but also making decisions about what to observe. Though much of the computer vision literature implicitly assumes a well-captured visual observation as input, in reality a single view of a complex visual environment---or even multiple arbitrarily chosen views---may provide too little information for perception tasks. We aim to address the problem of "learning to look around" in the first place. Specifically, in a setting where a visual agent has the ability to voluntarily acquire new views to observe its environment, how can we train it to exhibit efficient exploratory behaviors to acquire informative observations? We treat this as a reinforcement learning problem, where a system is rewarded for actions that reduce its uncertainty about the unobserved portions of its environment. Based on this principle, we develop recurrent neural network-based systems to perform active completion of panoramic natural scenes and 3-D object shapes. Crucially, the learned policies are not closely tied to the particular semantic content seen during training; as a result, 1) the learned "look around" behavior is relevant even for new tasks in unseen environments, and 2) training data acquisition involves no manual labeling. Through tests in diverse settings, we demonstrate that our system learns useful and generic exploratory policies that transfer to new unseen tasks, an important step for autonomous embodied visual agents.

##### Abstract (translated by Google)
视觉感知不仅需要从观察结果中作出推断，还需要做出关于观察结果的决定。尽管大部分的计算机视觉文献都隐含地把视觉观察作为输入，但实际上对复杂的视觉环境 - 甚至是多个任意选择的视图的单一视图 - 可能为感知任务提供的信息太少。我们的目标是首先解决“学习四处看看”的问题。具体而言，在一个视觉代理人有能力自愿获取新视图来观察其环境的环境中，我们如何训练它以展现有效的探索行为来获取信息性观察？我们将此视为一个强化学习问题，在这个问题中，一个系统被奖励的行为可以减少它对未被察觉的环境部分的不确定性。基于这个原理，我们开发了基于循环的神经网络的系统来执行全景自然场景和三维物体形状的主动完成。至关重要的是，学到的政策并没有紧密联系在训练期间看到的特定语义内容。因此，1）即使对于看不见的环境中的新任务，学习到的“环视”行为也是相关的，2）训练数据采集不涉及手动标记。通过在不同环境中的测试，我们证明我们的系统学习有用和通用的探索性策略，转移到新的看不见的任务，这是自主体现视觉代理的重要一步。

##### URL
[https://arxiv.org/abs/1709.00507](https://arxiv.org/abs/1709.00507)

##### PDF
[https://arxiv.org/pdf/1709.00507](https://arxiv.org/pdf/1709.00507)

