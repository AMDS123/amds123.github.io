---
layout: post
title: "Counterfactual Critic Multi-Agent Training for Scene Graph Generation"
date: 2019-08-09 13:08:58
categories: arXiv_CV
tags: arXiv_CV Relation
author: Long Chen, Hanwang Zhang, Jun Xiao, Xiangnan He, Shiliang Pu, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Scene graphs -- objects as nodes and visual relationships as edges -- describe the whereabouts and interactions of the things and stuff in an image for comprehensive scene understanding. To generate coherent scene graphs, almost all existing methods exploit the fruitful visual context by modeling message passing among objects, fitting the dynamic nature of reasoning with visual context, eg, "person" on "bike" can help to determine the relationship "ride", which in turn contributes to the category confidence of the two objects. However, we argue that the scene dynamics is not properly learned by using the prevailing cross-entropy based supervised learning paradigm, which is not sensitive to graph inconsistency: errors at the hub or non-hub nodes are unfortunately penalized equally. To this end, we propose a Counterfactual critic Multi-Agent Training (CMAT) approach to resolve the mismatch. CMAT is a multi-agent policy gradient method that frames objects as cooperative agents, and then directly maximizes a graph-level metric as the reward. In particular, to assign the reward properly to each agent, CMAT uses a counterfactual baseline that disentangles the agent-specific reward by fixing the dynamics of other agents. Extensive validations on the challenging Visual Genome benchmark show that CMAT achieves a state-of-the-art by significant performance gains under various settings and metrics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02347](http://arxiv.org/abs/1812.02347)

##### PDF
[http://arxiv.org/pdf/1812.02347](http://arxiv.org/pdf/1812.02347)

