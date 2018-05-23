---
layout: post
title: "Planning to Give Information in Partially Observed Domains with a Learned Weighted Entropy Model"
date: 2018-05-21 19:16:02
categories: arXiv_AI
tags: arXiv_AI
author: Rohan Chitnis, Leslie Pack Kaelbling, Tomás Lozano-Pérez
mathjax: true
---

* content
{:toc}

##### Abstract
In many real-world robotic applications, an autonomous agent must act within and explore a partially observed environment that is unobserved by its human teammate. We consider such a setting in which the agent can, while acting, transmit declarative information to the human that helps them understand aspects of this unseen environment. Importantly, we should expect the human to have preferences about what information they are given and when they are given it. In this work, we adopt an information-theoretic view of the human's preferences: the human scores a piece of information as a function of the induced reduction in weighted entropy of their belief about the environment state. We formulate this setting as a POMDP and give a practical algorithm for solving it approximately. Then, we give an algorithm that allows the agent to sample-efficiently learn the human's preferences online. Finally, we describe an extension in which the human's preferences are time-varying. We validate our approach experimentally in two planning domains: a 2D robot mining task and a more realistic 3D robot fetching task.

##### Abstract (translated by Google)
在许多现实世界的机器人应用中，自主代理必须在其内部行动并探索其人类团队不可观察的部分观察环境。我们考虑这样一种设置，在这种设置中，代理可以在行事的同时向人类传送声明信息，以帮助他们理解这个看不见的环境的各个方面。重要的是，我们应该期待人们对他们给出的信息以及给予信息的时间有偏好。在这项工作中，我们采用了一个关于人类偏好的信息论视角：人类根据其对环境状态信念的加权熵的诱导减少来评分一条信息。我们将此设置制定为POMDP，并给出一个实用的算法来解决它。然后，我们给出一个算法，允许代理人在线上有效地学习人的喜好。最后，我们描述了一个扩展，其中人的偏好是随时间变化的。我们通过两个规划领域的实验验证了我们的方法：2D机器人挖掘任务和更逼真的3D机器人抓取任务。

##### URL
[https://arxiv.org/abs/1805.08263](https://arxiv.org/abs/1805.08263)

##### PDF
[https://arxiv.org/pdf/1805.08263](https://arxiv.org/pdf/1805.08263)

