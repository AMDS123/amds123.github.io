---
layout: post
title: "Knowing The What But Not The Where in Bayesian Optimization"
date: 2019-05-07 16:42:01
categories: arXiv_AI
tags: arXiv_AI Knowledge Segmentation Reinforcement_Learning Optimization Quantitative
author: Vu Nguyen, Michael A. Osborne
mathjax: true
---

* content
{:toc}

##### Abstract
Bayesian optimization has demonstrated impressive success in finding the optimum location $x^{*}$ and value $f^{*}=f(x^{*})=\max_{x\in\mathcal{X}}f(x)$ of the black-box function $f$. In some applications, however, the optimum value is known in advance and the goal is to find the corresponding optimum location. Existing work in Bayesian optimization (BO) has not effectively exploited the knowledge of $f^{*}$ for optimization. In this paper, we consider a new setting in BO in which the knowledge of the optimum value is available. Our goal is to exploit the knowledge about $f^{*}$ to search for the location $x^{*}$ efficiently. To achieve this goal, we first transform the Gaussian process surrogate using the information about the optimum value. Then, we propose two acquisition functions, called confidence bound minimization and expected regret minimization, which exploit the knowledge about the optimum value to identify the optimum location efficiently. We show that our approaches work both intuitively and quantitatively achieve better performance against standard BO methods. We demonstrate real applications in tuning a deep reinforcement learning algorithm on the CartPole problem and XGBoost on Skin Segmentation dataset in which the optimum values are publicly available.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.02685](https://arxiv.org/abs/1905.02685)

##### PDF
[https://arxiv.org/pdf/1905.02685](https://arxiv.org/pdf/1905.02685)

