---
layout: post
title: "Value constrained model-free continuous control"
date: 2019-02-12 20:31:43
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Optimization
author: Steven Bohez, Abbas Abdolmaleki, Michael Neunert, Jonas Buchli, Nicolas Heess, Raia Hadsell
mathjax: true
---

* content
{:toc}

##### Abstract
The naive application of Reinforcement Learning algorithms to continuous control problems -- such as locomotion and manipulation -- often results in policies which rely on high-amplitude, high-frequency control signals, known colloquially as bang-bang control. Although such solutions may indeed maximize task reward, they can be unsuitable for real world systems. Bang-bang control may lead to increased wear and tear or energy consumption, and tends to excite undesired second-order dynamics. To counteract this issue, multi-objective optimization can be used to simultaneously optimize both the reward and some auxiliary cost that discourages undesired (e.g. high-amplitude) control. In principle, such an approach can yield the sought after, smooth, control policies. It can, however, be hard to find the correct trade-off between cost and return that results in the desired behavior. In this paper we propose a new constraint-based reinforcement learning approach that ensures task success while minimizing one or more auxiliary costs (such as control effort). We employ Lagrangian relaxation to learn both (a) the parameters of a control policy that satisfies the desired constraints and (b) the Lagrangian multipliers for the optimization. Moreover, we demonstrate that we can satisfy constraints either in expectation or in a per-step fashion, and can even learn a single policy that is able to dynamically trade-off between return and cost. We demonstrate the efficacy of our approach using a number of continuous control benchmark tasks, a realistic, energy-optimized quadruped locomotion task, as well as a reaching task on a real robot arm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04623](http://arxiv.org/abs/1902.04623)

##### PDF
[http://arxiv.org/pdf/1902.04623](http://arxiv.org/pdf/1902.04623)

