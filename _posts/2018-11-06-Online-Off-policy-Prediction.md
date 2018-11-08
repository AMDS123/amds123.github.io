---
layout: post
title: "Online Off-policy Prediction"
date: 2018-11-06 19:09:04
categories: arXiv_AI
tags: arXiv_AI Knowledge Prediction Gradient_Descent
author: Sina Ghiassian, Andrew Patterson, Martha White, Richard S. Sutton, Adam White
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates the problem of online prediction learning, where learning proceeds continuously as the agent interacts with an environment. The predictions made by the agent are contingent on a particular way of behaving, represented as a value function. However, the behavior used to select actions and generate the behavior data might be different from the one used to define the predictions, and thus the samples are generated off-policy. The ability to learn behavior-contingent predictions online and off-policy has long been advocated as a key capability of predictive-knowledge learning systems but remained an open algorithmic challenge for decades. The issue lies with the temporal difference (TD) learning update at the heart of most prediction algorithms: combining bootstrapping, off-policy sampling and function approximation may cause the value estimate to diverge. A breakthrough came with the development of a new objective function that admitted stochastic gradient descent variants of TD. Since then, many sound online off-policy prediction algorithms have been developed, but there has been limited empirical work investigating the relative merits of all the variants. This paper aims to fill these empirical gaps and provide clarity on the key ideas behind each method. We summarize the large body of literature on off-policy learning, focusing on 1- methods that use computation linear in the number of features and are convergent under off-policy sampling, and 2- other methods which have proven useful with non-fixed, nonlinear function approximation. We provide an empirical study of off-policy prediction methods in two challenging microworlds. We report each method's parameter sensitivity, empirical convergence rate, and final performance, providing new insights that should enable practitioners to successfully extend these new methods to large-scale applications.[Abridged abstract]

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02597](http://arxiv.org/abs/1811.02597)

##### PDF
[http://arxiv.org/pdf/1811.02597](http://arxiv.org/pdf/1811.02597)

