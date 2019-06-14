---
layout: post
title: "Privacy-Preserving Deep Visual Recognition: An Adversarial Learning Framework and A New Dataset"
date: 2019-06-12 02:23:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization Deep_Learning Relation Recognition
author: Haotao Wang, Zhenyu Wu, Zhangyang Wang, Zhaowen Wang, Hailin Jin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims to boost privacy-preserving visual recognition, an increasingly demanded feature in smart camera applications, using deep learning. We formulate a unique adversarial training framework, that learns a degradation transform for the original video inputs, in order to explicitly optimize the trade-off between target task performance and the associated privacy budgets on the degraded video. We carefully analyze and benchmark three different optimization strategies to train the resulting model. Notably, the privacy budget, often defined and measured in task-driven contexts, cannot be reliably indicated using any single model performance, because a strong protection of privacy has to sustain against any possible model that tries to hack privacy information. In order to tackle this problem, we propose two strategies: model restarting and model ensemble, which can be easily plug-and-play into our training algorithms and further improve the performance. Extensive experiments have been carried out and analyzed. On the other hand, few public datasets are available with both utility and privacy labels provided, making the power of data-driven (supervised) learning not yet fully unleashed on this task. We first discuss an innovative heuristic of cross-dataset training and evaluation, that jointly utilizes two datasets with target task and privacy labels respectively, for adversarial training. To further alleviate this challenge, we have constructed a new dataset, termed PA-HMDB51, with both target task (action) and selected privacy attributes (gender, age, race, nudity, and relationship) labeled on a frame-wise basis. This first-of-its-kind video dataset further validates the effectiveness of our proposed framework, and opens up new opportunities for the research community.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05675](https://arxiv.org/abs/1906.05675)

##### PDF
[https://arxiv.org/pdf/1906.05675](https://arxiv.org/pdf/1906.05675)

