---
layout: post
title: "Learning Abstract Options"
date: 2018-10-27 02:54:59
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Matthew Riemer, Miao Liu, Gerald Tesauro
mathjax: true
---

* content
{:toc}

##### Abstract
Building systems that autonomously create temporal abstractions from data is a key challenge in scaling learning and planning in reinforcement learning. One popular approach for addressing this challenge is the options framework (Sutton et al., 1999). However, only recently in (Bacon et al., 2017) was a policy gradient theorem derived for online learning of general purpose options in an end to end fashion. In this work, we extend previous work on this topic that only focuses on learning a two-level hierarchy including options and primitive actions to enable learning simultaneously at multiple resolutions in time. We achieve this by considering an arbitrarily deep hierarchy of options where high level temporally extended options are composed of lower level options with finer resolutions in time. We extend results from (Bacon et al., 2017) and derive policy gradient theorems for a deep hierarchy of options. Our proposed hierarchical option-critic architecture is capable of learning internal policies, termination conditions, and hierarchical compositions over options without the need for any intrinsic rewards or subgoals. Our empirical results in both discrete and continuous environments demonstrate the efficiency of our framework.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11583](http://arxiv.org/abs/1810.11583)

##### PDF
[http://arxiv.org/pdf/1810.11583](http://arxiv.org/pdf/1810.11583)

