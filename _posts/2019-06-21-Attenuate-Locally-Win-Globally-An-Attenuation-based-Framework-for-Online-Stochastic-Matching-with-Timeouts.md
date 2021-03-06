---
layout: post
title: "Attenuate Locally, Win Globally: An Attenuation-based Framework for Online Stochastic Matching with Timeouts"
date: 2019-06-21 16:16:21
categories: arXiv_AI
tags: arXiv_AI Attention
author: Brian Brubach, Karthik Abinav Sankararaman, Aravind Srinivasan, Pan Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Online matching problems have garnered significant attention in recent years due to numerous applications in e-commerce, online advertisements, ride-sharing, etc. Many of them capture the uncertainty in the real world by including stochasticity in both the arrival process and the matching process. The Online Stochastic Matching with Timeouts problem introduced by Bansal, et al., (Algorithmica, 2012) models matching markets (e.g., E-Bay, Amazon). Buyers arrive from an independent and identically distributed (i.i.d.) known distribution on buyer profiles and can be shown a list of items one at a time. Each buyer has some probability of purchasing each item and a limit (timeout) on the number of items they can be shown. 
 Bansal et al., (Algorithmica, 2012) gave a 0.12-competitive algorithm which was improved by Adamczyk, et al., (ESA, 2015) to 0.24. We present an online attenuation framework that uses an algorithm for offline stochastic matching as a black box. On the upper bound side, we show that this framework, combined with a black-box adapted from Bansal et al., (Algorithmica, 2012), yields an online algorithm which nearly doubles the ratio to 0.46. On the lower bound side, we show that no algorithm can achieve a ratio better than 0.632 using the standard LP for this problem. This framework has a high potential for further improvements since new algorithms for offline stochastic matching can directly improve the ratio for the online problem. 
 Our online framework also has the potential for a variety of extensions. For example, we introduce a natural generalization: Online Stochastic Matching with Two-sided Timeouts in which both online and offline vertices have timeouts. Our framework provides the first algorithm for this problem achieving a ratio of 0.30. We once again use the algorithm of Adamczyk et al., (ESA, 2015) as a black-box and plug-it into our framework.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.08062](http://arxiv.org/abs/1804.08062)

##### PDF
[http://arxiv.org/pdf/1804.08062](http://arxiv.org/pdf/1804.08062)

