---
layout: post
title: "Continual Learning of New Sound Classes using Generative Replay"
date: 2019-06-03 09:20:18
categories: arXiv_SD
tags: arXiv_SD Classification
author: Zhepei Wang, Cem Subakan, Efthymios Tzinis, Paris Smaragdis, Laurent Charlin
mathjax: true
---

* content
{:toc}

##### Abstract
Continual learning consists in incrementally training a model on a sequence of datasets and testing on the union of all datasets. In this paper, we examine continual learning for the problem of sound classification, in which we wish to refine already trained models to learn new sound classes. In practice one does not want to maintain all past training data and retrain from scratch, but naively updating a model with new data(sets) results in a degradation of already learned tasks, which is referred to as "catastrophic forgetting." We develop a generative replay procedure for generating training audio spectrogram data, in place of keeping older training datasets. We show that by incrementally refining a classifier with generative replay a generator that is 4% of the size of all previous training data matches the performance of refining the classifier keeping 20% of all previous training data. We thus conclude that we can extend a trained sound classifier to learn new classes without having to keep previously used datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00654](http://arxiv.org/abs/1906.00654)

##### PDF
[http://arxiv.org/pdf/1906.00654](http://arxiv.org/pdf/1906.00654)

