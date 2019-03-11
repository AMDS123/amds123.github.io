---
layout: post
title: "Penalizing side effects using stepwise relative reachability"
date: 2019-03-08 09:17:21
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Victoria Krakovna, Laurent Orseau, Ramana Kumar, Miljan Martic, Shane Legg
mathjax: true
---

* content
{:toc}

##### Abstract
How can we design safe reinforcement learning agents that avoid unnecessary disruptions to their environment? We show that current approaches to penalizing side effects can introduce bad incentives, e.g. to prevent any irreversible changes in the environment, including the actions of other agents. To isolate the source of such undesirable incentives, we break down side effects penalties into two components: a baseline state and a measure of deviation from this baseline state. We argue that some of these incentives arise from the choice of baseline, and others arise from the choice of deviation measure. We introduce a new variant of the stepwise inaction baseline and a new deviation measure based on relative reachability of states. The combination of these design choices avoids the given undesirable incentives, while simpler baselines and the unreachability measure fail. We demonstrate this empirically by comparing different combinations of baseline and deviation measure choices on a set of gridworld experiments designed to illustrate possible bad incentives.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.01186](http://arxiv.org/abs/1806.01186)

##### PDF
[http://arxiv.org/pdf/1806.01186](http://arxiv.org/pdf/1806.01186)

