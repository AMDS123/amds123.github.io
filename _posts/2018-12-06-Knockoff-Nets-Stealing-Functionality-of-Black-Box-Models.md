---
layout: post
title: "Knockoff Nets: Stealing Functionality of Black-Box Models"
date: 2018-12-06 19:34:33
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning Prediction
author: Tribhuvanesh Orekondy, Bernt Schiele, Mario Fritz
mathjax: true
---

* content
{:toc}

##### Abstract
Machine Learning (ML) models are increasingly deployed in the wild to perform a wide range of tasks. In this work, we ask to what extent can an adversary steal functionality of such "victim" models based solely on blackbox interactions: image in, predictions out. In contrast to prior work, we present an adversary lacking knowledge of train/test data used by the model, its internals, and semantics over model outputs. We formulate model functionality stealing as a two-step approach: (i) querying a set of input images to the blackbox model to obtain predictions; and (ii) training a "knockoff" with queried image-prediction pairs. We make multiple remarkable observations: (a) querying random images from a different distribution than that of the blackbox training data results in a well-performing knockoff; (b) this is possible even when the knockoff is represented using a different architecture; and (c) our reinforcement learning approach additionally improves query sample efficiency in certain settings and provides performance gains. We validate model functionality stealing on a range of datasets and tasks, as well as on a popular image analysis API where we create a reasonable knockoff for as little as $30.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02766](http://arxiv.org/abs/1812.02766)

##### PDF
[http://arxiv.org/pdf/1812.02766](http://arxiv.org/pdf/1812.02766)

