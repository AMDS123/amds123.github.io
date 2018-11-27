---
layout: post
title: "Incremental learning abstract discrete planning domains and mappings to continuous perceptions"
date: 2018-11-26 10:55:58
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Luciano Serafini, Paolo Traverso
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the works on planning and learning, e.g., planning by (model based) reinforcement learning, are based on two main assumptions: (i) the set of states of the planning domain is fixed; (ii) the mapping between the observations from the real word and the states is implicitly assumed or learned offline, and it is not part of the planning domain. Consequently, the focus is on learning the transitions between states. In this paper, we drop such assumptions. We provide a formal framework in which (i) the agent can learn dynamically new states of the planning domain; (ii) the mapping between abstract states and the perception from the real world, represented by continuous variables, is part of the planning domain; (iii) such mapping is learned and updated along the "life" of the agent. We define an algorithm that interleaves planning, acting, and learning, and allows the agent to update the planning domain depending on how much it trusts the model w.r.t. the new experiences learned by executing actions. We define a measure of coherence between the planning domain and the real world as perceived by the agent. We test our approach showing that the agent learns increasingly coherent models, and that the system can scale to deal with models with an order of $10^6$ states.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07096](http://arxiv.org/abs/1810.07096)

##### PDF
[http://arxiv.org/pdf/1810.07096](http://arxiv.org/pdf/1810.07096)

