---
layout: post
title: "Model-Predictive Policy Learning with Uncertainty Regularization for Driving in Dense Traffic"
date: 2019-01-08 00:39:21
categories: arXiv_AI
tags: arXiv_AI Regularization Prediction
author: Mikael Henaff, Alfredo Canziani, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a policy using only observational data is challenging because the distribution of states it induces at execution time may differ from the distribution observed during training. We propose to train a policy by unrolling a learned model of the environment dynamics over multiple time steps while explicitly penalizing two costs: the original cost the policy seeks to optimize, and an uncertainty cost which represents its divergence from the states it is trained on. We measure this second cost by using the uncertainty of the dynamics model about its own predictions, using recent ideas from uncertainty estimation for deep networks. We evaluate our approach using a large-scale observational dataset of driving behavior recorded from traffic cameras, and show that we are able to learn effective driving policies from purely observational data, with no environment interaction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02705](http://arxiv.org/abs/1901.02705)

##### PDF
[http://arxiv.org/pdf/1901.02705](http://arxiv.org/pdf/1901.02705)

