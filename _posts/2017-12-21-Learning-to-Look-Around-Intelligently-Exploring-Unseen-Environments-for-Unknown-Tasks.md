---
layout: post
title: "Learning to Look Around: Intelligently Exploring Unseen Environments for Unknown Tasks"
date: 2017-12-21 17:11:10
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Recognition
author: Dinesh Jayaraman, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
It is common to implicitly assume access to intelligently captured inputs (e.g., photos from a human photographer), yet autonomously capturing good observations is itself a major challenge. We address the problem of learning to look around: if a visual agent has the ability to voluntarily acquire new views to observe its environment, how can it learn efficient exploratory behaviors to acquire informative observations? We propose a reinforcement learning solution, where the agent is rewarded for actions that reduce its uncertainty about the unobserved portions of its environment. Based on this principle, we develop a recurrent neural network-based approach to perform active completion of panoramic natural scenes and 3D object shapes. Crucially, the learned policies are not tied to any recognition task nor to the particular semantic content seen during training. As a result, 1) the learned "look around" behavior is relevant even for new tasks in unseen environments, and 2) training data acquisition involves no manual labeling. Through tests in diverse settings, we demonstrate that our approach learns useful generic policies that transfer to new unseen tasks and environments. Completion episodes are shown at https://goo.gl/BgWX3W.

##### Abstract (translated by Google)
隐含地假定访问智能捕获的输入（例如来自人类摄影师的照片）是常见的，但是自主捕获良好的观察本身是一个主要挑战。我们解决了学习问题：如果一个视觉代理人有能力自发地获得新的观点来观察它的环境，那么它如何学习有效的探索行为来获取信息性的观察结果呢？我们提出了一个强化学习解决方案，在这个解决方案中，代理人被奖励的行为可以减少其未被察觉的环境部分的不确定性。基于这一原则，我们开发了一种基于循环的神经网络的方法来执行全景自然场景和3D物体形状的主动完成。至关重要的是，学到的政策并不与任何识别任务相关，也不与训练期间看到的特定语义内容相关联。因此，1）即使对于看不见的环境中的新任务，学习到的“环视”行为也是相关的，2）训练数据采集不涉及人工标记。通过在不同环境下的测试，我们证明了我们的方法学习了转移到新的看不见的任务和环境的有用的通用策略。完成剧集显示在https://goo.gl/BgWX3W。

##### URL
[http://arxiv.org/abs/1709.00507](http://arxiv.org/abs/1709.00507)

##### PDF
[http://arxiv.org/pdf/1709.00507](http://arxiv.org/pdf/1709.00507)

