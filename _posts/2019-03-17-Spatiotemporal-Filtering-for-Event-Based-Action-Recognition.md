---
layout: post
title: "Spatiotemporal Filtering for Event-Based Action Recognition"
date: 2019-03-17 12:13:14
categories: arXiv_CV
tags: arXiv_CV Sparse Action_Recognition CNN Recognition
author: Rohan Ghosh, Anupam Gupta, Andrei Nakagawa, Alcimar Soares, Nitish Thakor
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the challenging problem of action recognition, using event-based cameras. To recognise most gestural actions, often higher temporal precision is required for sampling visual information. Actions are defined by motion, and therefore, when using event-based cameras it is often unnecessary to re-sample the entire scene. Neuromorphic, event-based cameras have presented an alternative to visual information acquisition by asynchronously time-encoding pixel intensity changes, through temporally precise spikes (10 micro-second resolution), making them well equipped for action recognition. However, other challenges exist, which are intrinsic to event-based imagers, such as higher signal-to-noise ratio, and a spatiotemporally sparse information. One option is to convert event-data into frames, but this could result in significant temporal precision loss. In this work we introduce spatiotemporal filtering in the spike-event domain, as an alternative way of channeling spatiotemporal information through to a convolutional neural network. The filters are local spatiotemporal weight matrices, learned from the spike-event data, in an unsupervised manner. We find that appropriate spatiotemporal filtering significantly improves CNN performance beyond state-of-the-art on the event-based DVS Gesture dataset. On our newly recorded action recognition dataset, our method shows significant improvement when compared with other, standard ways of generating the spatiotemporal filters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07067](http://arxiv.org/abs/1903.07067)

##### PDF
[http://arxiv.org/pdf/1903.07067](http://arxiv.org/pdf/1903.07067)

