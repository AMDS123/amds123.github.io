---
layout: post
title: "Efficient Multitask Feature and Relationship Learning"
date: 2019-07-10 06:00:02
categories: arXiv_AI
tags: arXiv_AI Optimization Relation
author: Han Zhao, Otilia Stretcu, Alex Smola, Geoff Gordon
mathjax: true
---

* content
{:toc}

##### Abstract
We consider a multitask learning problem, in which several predictors are learned jointly. Prior research has shown that learning the relations between tasks, and between the input features, together with the predictor, can lead to better generalization and interpretability, which proved to be useful for applications in many domains. In this paper, we consider a formulation of multitask learning that learns the relationships both between tasks and between features, represented through a task covariance and a feature covariance matrix, respectively. First, we demonstrate that existing methods proposed for this problem present an issue that may lead to ill-posed optimization. We then propose an alternative formulation, as well as an efficient algorithm to optimize it. Using ideas from optimization and graph theory, we propose an efficient coordinate-wise minimization algorithm that has a closed form solution for each block subproblem. Our experiments show that the proposed optimization method is orders of magnitude faster than its competitors. We also provide a nonlinear extension that is able to achieve better generalization than existing methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1702.04423](http://arxiv.org/abs/1702.04423)

##### PDF
[http://arxiv.org/pdf/1702.04423](http://arxiv.org/pdf/1702.04423)

