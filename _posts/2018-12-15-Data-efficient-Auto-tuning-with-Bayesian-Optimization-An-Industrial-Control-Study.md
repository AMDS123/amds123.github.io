---
layout: post
title: "Data-efficient Auto-tuning with Bayesian Optimization: An Industrial Control Study"
date: 2018-12-15 17:19:35
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Matthias Neumann-Brosig, Alonso Marco, Dieter Schwarzmann, Sebastian Trimpe
mathjax: true
---

* content
{:toc}

##### Abstract
Bayesian optimization is proposed for automatic learning of optimal controller parameters from experimental data. A probabilistic description (a Gaussian process) is used to model the unknown function from controller parameters to a user-defined cost. The probabilistic model is updated with data, which is obtained by testing a set of parameters on the physical system and evaluating the cost. In order to learn fast, the Bayesian optimization algorithm selects the next parameters to evaluate in a systematic way, for example, by maximizing information gain about the optimum. The algorithm thus iteratively finds the globally optimal parameters with only few experiments. Taking throttle valve control as a representative industrial control example, the proposed auto-tuning method is shown to outperform manual calibration: it consistently achieves better performance with a low number of experiments. The proposed auto-tuning framework is flexible and can handle different control structures and objectives.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06325](http://arxiv.org/abs/1812.06325)

##### PDF
[http://arxiv.org/pdf/1812.06325](http://arxiv.org/pdf/1812.06325)

