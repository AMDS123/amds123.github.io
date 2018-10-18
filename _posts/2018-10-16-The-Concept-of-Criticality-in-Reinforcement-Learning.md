---
layout: post
title: "The Concept of Criticality in Reinforcement Learning"
date: 2018-10-16 20:07:06
categories: arXiv_AI
tags: arXiv_AI Attention Reinforcement_Learning
author: Yitzhak Spielberg, Amos Azaria
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning methods carry a well known bias-variance trade-off in n-step algorithms for optimal control. Unfortunately, this has rarely been addressed in current research. This trade-off principle holds independent of the choice of the algorithm, such as n-step SARSA, n-step Expected SARSA or n-step Tree backup. A small n results in a large bias, while a large n leads to large variance. The literature offers no straightforward recipe for the best choice of this value. While currently all n-step algorithms use a fixed value of n over the state space we extend the framework of n-step updates by allowing each state to have its specific n. 
 We propose a solution to this problem within the context of human aided reinforcement learning. Our approach is based on the observation that a human can learn more efficiently if she receives input regarding the criticality of a given state and thus the amount of attention she needs to invest into the learning in that state. This observation is related to the idea that each state of the MDP has a certain measure of criticality which indicates how much the choice of the action in that state influences the return. In our algorithm the RL agent utilizes the criticality measure, a function provided by a human trainer, in order to locally choose the best stepnumber n for the update of the Q function.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07254](http://arxiv.org/abs/1810.07254)

##### PDF
[http://arxiv.org/pdf/1810.07254](http://arxiv.org/pdf/1810.07254)

