---
layout: post
title: "New CleverHans Feature: Better Adversarial Robustness Evaluations with Attack Bundling"
date: 2018-11-08 21:30:57
categories: arXiv_AI
tags: arXiv_AI Adversarial Classification
author: Ian Goodfellow
mathjax: true
---

* content
{:toc}

##### Abstract
This technical report describes a new feature of the CleverHans library called "attack bundling". Many papers about adversarial examples present lists of error rates corresponding to different attack algorithms. A common approach is to take the maximum across this list and compare defenses against that error rate. We argue that a better approach is to use attack bundling: the max should be taken across many examples at the level of individual examples, then the error rate should be calculated by averaging after this maximization operation. Reporting the bundled attacker error rate provides a lower bound on the true worst-case error rate. The traditional approach of reporting the maximum error rate across attacks can underestimate the true worst-case error rate by an amount approaching 100\% as the number of attacks approaches infinity. Attack bundling can be used with different prioritization schemes to optimize quantities such as error rate on adversarial examples, perturbation size needed to cause misclassification, or failure rate when using a specific confidence threshold.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03685](http://arxiv.org/abs/1811.03685)

##### PDF
[http://arxiv.org/pdf/1811.03685](http://arxiv.org/pdf/1811.03685)

