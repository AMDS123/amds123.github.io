---
layout: post
title: "On the Pitfalls of Measuring Emergent Communication"
date: 2019-03-12 19:33:49
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Survey Quantitative Detection Recommendation
author: Ryan Lowe, Jakob Foerster, Y-Lan Boureau, Joelle Pineau, Yann Dauphin
mathjax: true
---

* content
{:toc}

##### Abstract
How do we know if communication is emerging in a multi-agent system? The vast majority of recent papers on emergent communication show that adding a communication channel leads to an increase in reward or task success. This is a useful indicator, but provides only a coarse measure of the agent's learned communication abilities. As we move towards more complex environments, it becomes imperative to have a set of finer tools that allow qualitative and quantitative insights into the emergence of communication. This may be especially useful to allow humans to monitor agents' behaviour, whether for fault detection, assessing performance, or even building trust. In this paper, we examine a few intuitive existing metrics for measuring communication, and show that they can be misleading. Specifically, by training deep reinforcement learning agents to play simple matrix games augmented with a communication channel, we find a scenario where agents appear to communicate (their messages provide information about their subsequent action), and yet the messages do not impact the environment or other agent in any way. We explain this phenomenon using ablation studies and by visualizing the representations of the learned policies. We also survey some commonly used metrics for measuring emergent communication, and provide recommendations as to when these metrics should be used.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05168](http://arxiv.org/abs/1903.05168)

##### PDF
[http://arxiv.org/pdf/1903.05168](http://arxiv.org/pdf/1903.05168)

