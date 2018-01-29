---
layout: post
title: "Safe Exploration in Continuous Action Spaces"
date: 2018-01-26 11:11:18
categories: arXiv_AI
tags: arXiv_AI GAN Reinforcement_Learning
author: Gal Dalal, Krishnamurthy Dvijotham, Matej Vecerik, Todd Hester, Cosmin Paduraru, Yuval Tassa
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of deploying a reinforcement learning (RL) agent on a physical system such as a datacenter cooling unit or robot, where critical constraints must never be violated. We show how to exploit the typically smooth dynamics of these systems and enable RL algorithms to never violate constraints during learning. Our technique is to directly add to the policy a safety layer that analytically solves an action correction formulation per each state. The novelty of obtaining an elegant closed-form solution is attained due to a linearized model, learned on past trajectories consisting of arbitrary actions. This is to mimic the real-world circumstances where data logs were generated with a behavior policy that is implausible to describe mathematically; such cases render the known safety-aware off-policy methods inapplicable. We demonstrate the efficacy of our approach on new representative physics-based environments, and prevail where reward shaping fails by maintaining zero constraint violations.

##### Abstract (translated by Google)
我们解决了在物理系统（如数据中心冷却单元或机器人）上部署强化学习（RL）代理的问题，在这种系统中绝不能违反关键约束条件。我们展示了如何利用这些系统的典型平滑动力学，并使RL算法在学习过程中从不违反约束条件。我们的技术是直接为政策添加一个安全层，以分析的方式解决每个州的行为修正公式。获得一个优雅的封闭形式的解决方案的新颖性是由于一个线性化的模型，学习过去的任意行动组成的轨迹。这是为了模拟数据日志生成的真实世界环境，其行为策略难以用数学描述;这种情况使得已知的安全意识到的关闭策略方法不适用。我们证明了我们的方法在基于新的代表性物理的环境中的有效性，并且通过维持零约束违规而成为奖励失败的优势。

##### URL
[http://arxiv.org/abs/1801.08757](http://arxiv.org/abs/1801.08757)

##### PDF
[http://arxiv.org/pdf/1801.08757](http://arxiv.org/pdf/1801.08757)

