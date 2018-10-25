---
layout: post
title: "Learning Representations in Model-Free Hierarchical Reinforcement Learning"
date: 2018-10-23 21:24:06
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Jacob Rafati, David C. Noelle
mathjax: true
---

* content
{:toc}

##### Abstract
Common approaches to Reinforcement Learning (RL) are seriously challenged by large-scale applications involving huge state spaces and sparse delayed reward feedback. Hierarchical Reinforcement Learning (HRL) methods attempt to address this scalability issue by learning action selection policies at multiple levels of temporal abstraction. Abstraction can be had by identifying a relatively small set of states that are likely to be useful as subgoals, in concert with the learning of corresponding skill policies to achieve those subgoals. Many approaches to subgoal discovery in HRL depend on the analysis of a model of the environment, but the need to learn such a model introduces its own problems of scale. Once subgoals are identified, skills may be learned through intrinsic motivation, introducing an internal reward signal marking subgoal attainment. In this paper, we present a novel model-free method for subgoal discovery using incremental unsupervised learning over a small memory of the most recent experiences of the agent. When combined with an intrinsic motivation learning mechanism, this method learns subgoals and skills together, based on experiences in the environment. Thus, we offer an original approach to HRL that does not require the acquisition of a model of the environment, suitable for large-scale applications. We demonstrate the efficiency of our method on two RL problems with sparse delayed feedback: a variant of the rooms environment and the ATARI 2600 game called Montezuma's Revenge.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.10096](http://arxiv.org/abs/1810.10096)

##### PDF
[http://arxiv.org/pdf/1810.10096](http://arxiv.org/pdf/1810.10096)

