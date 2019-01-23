---
layout: post
title: "Estimating Buildings' Parameters over Time Including Prior Knowledge"
date: 2019-01-09 03:37:32
categories: arXiv_AI
tags: arXiv_AI Knowledge Transfer_Learning Inference
author: Nilavra Pathak, James Foulds, Nirmalya Roy. Nilanjan Banerjee, Ryan Robucci
mathjax: true
---

* content
{:toc}

##### Abstract
Modeling buildings' heat dynamics is a complex process which depends on various factors including weather, building thermal capacity, insulation preservation, and residents' behavior. Gray-box models offer a causal inference of those dynamics expressed in few parameters specific to built environments. These parameters can provide compelling insights into the characteristics of building artifacts and have various applications such as forecasting HVAC usage, indoor temperature control monitoring of built environments, etc. In this paper, we present a systematic study of modeling buildings' thermal characteristics and thus derive the parameters of built conditions with a Bayesian approach. We build a Bayesian state-space model that can adapt and incorporate buildings' thermal equations and propose a generalized solution that can easily adapt prior knowledge regarding the parameters. We show that a faster approximate approach using variational inference for parameter estimation can provide similar parameters as that of a more time-consuming Markov Chain Monte Carlo (MCMC) approach. We perform extensive evaluations on two datasets to understand the generative process and show that the Bayesian approach is more interpretable. We further study the effects of prior selection for the model parameters and transfer learning, where we learn parameters from one season and use them to fit the model in the other. We perform extensive evaluations on controlled and real data traces to enumerate buildings' parameter within a 95% credible interval.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07469](http://arxiv.org/abs/1901.07469)

##### PDF
[http://arxiv.org/pdf/1901.07469](http://arxiv.org/pdf/1901.07469)

