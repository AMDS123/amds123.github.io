---
layout: post
title: "Network Transplanting"
date: 2018-12-18 05:18:29
categories: arXiv_CV
tags: arXiv_CV
author: Quanshi Zhang, Yu Yang, Qian Yu, Ying Nian Wu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on a new task, i.e., transplanting a category-and-task-specific neural network to a generic, modular network without strong supervision. We design an functionally interpretable structure for the generic network. Like building LEGO blocks, we teach the generic network a new category by directly transplanting the module corresponding to the category from a pre-trained network with a few or even without sample annotations. Our method incrementally adds new categories to the generic network but does not affect representations of existing categories. In this way, our method breaks the typical bottleneck of learning a net for massive tasks and categories, i.e. the requirement of collecting samples for all tasks and categories at the same time before the learning begins. Thus, we use a new distillation algorithm, namely back-distillation, to overcome specific challenges of network transplanting. Our method without training samples even outperformed the baseline with 100 training samples.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.10272](http://arxiv.org/abs/1804.10272)

##### PDF
[http://arxiv.org/pdf/1804.10272](http://arxiv.org/pdf/1804.10272)

