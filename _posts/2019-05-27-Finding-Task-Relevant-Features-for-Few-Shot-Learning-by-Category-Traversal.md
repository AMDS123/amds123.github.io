---
layout: post
title: "Finding Task-Relevant Features for Few-Shot Learning by Category Traversal"
date: 2019-05-27 10:55:51
categories: arXiv_AI
tags: arXiv_AI
author: Hongyang Li, David Eigen, Samuel Dodge, Matthew Zeiler, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Few-shot learning is an important area of research. Conceptually, humans are readily able to understand new concepts given just a few examples, while in more pragmatic terms, limited-example training situations are common in practice. Recent effective approaches to few-shot learning employ a metric-learning framework to learn a feature similarity comparison between a query (test) example, and the few support (training) examples. However, these approaches treat each support class independently from one another, never looking at the entire task as a whole. Because of this, they are constrained to use a single set of features for all possible test-time tasks, which hinders the ability to distinguish the most relevant dimensions for the task at hand. In this work, we introduce a Category Traversal Module that can be inserted as a plug-and-play module into most metric-learning based few-shot learners. This component traverses across the entire support set at once, identifying task-relevant features based on both intra-class commonality and inter-class uniqueness in the feature space. Incorporating our module improves performance considerably (5%-10% relative) over baseline systems on both mini-ImageNet and tieredImageNet benchmarks, with overall performance competitive with recent state-of-the-art systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.11116](http://arxiv.org/abs/1905.11116)

##### PDF
[http://arxiv.org/pdf/1905.11116](http://arxiv.org/pdf/1905.11116)

