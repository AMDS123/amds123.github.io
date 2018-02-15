---
layout: post
title: "Specification Inference from Demonstrations"
date: 2018-02-14 06:03:22
categories: arXiv_AI
tags: arXiv_AI Attention Inference
author: Marcell Vazquez-Chanlatte, Susmit Jha, Ashish Tiwari, Sanjit A. Seshia
mathjax: true
---

* content
{:toc}

##### Abstract
Learning from expert demonstrations has received a lot of attention in artificial intelligence and machine learning. The goal is to infer the underlying reward function that an agent is optimizing given a set of observations of the agent's behavior over time in a variety of circumstances, the system state trajectories, and a plant model specifying the evolution of the system state for different agent's actions. The system is often modeled as a Markov decision process, that is, the next state depends only on the current state and agent's action, and the the agent's choice of action depends only on the current state. While the former is a Markovian assumption on the evolution of system state, the later assumes that the target reward function is itself Markovian. In this work, we explore learning a class of non-Markovian reward functions, known in the formal methods literature as specifications. These specifications offer better composition, transferability, and interpretability. We then show that inferring the specification can be done efficiently without unrolling the transition system. We demonstrate on a 2-d grid world example.

##### Abstract (translated by Google)
学习专家示范在人工智能和机器学习方面受到了很多关注。目标是在各种情况下，根据一系列随时间推移的代理行为的观察结果，系统状态轨迹和指定不同代理的系统状态演化的工厂模型，推断代理正在优化的基础奖励函数动作。该系统通常被建模为马尔可夫决策过程，即下一个状态仅取决于当前状态和代理的行为，而代理的行动选择仅取决于当前状态。前者是系统状态演化的马尔可夫假设，后者假设目标回报函数本身就是马尔可夫。在这项工作中，我们探索学习一类非马尔可夫奖励函数，在正式方法文献中称为规范。这些规格提供了更好的组成，可转移性和可解释性。然后，我们表明，推断规范可以高效地完成，无需展开转换系统。我们在一个2-D网格世界的例子中演示。

##### URL
[http://arxiv.org/abs/1710.03875](http://arxiv.org/abs/1710.03875)

##### PDF
[http://arxiv.org/pdf/1710.03875](http://arxiv.org/pdf/1710.03875)

