---
layout: post
title: "Learning a Multitask Curriculum for Neural Machine Translation"
date: 2019-08-28 20:48:05
categories: arXiv_CL
tags: arXiv_CL Optimization NMT
author: Wei Wang, Ye Tian, Jiquan Ngiam, Yinfei Yang, Isaac Caswell, Zarana Parekh
mathjax: true
---

* content
{:toc}

##### Abstract
Existing curriculum learning research in neural machine translation (NMT) mostly focuses on a single final task such as selecting data for a domain or for denoising, and considers in-task example selection. This paper studies the data selection problem in multitask setting. We present a method to learn a multitask curriculum on a single, diverse, potentially noisy training dataset. It computes multiple data selection scores for each training example, each score measuring how useful the example is to a certain task. It uses Bayesian optimization to learn a linear weighting of these per-instance scores, and then sorts the data to form a curriculum. We experiment with three domain translation tasks: two specific domains and the general domain, and demonstrate that the learned multitask curriculum delivers results close to individually optimized models and brings solid gains over no curriculum training, across all test sets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10940](http://arxiv.org/abs/1908.10940)

##### PDF
[http://arxiv.org/pdf/1908.10940](http://arxiv.org/pdf/1908.10940)

