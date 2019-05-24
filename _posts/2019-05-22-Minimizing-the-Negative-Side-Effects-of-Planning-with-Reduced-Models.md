---
layout: post
title: "Minimizing the Negative Side Effects of Planning with Reduced Models"
date: 2019-05-22 20:36:28
categories: arXiv_AI
tags: arXiv_AI
author: Sandhya Saisubramanian, Shlomo Zilberstein
mathjax: true
---

* content
{:toc}

##### Abstract
Reduced models of large Markov decision processes accelerate planning by considering a subset of outcomes for each state-action pair. This reduction in reachable states leads to replanning when the agent encounters states without a precomputed action during plan execution. However, not all states are suitable for replanning. In the worst case, the agent may not be able to reach the goal from the newly encountered state. Agents should be better prepared to handle such risky situations and avoid replanning in risky states. Hence, we consider replanning in states that are unsafe for deliberation as a negative side effect of planning with reduced models. While the negative side effects can be minimized by always using the full model, this defeats the purpose of using reduced models. The challenge is to plan with reduced models, but somehow account for the possibility of encountering risky situations. An agent should thus only replan in states that the user has approved as safe for replanning. To that end, we propose planning using a portfolio of reduced models, a planning paradigm that minimizes the negative side effects of planning using reduced models by alternating between different outcome selection approaches. We empirically demonstrate the effectiveness of our approach on three domains: an electric vehicle charging domain using real-world data from a university campus and two benchmark planning problems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09355](http://arxiv.org/abs/1905.09355)

##### PDF
[http://arxiv.org/pdf/1905.09355](http://arxiv.org/pdf/1905.09355)

