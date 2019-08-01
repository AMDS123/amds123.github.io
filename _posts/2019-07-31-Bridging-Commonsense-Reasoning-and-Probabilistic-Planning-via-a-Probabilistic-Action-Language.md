---
layout: post
title: "Bridging Commonsense Reasoning and Probabilistic Planning via a Probabilistic Action Language"
date: 2019-07-31 15:29:44
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Yi Wang, Shiqi Zhang, Joohyung Lee
mathjax: true
---

* content
{:toc}

##### Abstract
To be responsive to dynamically changing real-world environments, an intelligent agent needs to perform complex sequential decision-making tasks that are often guided by commonsense knowledge. The previous work on this line of research led to the framework called "interleaved commonsense reasoning and probabilistic planning" (icorpp), which used P-log for representing commmonsense knowledge and Markov Decision Processes (MDPs) or Partially Observable MDPs (POMDPs) for planning under uncertainty. A main limitation of icorpp is that its implementation requires non-trivial engineering efforts to bridge the commonsense reasoning and probabilistic planning formalisms. In this paper, we present a unified framework to integrate icorpp's reasoning and planning components. In particular, we extend probabilistic action language pBC+ to express utility, belief states, and observation as in POMDP models. Inheriting the advantages of action languages, the new action language provides an elaboration tolerant representation of POMDP that reflects commonsense knowledge. The idea led to the design of the system pbcplus2pomdp, which compiles a pBC+ action description into a POMDP model that can be directly processed by off-the-shelf POMDP solvers to compute an optimal policy of the pBC+ action description. Our experiments show that it retains the advantages of icorpp while avoiding the manual efforts in bridging the commonsense reasoner and the probabilistic planner.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13482](http://arxiv.org/abs/1907.13482)

##### PDF
[http://arxiv.org/pdf/1907.13482](http://arxiv.org/pdf/1907.13482)

