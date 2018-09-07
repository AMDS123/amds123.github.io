---
layout: post
title: "IQA: Visual Question Answering in Interactive Environments"
date: 2018-09-06 17:05:18
categories: arXiv_CV
tags: arXiv_CV QA Reinforcement_Learning VQA
author: Daniel Gordon, Aniruddha Kembhavi, Mohammad Rastegari, Joseph Redmon, Dieter Fox, Ali Farhadi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Interactive Question Answering (IQA), the task of answering questions that require an autonomous agent to interact with a dynamic visual environment. IQA presents the agent with a scene and a question, like: "Are there any apples in the fridge?" The agent must navigate around the scene, acquire visual understanding of scene elements, interact with objects (e.g. open refrigerators) and plan for a series of actions conditioned on the question. Popular reinforcement learning approaches with a single controller perform poorly on IQA owing to the large and diverse state space. We propose the Hierarchical Interactive Memory Network (HIMN), consisting of a factorized set of controllers, allowing the system to operate at multiple levels of temporal abstraction. To evaluate HIMN, we introduce IQUAD V1, a new dataset built upon AI2-THOR, a simulated photo-realistic environment of configurable indoor scenes with interactive objects (code and dataset available at https://github.com/danielgordon10/thor-iqa-cvpr-2018). IQUAD V1 has 75,000 questions, each paired with a unique scene configuration. Our experiments show that our proposed model outperforms popular single controller based methods on IQUAD V1. For sample questions and results, please view our video: https://youtu.be/pXd3C-1jr98

##### Abstract (translated by Google)
我们引入了交互式问答（IQA），这是回答需要自主代理与动态视觉环境交互的问题的任务。 IQA向代理人展示了一个场景和一个问题，例如：“冰箱里有苹果吗？”代理必须在场景中导航，获得场景元素的视觉理解，与对象（例如开放式冰箱）交互并计划以问题为条件的一系列动作。由于状态空间庞大且多样化，使用单个控制器的流行强化学习方法在IQA上表现不佳。我们提出了分层交互存储器网络（HIMN），它由一组分解的控制器组成，允许系统在多个时间抽象层次上运行。为了评估HIMN，我们介绍了IQUAD V1，这是一个基于AI2-THOR的新数据集，一个模拟的照片般逼真的环境，带有交互式对象的可配置室内场景（代码和数据集可在https://github.com/danielgordon10/thor-iqa获得） -cvpr-2018）。 IQUAD V1有75,000个问题，每个问题都配有独特的场景配置。我们的实验表明，我们提出的模型优于IQUAD V1上流行的基于单一控制器的方法。有关示例问题和结果，请查看我们的视频：https：//youtu.be/pXd3C-1jr98

##### URL
[http://arxiv.org/abs/1712.03316](http://arxiv.org/abs/1712.03316)

##### PDF
[http://arxiv.org/pdf/1712.03316](http://arxiv.org/pdf/1712.03316)

