---
layout: post
title: "Model Aggregation via Good-Enough Model Spaces"
date: 2019-06-04 18:34:56
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Neel Guha, Virginia Smith
mathjax: true
---

* content
{:toc}

##### Abstract
In many applications, the training data for a machine learning task is partitioned across multiple nodes, and aggregating this data may be infeasible due to communication, privacy, or storage constraints. Existing distributed optimization methods for learning global models in these settings typically aggregate local updates from each node in an iterative fashion. However, these approaches require many rounds of communication between nodes, and assume that updates can be synchronously shared across a connected network. In this work, we present Good-Enough Model Spaces (GEMS), a novel framework for learning a global model by carefully intersecting the sets of "good-enough" models across each node. Our approach utilizes minimal communication and does not require sharing of data between nodes. We present methods for learning both convex models and neural networks within this framework and discuss how small samples of held-out data can be used for post-learning fine-tuning. In experiments on image and medical datasets, our approach on average improves upon other baseline aggregation techniques such as ensembling or model averaging by as much as 15 points (accuracy).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.07782](http://arxiv.org/abs/1805.07782)

##### PDF
[http://arxiv.org/pdf/1805.07782](http://arxiv.org/pdf/1805.07782)

