---
layout: post
title: "Learning Local Forward Models on Unforgiving Games"
date: 2019-09-01 18:25:14
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Alexander Dockhorn, Simon M. Lucas, Vanessa Volz, Ivan Bravi, Raluca D. Gaina, Diego Perez-Liebana
mathjax: true
---

* content
{:toc}

##### Abstract
This paper examines learning approaches for forward models based on local cell transition functions. We provide a formal definition of local forward models for which we propose two basic learning approaches. Our analysis is based on the game Sokoban, where a wrong action can lead to an unsolvable game state. Therefore, an accurate prediction of an action's resulting state is necessary to avoid this scenario. 
 In contrast to learning the complete state transition function, local forward models allow extracting multiple training examples from a single state transition. In this way, the Hash Set model, as well as the Decision Tree model, quickly learn to predict upcoming state transitions of both the training and the test set. Applying the model using a statistical forward planner showed that the best models can be used to satisfying degree even in cases in which the test levels have not yet been seen. 
 Our evaluation includes an analysis of various local neighbourhood patterns and sizes to test the learners' capabilities in case too few or too many attributes are extracted, of which the latter has shown do degrade the performance of the model learner.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00442](http://arxiv.org/abs/1909.00442)

##### PDF
[http://arxiv.org/pdf/1909.00442](http://arxiv.org/pdf/1909.00442)

