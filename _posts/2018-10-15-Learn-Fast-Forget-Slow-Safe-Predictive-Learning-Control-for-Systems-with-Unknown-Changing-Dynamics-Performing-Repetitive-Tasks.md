---
layout: post
title: "Learn Fast, Forget Slow: Safe Predictive Learning Control for Systems with Unknown, Changing Dynamics Performing Repetitive Tasks"
date: 2018-10-15 20:49:06
categories: arXiv_RO
tags: arXiv_RO Optimization Prediction
author: Christopher D. McKinnon, Angela P. Schoellig
mathjax: true
---

* content
{:toc}

##### Abstract
We present a control method for improved repetitive path following for a ground vehicle that is geared towards long-term operation where the operating conditions can change over time and are initially unknown. We use weighted Bayesian Linear Regression to model the unknown actuator dynamics, and show how this simple model is more accurate in both its estimate of the mean behaviour and model uncertainty than Gaussian Process Regression and generalizes to novel operating conditions with little or no tuning. In addition, it allows us to use fast adaptation and long-term learning in one, unified framework, to adapt quickly to new operating conditions and learn repetitive model errors over time. This comes with the added benefit of lower computational cost, longer look-ahead, and easier optimization when the model is used in a robust, Model Predictive controller (MPC). In order to fully capitalize on the long prediction horizons that are possible with this new approach, we use Tube MPC to reduce predicted uncertainty growth. We demonstrate the effectiveness of our approach in experiment on a 900 kg ground robot showing results over 2.7 km of driving with both physical and artificial changes to the robot's dynamics. All of our experiments are conducted using a stereo camera for localization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.06681](http://arxiv.org/abs/1810.06681)

##### PDF
[http://arxiv.org/pdf/1810.06681](http://arxiv.org/pdf/1810.06681)

