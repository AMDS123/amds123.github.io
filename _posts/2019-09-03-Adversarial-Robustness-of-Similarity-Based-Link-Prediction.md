---
layout: post
title: "Adversarial Robustness of Similarity-Based Link Prediction"
date: 2019-09-03 20:20:45
categories: arXiv_AI
tags: arXiv_AI Adversarial Prediction
author: Kai Zhou, Tomasz P. Michalak, Yevgeniy Vorobeychik
mathjax: true
---

* content
{:toc}

##### Abstract
Link prediction is one of the fundamental problems in social network analysis. A common set of techniques for link prediction rely on similarity metrics which use the topology of the observed subnetwork to quantify the likelihood of unobserved links. Recently, similarity metrics for link prediction have been shown to be vulnerable to attacks whereby observations about the network are adversarially modified to hide target links. We propose a novel approach for increasing robustness of similarity-based link prediction by endowing the analyst with a restricted set of reliable queries which accurately measure the existence of queried links. The analyst aims to robustly predict a collection of possible links by optimally allocating the reliable queries. We formalize the analyst problem as a Bayesian Stackelberg game in which they first choose the reliable queries, followed by an adversary who deletes a subset of links among the remaining (unreliable) queries by the analyst. The analyst in our model is uncertain about the particular target link the adversary attempts to hide, whereas the adversary has full information about the analyst and the network. Focusing on similarity metrics using only local information, we show that the problem is NP-Hard for both players, and devise two principled and efficient approaches for solving it approximately. Extensive experiments with real and synthetic networks demonstrate the effectiveness of our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01432](http://arxiv.org/abs/1909.01432)

##### PDF
[http://arxiv.org/pdf/1909.01432](http://arxiv.org/pdf/1909.01432)

