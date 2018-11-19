---
layout: post
title: "On the Complexity of Exploration in Goal-Driven Navigation"
date: 2018-11-16 16:17:27
categories: arXiv_AI
tags: arXiv_AI Sparse Optimization Relation
author: Maruan Al-Shedivat, Lisa Lee, Ruslan Salakhutdinov, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Building agents that can explore their environments intelligently is a challenging open problem. In this paper, we make a step towards understanding how a hierarchical design of the agent's policy can affect its exploration capabilities. First, we design EscapeRoom environments, where the agent must figure out how to navigate to the exit by accomplishing a number of intermediate tasks (\emph{subgoals}), such as finding keys or opening doors. Our environments are procedurally generated and vary in complexity, which can be controlled by the number of subgoals and relationships between them. Next, we propose to measure the complexity of each environment by constructing dependency graphs between the goals and analytically computing \emph{hitting times} of a random walk in the graph. We empirically evaluate Proximal Policy Optimization (PPO) with sparse and shaped rewards, a variation of policy sketches, and a hierarchical version of PPO (called HiPPO) akin to h-DQN. We show that analytically estimated \emph{hitting time} in goal dependency graphs is an informative metric of the environment complexity. We conjecture that the result should hold for environments other than navigation. Finally, we show that solving environments beyond certain level of complexity requires hierarchical approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06889](http://arxiv.org/abs/1811.06889)

##### PDF
[http://arxiv.org/pdf/1811.06889](http://arxiv.org/pdf/1811.06889)

