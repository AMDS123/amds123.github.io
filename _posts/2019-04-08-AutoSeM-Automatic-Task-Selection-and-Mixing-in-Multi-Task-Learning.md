---
layout: post
title: "AutoSeM: Automatic Task Selection and Mixing in Multi-Task Learning"
date: 2019-04-08 16:05:43
categories: arXiv_CL
tags: arXiv_CL Optimization
author: Han Guo, Ramakanth Pasunuru, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-task learning (MTL) has achieved success over a wide range of problems, where the goal is to improve the performance of a primary task using a set of relevant auxiliary tasks. However, when the usefulness of the auxiliary tasks w.r.t. the primary task is not known a priori, the success of MTL models depends on the correct choice of these auxiliary tasks and also a balanced mixing ratio of these tasks during alternate training. These two problems could be resolved via manual intuition or hyper-parameter tuning over all combinatorial task choices, but this introduces inductive bias or is not scalable when the number of candidate auxiliary tasks is very large. To address these issues, we present AutoSeM, a two-stage MTL pipeline, where the first stage automatically selects the most useful auxiliary tasks via a Beta-Bernoulli multi-armed bandit with Thompson Sampling, and the second stage learns the training mixing ratio of these selected auxiliary tasks via a Gaussian Process based Bayesian optimization framework. We conduct several MTL experiments on the GLUE language understanding tasks, and show that our AutoSeM framework can successfully find relevant auxiliary tasks and automatically learn their mixing ratio, achieving significant performance boosts on several primary tasks. Finally, we present ablations for each stage of AutoSeM and analyze the learned auxiliary task choices.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04153](http://arxiv.org/abs/1904.04153)

##### PDF
[http://arxiv.org/pdf/1904.04153](http://arxiv.org/pdf/1904.04153)

