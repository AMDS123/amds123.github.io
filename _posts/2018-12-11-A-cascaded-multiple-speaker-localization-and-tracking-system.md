---
layout: post
title: "A cascaded multiple-speaker localization and tracking system"
date: 2018-12-11 14:12:10
categories: arXiv_SD
tags: arXiv_SD Tracking Optimization
author: Xiaofei Li, Yutong Ban, Laurent Girin, Xavier Alameda-Pineda, Radu Horaud
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an online multiple-speaker localization and tracking method, as the INRIA-Perception contribution to the LOCATA Challenge 2018. First, the recursive least-square method is used to adaptively estimate the direct-path relative transfer function as an interchannel localization feature. The feature is assumed to associate with a single speaker at each time-frequency bin. Second, a complex Gaussian mixture model (CGMM) is used as a generative model of the features. The weight of each CGMM component represents the probability that this component corresponds to an active speaker, and is adaptively estimated with an online optimization algorithm. Finally, taking the CGMM component weights as observations, a Bayesian multiple-speaker tracking method based on the variational expectation maximization algorithm is used. The tracker accounts for the variation of active speakers and the localization miss measurements, by introducing speaker birth and sleeping processes. The experiments carried out on the development dataset of the challenge are reported.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04417](http://arxiv.org/abs/1812.04417)

##### PDF
[http://arxiv.org/pdf/1812.04417](http://arxiv.org/pdf/1812.04417)

