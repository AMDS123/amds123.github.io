---
layout: post
title: "Universal Decision-Based Black-Box Perturbations: Breaking Security-Through-Obscurity Defenses"
date: 2018-11-13 15:56:52
categories: arXiv_AI
tags: arXiv_AI Adversarial Optimization
author: Thomas A. Hogan, Bhavya Kailkhura
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of finding a universal (image-agnostic) perturbation to fool machine learning (ML) classifiers (e.g., neural nets, decision tress) in the hard-label black-box setting. Recent work in adversarial ML in the white-box setting (model parameters are known) has shown that many state-of-the-art image classifiers are vulnerable to universal adversarial perturbations: a fixed human-imperceptible perturbation that, when added to any image, causes it to be misclassified with high probability Kurakin et al. [2016], Szegedy et al. [2013], Chen et al. [2017a], Carlini and Wagner [2017]. This paper considers a more practical and challenging problem of finding such universal perturbations in an obscure (or black-box) setting. More specifically, we use zeroth order optimization algorithms to find such a universal adversarial perturbation when no model information is revealed-except that the attacker can make queries to probe the classifier. We further relax the assumption that the output of a query is continuous valued confidence scores for all the classes and consider the case where the output is a hard-label decision. Surprisingly, we found that even in these extremely obscure regimes, state-of-the-art ML classifiers can be fooled with a very high probability just by adding a single human-imperceptible image perturbation to any natural image. The surprising existence of universal perturbations in a hard-label black-box setting raises serious security concerns with the existence of a universal noise vector that adversaries can possibly exploit to break a classifier on most natural images.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.03733](https://arxiv.org/abs/1811.03733)

##### PDF
[https://arxiv.org/pdf/1811.03733](https://arxiv.org/pdf/1811.03733)

