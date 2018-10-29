---
layout: post
title: "Sample-Efficient Learning of Nonprehensile Manipulation Policies via Physics-Based Informed State Distributions"
date: 2018-10-24 23:49:58
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Lerrel Pinto, Aditya Mandalika, Brian Hou, Siddhartha Srinivasa
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a sample-efficient yet simple approach to learning closed-loop policies for nonprehensile manipulation. Although reinforcement learning (RL) can learn closed-loop policies without requiring access to underlying physics models, it suffers from poor sample complexity on challenging tasks. To overcome this problem, we leverage rearrangement planning to provide an informative physics-based prior on the environment's optimal state-visitation distribution. Specifically, we present a new technique, Learning with Planned Episodic Resets (LeaPER), that resets the environment's state to one informed by the prior during the learning phase. We experimentally show that LeaPER significantly outperforms traditional RL approaches by a factor of up to 5X on simulated rearrangement. Further, we relax dynamics from quasi-static to welded contacts to illustrate that LeaPER is robust to the use of simpler physics models. Finally, LeaPER's closed-loop policies significantly improve task success rates relative to both open-loop controls with a planned path or simple feedback controllers that track open-loop trajectories. We demonstrate the performance and behavior of LeaPER on a physical 7-DOF manipulator in this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10654](https://arxiv.org/abs/1810.10654)

##### PDF
[https://arxiv.org/pdf/1810.10654](https://arxiv.org/pdf/1810.10654)

