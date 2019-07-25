---
layout: post
title: "Classified Regression for Bayesian Optimization: Robot Learning with Unknown Penalties"
date: 2019-07-24 12:25:37
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Alonso Marco, Dominik Baumann, Philipp Hennig, Sebastian Trimpe
mathjax: true
---

* content
{:toc}

##### Abstract
Learning robot controllers by minimizing a black-box objective cost using Bayesian optimization (BO) can be time-consuming and challenging. It is very often the case that some roll-outs result in failure behaviors, causing premature experiment detention. In such cases, the designer is forced to decide on heuristic cost penalties because the acquired data is often scarce, or not comparable with that of the stable policies. To overcome this, we propose a Bayesian model that captures exactly what we know about the cost of unstable controllers prior to data collection: Nothing, except that it should be a somewhat large number. The resulting Bayesian model, approximated with a Gaussian process, predicts high cost values in regions where failures are likely to occur. In this way, the model guides the BO exploration toward regions of stability. We demonstrate the benefits of the proposed model in several illustrative and statistical synthetic benchmarks, and also in experiments on a real robotic platform. In addition, we propose and experimentally validate a new BO method to account for unknown constraints. Such method is an extension of Max-Value Entropy Search, a recent information-theoretic method, to solve unconstrained global optimization problems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10383](http://arxiv.org/abs/1907.10383)

##### PDF
[http://arxiv.org/pdf/1907.10383](http://arxiv.org/pdf/1907.10383)

