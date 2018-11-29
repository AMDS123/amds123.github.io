---
layout: post
title: "Prioritizing Starting States for Reinforcement Learning"
date: 2018-11-27 22:40:01
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Relation
author: Arash Tavakoli, Vitaly Levdik, Riashat Islam, Petar Kormushev
mathjax: true
---

* content
{:toc}

##### Abstract
Online, off-policy reinforcement learning algorithms are able to use an experience memory to remember and replay past experiences. In prior work, this approach was used to stabilize training by breaking the temporal correlations of the updates and avoiding the rapid forgetting of possibly rare experiences. In this work, we propose a conceptually simple framework that uses an experience memory to help exploration by prioritizing the starting states from which the agent starts acting in the environment, importantly, in a fashion that is also compatible with on-policy algorithms. Given the capacity to restart the agent in states corresponding to its past observations, we achieve this objective by (i) enabling the agent to restart in states belonging to significant past experiences (e.g., nearby goals), and (ii) promoting faster coverage of the state space through starting from a more diverse set of states. While, using a good measure of priority to identify significant past transitions, we expect case (i) to more considerably help exploration in certain problems (e.g., sparse reward tasks), we hypothesize that case (ii) will generally be beneficial, even without any prioritization. We show empirically that our approach improves learning performance for both off-policy and on-policy deep reinforcement learning methods, with the most notable improvement in a significantly sparse reward task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11298](http://arxiv.org/abs/1811.11298)

##### PDF
[http://arxiv.org/pdf/1811.11298](http://arxiv.org/pdf/1811.11298)

