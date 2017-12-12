---
layout: post
title: "IQA: Visual Question Answering in Interactive Environments"
date: 2017-12-09 00:13:59
categories: arXiv_CV
tags: arXiv_CV QA Reinforcement_Learning VQA
author: Daniel Gordon, Aniruddha Kembhavi, Mohammad Rastegari, Joseph Redmon, Dieter Fox, Ali Farhadi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Interactive Question Answering (IQA), the task of answering questions that require an autonomous agent to interact with a dynamic visual environment. IQA presents the agent with a scene and a question, like: "Are there any apples in the fridge?" The agent must navigate around the scene, acquire visual understanding of scene elements, interact with objects (e.g. open refrigerators) and plan for a series of actions conditioned on the question. Popular reinforcement learning approaches with a single controller perform poorly on IQA owing to the large and diverse state space. We propose the Hierarchical Interactive Memory Network (HIMN) consisting of a factorized set of controllers, allowing the system to operate at multiple levels of temporal abstraction, reducing the diversity of the action space available to each controller and enabling an easier training paradigm. We introduce IQADATA, a new Interactive Question Answering dataset built upon AI2-THOR, a simulated photo-realistic environment of configurable indoor scenes with interactive objects. IQADATA has 75,000 questions, each paired with a unique scene configuration. Our experiments show that our proposed model outperforms popular single controller based methods on IQADATA.

##### Abstract (translated by Google)
我们介绍交互式问答（IQA），回答需要自主代理与动态视觉环境交互的问题。 IQA向代理人介绍一个场景和一个问题，如：“冰箱里有没有苹果？”代理人必须在现场四处导航，获得对场景元素的视觉理解，与对象（例如打开的冰箱）交互，并计划针对该问题的一系列行动。由于状态空间大而多样化，单个控制器的强化学习方法在IQA方面表现不佳。我们提出了分层交互记忆网络（HIMN）由工厂化组控制器，允许系统在时间上多个抽象层次上进行操作，减少了每个控制器提供的行动空间的多样性，实现更简单的训练模式。我们介绍IQADATA，这是一个基于AI2-THOR的新型交互式问题解答数据集，是一个模拟逼真的可配置室内场景交互式对象环境。 IQADATA有75,000个问题，每个问题都配有独特的场景配置。我们的实验表明，我们提出的模型胜过IQADATA上流行的基于单控制器的方法。

##### URL
[http://arxiv.org/abs/1712.03316](http://arxiv.org/abs/1712.03316)

##### PDF
[http://arxiv.org/pdf/1712.03316](http://arxiv.org/pdf/1712.03316)

