---
layout: post
title: "Actor-Expert: A Framework for using Q-learning in Continuous Action Spaces"
date: 2019-04-28 17:34:35
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Sungsu Lim, Ajin Joseph, Lei Le, Yangchen Pan, Martha White
mathjax: true
---

* content
{:toc}

##### Abstract
Q-learning can be difficult to use in continuous action spaces, because an optimization has to be solved to find the maximal action for the action-values. A common strategy has been to restrict the functional form of the action-values to be concave in the actions, to simplify the optimization. Such restrictions, however, can prevent learning accurate action-values. In this work, we propose a new policy search objective that facilitates using Q-learning and a framework to optimize this objective, called Actor-Expert. The Expert uses Q-learning to update the action-values towards optimal action-values. The Actor learns the maximal actions over time for these changing action-values. We develop a Cross Entropy Method (CEM) for the Actor, where such a global optimization approach facilitates use of generically parameterized action-values. This method - which we call Conditional CEM - iteratively concentrates density around maximal actions, conditioned on state. We prove that this algorithm tracks the expected CEM update, over states with changing action-values. We demonstrate in a toy environment that previous methods that restrict the action-value parameterization fail whereas Actor-Expert with a more general action-value parameterization succeeds. Finally, we demonstrate that Actor-Expert performs as well as or better than competitors on four benchmark continuous-action environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09103](http://arxiv.org/abs/1810.09103)

##### PDF
[http://arxiv.org/pdf/1810.09103](http://arxiv.org/pdf/1810.09103)

