---
layout: post
title: "A Hybrid RNN-HMM Approach for Weakly Supervised Temporal Action Segmentation"
date: 2019-06-03 19:12:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Action_Recognition Inference RNN Recognition
author: Hilde Kuehne, Alexander Richard, Juergen Gall
mathjax: true
---

* content
{:toc}

##### Abstract
Action recognition has become a rapidly developing research field within the last decade. But with the increasing demand for large scale data, the need of hand annotated data for the training becomes more and more impractical. One way to avoid frame-based human annotation is the use of action order information to learn the respective action classes. In this context, we propose a hierarchical approach to address the problem of weakly supervised learning of human actions from ordered action labels by structuring recognition in a coarse-to-fine manner. Given a set of videos and an ordered list of the occurring actions, the task is to infer start and end frames of the related action classes within the video and to train the respective action classifiers without any need for hand labeled frame boundaries. We address this problem by combining a framewise RNN model with a coarse probabilistic inference. This combination allows for the temporal alignment of long sequences and thus, for an iterative training of both elements. While this system alone already generates good results, we show that the performance can be further improved by approximating the number of subactions to the characteristics of the different action classes as well as by the introduction of a regularizing length prior. The proposed system is evaluated on two benchmark datasets, the Breakfast and the Hollywood extended dataset, showing a competitive performance on various weak learning tasks such as temporal action segmentation and action alignment.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01028](http://arxiv.org/abs/1906.01028)

##### PDF
[http://arxiv.org/pdf/1906.01028](http://arxiv.org/pdf/1906.01028)

