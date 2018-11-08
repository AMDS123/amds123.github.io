---
layout: post
title: "Learning-based Model Predictive Control for Safe Exploration"
date: 2018-11-07 11:08:25
categories: arXiv_AI
tags: arXiv_AI Knowledge Prediction
author: Torsten Koller, Felix Berkenkamp, Matteo Turchetta, Andreas Krause
mathjax: true
---

* content
{:toc}

##### Abstract
Learning-based methods have been successful in solving complex control tasks without significant prior knowledge about the system. However, these methods typically do not provide any safety guarantees, which prevents their use in safety-critical, real-world applications. In this paper, we present a learning-based model predictive control scheme that can provide provable high-probability safety guarantees. To this end, we exploit regularity assumptions on the dynamics in terms of a Gaussian process prior to construct provably accurate confidence intervals on predicted trajectories. Unlike previous approaches, we do not assume that model uncertainties are independent. Based on these predictions, we guarantee that trajectories satisfy safety constraints. Moreover, we use a terminal set constraint to recursively guarantee the existence of safe control actions at every iteration. In our experiments, we show that the resulting algorithm can be used to safely and efficiently explore and learn about dynamic systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.08287](http://arxiv.org/abs/1803.08287)

##### PDF
[http://arxiv.org/pdf/1803.08287](http://arxiv.org/pdf/1803.08287)

