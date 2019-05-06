---
layout: post
title: "GradNorm: Gradient Normalization for Adaptive Loss Balancing in Deep Multitask Networks"
date: 2018-06-12 06:45:49
categories: arXiv_CV
tags: arXiv_CV Classification
author: Zhao Chen, Vijay Badrinarayanan, Chen-Yu Lee, Andrew Rabinovich
mathjax: true
---

* content
{:toc}

##### Abstract
Deep multitask networks, in which one neural network produces multiple predictive outputs, can offer better speed and performance than their single-task counterparts but are challenging to train properly. We present a gradient normalization (GradNorm) algorithm that automatically balances training in deep multitask models by dynamically tuning gradient magnitudes. We show that for various network architectures, for both regression and classification tasks, and on both synthetic and real datasets, GradNorm improves accuracy and reduces overfitting across multiple tasks when compared to single-task networks, static baselines, and other adaptive multitask loss balancing techniques. GradNorm also matches or surpasses the performance of exhaustive grid search methods, despite only involving a single asymmetry hyperparameter $\alpha$. Thus, what was once a tedious search process that incurred exponentially more compute for each task added can now be accomplished within a few training runs, irrespective of the number of tasks. Ultimately, we will demonstrate that gradient manipulation affords us great control over the training dynamics of multitask networks and may be one of the keys to unlocking the potential of multitask learning.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.02257](https://arxiv.org/abs/1711.02257)

##### PDF
[https://arxiv.org/pdf/1711.02257](https://arxiv.org/pdf/1711.02257)

