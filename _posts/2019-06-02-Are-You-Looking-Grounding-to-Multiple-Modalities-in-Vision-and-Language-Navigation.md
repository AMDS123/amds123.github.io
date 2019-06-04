---
layout: post
title: "Are You Looking? Grounding to Multiple Modalities in Vision-and-Language Navigation"
date: 2019-06-02 05:16:06
categories: arXiv_CL
tags: arXiv_CL Object_Detection Prediction Detection
author: Ronghang Hu, Daniel Fried, Anna Rohrbach, Dan Klein, trevor darrell, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
Vision-and-Language Navigation (VLN) requires grounding instructions, such as "turn right and stop at the door", to routes in a visual environment. The actual grounding can connect language to the environment through multiple modalities, e.g. "stop at the door" might ground into visual objects, while "turn right" might rely only on the geometric structure of a route. We investigate where the natural language empirically grounds under two recent state-of-the-art VLN models. Surprisingly, we discover that visual features may actually hurt these models: models which only use route structure, ablating visual features, outperform their visual counterparts in unseen new environments on the benchmark Room-to-Room dataset. To better use all the available modalities, we propose to decompose the grounding procedure into a set of expert models with access to different modalities (including object detections) and ensemble them at prediction time, improving the performance of state-of-the-art models on the VLN task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00347](http://arxiv.org/abs/1906.00347)

##### PDF
[http://arxiv.org/pdf/1906.00347](http://arxiv.org/pdf/1906.00347)

