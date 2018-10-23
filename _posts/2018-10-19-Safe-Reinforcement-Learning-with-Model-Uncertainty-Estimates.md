---
layout: post
title: "Safe Reinforcement Learning with Model Uncertainty Estimates"
date: 2018-10-19 22:04:59
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Prediction
author: Bj&#xf6;rn L&#xfc;tjens, Michael Everett, Jonathan P. How
mathjax: true
---

* content
{:toc}

##### Abstract
Many current autonomous systems are being designed with a strong reliance on black box predictions from deep neural networks (DNNs). However, DNNs tend to be overconfident in predictions on unseen data and can give unpredictable results for far-from-distribution test data. The importance of predictions that are robust to this distributional shift is evident for safety-critical applications, such as collision avoidance around pedestrians. Measures of model uncertainty can be used to identify unseen data, but the state-of-the-art extraction methods such as Bayesian neural networks are mostly intractable to compute. This paper uses MC-Dropout and Bootstrapping to give computationally tractable and parallelizable uncertainty estimates. The methods are embedded in a Safe Reinforcement Learning framework to form uncertainty-aware navigation around pedestrians. The result is a collision avoidance policy that \textit{knows what it does not know} and cautiously avoids pedestrians that exhibit unseen behavior. The policy is demonstrated in simulation to be more robust to novel observations and take safer actions than an uncertainty-unaware baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08700](http://arxiv.org/abs/1810.08700)

##### PDF
[http://arxiv.org/pdf/1810.08700](http://arxiv.org/pdf/1810.08700)

