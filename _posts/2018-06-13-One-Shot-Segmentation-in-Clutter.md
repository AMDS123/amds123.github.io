---
layout: post
title: "One-Shot Segmentation in Clutter"
date: 2018-06-13 12:01:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Embedding Detection Recognition
author: Claudio Michaelis, Matthias Bethge, Alexander S. Ecker
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the problem of one-shot segmentation: finding and segmenting a previously unseen object in a cluttered scene based on a single instruction example. We propose a novel dataset, which we call $\textit{cluttered Omniglot}$. Using a baseline architecture combining a Siamese embedding for detection with a U-net for segmentation we show that increasing levels of clutter make the task progressively harder. Using oracle models with access to various amounts of ground-truth information, we evaluate different aspects of the problem and show that in this kind of visual search task, detection and segmentation are two intertwined problems, the solution to each of which helps solving the other. We therefore introduce $\textit{MaskNet}$, an improved model that attends to multiple candidate locations, generates segmentation proposals to mask out background clutter and selects among the segmented objects. Our findings suggest that such image recognition models based on an iterative refinement of object detection and foreground segmentation may provide a way to deal with highly cluttered scenes.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.09597](https://arxiv.org/abs/1803.09597)

##### PDF
[https://arxiv.org/pdf/1803.09597](https://arxiv.org/pdf/1803.09597)

