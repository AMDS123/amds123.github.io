---
layout: post
title: "Neural Packet Classification"
date: 2019-02-27 03:24:40
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Classification
author: Eric Liang, Hang Zhu, Xin Jin, Ion Stoica
mathjax: true
---

* content
{:toc}

##### Abstract
Packet classification is a fundamental problem in computer networking. This problem exposes a hard tradeoff between the computation and state complexity, which makes it particularly challenging. To navigate this tradeoff, existing solutions rely on complex hand-tuned heuristics, which are brittle and hard to optimize. In this paper, we propose a deep reinforcement learning (RL) approach to solve the packet classification problem. There are several characteristics that make this problem a good fit for Deep RL. First, many of the existing solutions are iteratively building a decision tree by splitting nodes in the tree. Second, the effects of these actions (e.g., splitting nodes) can only be evaluated once we are done with building the tree. These two characteristics are naturally captured by the ability of RL to take actions that have sparse and delayed rewards. Third, it is computationally efficient to generate data traces and evaluate decision trees, which alleviate the notoriously high sample complexity problem of Deep RL algorithms. Our solution, NeuroCuts, uses succinct representations to encode state and action space, and efficiently explore candidate decision trees to optimize for a global objective. It produces compact decision trees optimized for a specific set of rules and a given performance metric, such as classification time, memory footprint, or a combination of the two. Evaluation on ClassBench shows that NeuroCuts outperforms existing hand-crafted algorithms in classification time by 18% at the median, and reduces both time and memory footprint by up to 3x.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10319](http://arxiv.org/abs/1902.10319)

##### PDF
[http://arxiv.org/pdf/1902.10319](http://arxiv.org/pdf/1902.10319)

