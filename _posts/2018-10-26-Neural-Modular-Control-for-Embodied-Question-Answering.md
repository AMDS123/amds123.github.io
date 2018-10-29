---
layout: post
title: "Neural Modular Control for Embodied Question Answering"
date: 2018-10-26 03:58:26
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Abhishek Das, Georgia Gkioxari, Stefan Lee, Devi Parikh, Dhruv Batra
mathjax: true
---

* content
{:toc}

##### Abstract
We present a modular approach for learning policies for navigation over long planning horizons from language input. Our hierarchical policy operates at multiple timescales, where the higher-level master policy proposes subgoals to be executed by specialized sub-policies. Our choice of subgoals is compositional and semantic, i.e. they can be sequentially combined in arbitrary orderings, and assume human-interpretable descriptions (e.g. 'exit room', 'find kitchen', 'find refrigerator', etc.). 
 We use imitation learning to warm-start policies at each level of the hierarchy, dramatically increasing sample efficiency, followed by reinforcement learning. Independent reinforcement learning at each level of hierarchy enables sub-policies to adapt to consequences of their actions and recover from errors. Subsequent joint hierarchical training enables the master policy to adapt to the sub-policies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11181](http://arxiv.org/abs/1810.11181)

##### PDF
[http://arxiv.org/pdf/1810.11181](http://arxiv.org/pdf/1810.11181)

