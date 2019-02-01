---
layout: post
title: "Automatic Local Rewriting for Combinatorial Optimization"
date: 2019-01-31 15:09:06
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization RNN
author: Xinyun Chen, Yuandong Tian
mathjax: true
---

* content
{:toc}

##### Abstract
To solve combinatorial problems, traditional search-based optimization uses heuristics to guide the search. Deciding in which specific conditions and situations a certain heuristic can be applied is time-consuming and might cost decades to tune. In this paper, we learn a policy to pick heuristics and rewrite the local components of the current solution to iteratively improve it until convergence. The policy factorizes into a region-picking policy and a rule-picking policy, and it employs a neural network trained with reinforcement learning. We evaluate our approach in three domains: expression simplification, online job scheduling and SAT. Our approach outperforms Z3 (De Moura &amp; Bj{\o}rner, 2008), a state-of-the-art theorem prover, in expression simplification, outperforms DeepRM (Mao et al., 2016) and Google OR-tools (Google, 2019) in online job scheduling, and outperforms NeuroSAT (Selsam et al., 2019) and DG-DAGRNN (Amizadeh et al., 2019) in SAT with a small number of variables.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.00337](http://arxiv.org/abs/1810.00337)

##### PDF
[http://arxiv.org/pdf/1810.00337](http://arxiv.org/pdf/1810.00337)

