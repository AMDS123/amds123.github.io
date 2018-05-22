---
layout: post
title: "Autonomous discovery of the goal space to learn a parameterized skill"
date: 2018-05-19 08:18:39
categories: arXiv_AI
tags: arXiv_AI Face Relation
author: Emilio Cartoni, Gianluca Baldassarre
mathjax: true
---

* content
{:toc}

##### Abstract
A parameterized skill is a mapping from multiple goals/task parameters to the policy parameters to accomplish them. Existing works in the literature show how a parameterized skill can be learned given a task space that defines all the possible achievable goals. In this work, we focus on tasks defined in terms of final states (goals), and we face on the challenge where the agent aims to autonomously acquire a parameterized skill to manipulate an initially unknown environment. In this case, the task space is not known a priori and the agent has to autonomously discover it. The agent may posit as a task space its whole sensory space (i.e. the space of all possible sensor readings) as the achievable goals will certainly be a subset of this space. However, the space of achievable goals may be a very tiny subspace in relation to the whole sensory space, thus directly using the sensor space as task space exposes the agent to the curse of dimensionality and makes existing autonomous skill acquisition algorithms inefficient. In this work we present an algorithm that actively discovers the manifold of the achievable goals within the sensor space. We validate the algorithm by employing it in multiple different simulated scenarios where the agent actions achieve different types of goals: moving a redundant arm, pushing an object, and changing the color of an object.

##### Abstract (translated by Google)
参数化技能是从多个目标/任务参数到策略参数的映射，以实现它们。文献中的现有作品展示了如何在给定任务空间的情况下学习参数化技能，该任务空间定义了所有可能实现的目标。在这项工作中，我们专注于根据最终状态（目标）定义的任务，并且我们面临的挑战是代理人旨在自主获取参数化技能来操纵最初未知的环境。在这种情况下，任务空间并不是先验知道的，代理人必须自主发现它。代理可以将任务空间的整个感知空间（即所有可能的传感器读数的空间）作为可实现的目标肯定是该空间的子集。然而，实现目标的空间可能是与整个感官空间相关的非常小的子空间，因此直接使用传感器空间作为任务空间使代理暴露于维度灾难，并使得现有的自主技能获取算法效率低下。在这项工作中，我们提出一种算法，积极发现传感器空间内可实现目标的多样性。我们通过在多种不同的模拟场景中验证算法，其中代理操作实现不同类型的目标：移动冗余臂，推动对象以及更改对象的颜色。

##### URL
[https://arxiv.org/abs/1805.07547](https://arxiv.org/abs/1805.07547)

##### PDF
[https://arxiv.org/pdf/1805.07547](https://arxiv.org/pdf/1805.07547)

