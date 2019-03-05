---
layout: post
title: "Using Causal Analysis to Learn Specifications from Task Demonstrations"
date: 2019-03-04 14:26:13
categories: arXiv_AI
tags: arXiv_AI Relation
author: Daniel Angelov, Yordan Hristov, Subramanian Ramamoorthy
mathjax: true
---

* content
{:toc}

##### Abstract
Learning models of user behaviour is an important problem that is broadly applicable across many application domains requiring human-robot interaction. In this work we show that it is possible to learn a generative model for distinct user behavioral types, extracted from human demonstrations, by enforcing clustering of preferred task solutions within the latent space. We use this model to differentiate between user types and to find cases with overlapping solutions. Moreover, we can alter an initially guessed solution to satisfy the preferences that constitute a particular user type by backpropagating through the learned differentiable model. An advantage of structuring generative models in this way is that it allows us to extract causal relationships between symbols that might form part of the user's specification of the task, as manifested in the demonstrations. We show that the proposed method is capable of correctly distinguishing between three user types, who differ in degrees of cautiousness in their motion, while performing the task of moving objects with a kinesthetically driven robot in a tabletop environment. Our method successfully identifies the correct type, within the specified time, in 99% [97.8 - 99.8] of the cases, which outperforms an IRL baseline. We also show that our proposed method correctly changes a default trajectory to one satisfying a particular user specification even with unseen objects. The resulting trajectory is shown to be directly implementable on a PR2 humanoid robot completing the same task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01267](http://arxiv.org/abs/1903.01267)

##### PDF
[http://arxiv.org/pdf/1903.01267](http://arxiv.org/pdf/1903.01267)

