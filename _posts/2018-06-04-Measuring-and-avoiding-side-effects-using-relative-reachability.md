---
layout: post
title: "Measuring and avoiding side effects using relative reachability"
date: 2018-06-04 16:30:17
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Victoria Krakovna, Laurent Orseau, Miljan Martic, Shane Legg
mathjax: true
---

* content
{:toc}

##### Abstract
How can we design reinforcement learning agents that avoid causing unnecessary disruptions to their environment? We argue that current approaches to penalizing side effects can introduce bad incentives in tasks that require irreversible actions, and in environments that contain sources of change other than the agent. For example, some approaches give the agent an incentive to prevent any irreversible changes in the environment, including the actions of other agents. We introduce a general definition of side effects, based on relative reachability of states compared to a default state, that avoids these undesirable incentives. Using a set of gridworld experiments illustrating relevant scenarios, we empirically compare relative reachability to penalties based on existing definitions and show that it is the only penalty among those tested that produces the desired behavior in all the scenarios.

##### Abstract (translated by Google)
我们如何设计强化学习代理，避免对其环境造成不必要的破坏？我们认为，目前惩罚副作用的方法可能会对需要不可逆转行动的任务以及包含代理以外变化源的环境造成不良的激励。例如，一些方法为代理人提供了激励措施，以防止环境中的任何不可逆转的变化，包括其他代理人的行为。我们引入副作用的一般定义，基于状态相对于默认状态的相对可达性，避免了这些不良的激励。使用一组演示相关情景的网格世界实验，我们通过实证比较相对可达性和基于现有定义的处罚，并表明它是在所有情景中产生期望行为的那些测试中唯一的惩罚。

##### URL
[http://arxiv.org/abs/1806.01186](http://arxiv.org/abs/1806.01186)

##### PDF
[http://arxiv.org/pdf/1806.01186](http://arxiv.org/pdf/1806.01186)

