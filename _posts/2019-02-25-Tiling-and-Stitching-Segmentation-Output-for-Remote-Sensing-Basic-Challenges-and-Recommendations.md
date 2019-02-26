---
layout: post
title: "Tiling and Stitching Segmentation Output for Remote Sensing: Basic Challenges and Recommendations"
date: 2019-02-25 14:44:09
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Recommendation
author: Bohao Huang, Daniel Reichman, Leslie M. Collins, Kyle Bradbury, Jordan M. Malof
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we consider the application of convolutional neural networks (CNNs) for pixel-wise labeling (a.k.a., semantic segmentation) of remote sensing imagery (e.g., aerial color or hyperspectral imagery). Remote sensing imagery is usually stored in the form of very large images, referred to as "tiles", which are too large to be segmented directly using most CNNs and their associated hardware. As a result, during label inference, smaller sub-images, called "patches", are processed individually and then "stitched" (concatenated) back together to create a tile-sized label map. This approach suffers from computational ineffiency and can result in discontinuities at output boundaries. We propose a simple alternative approach in which the input size of the CNN is dramatically increased only during label inference. This does not avoid stitching altogether, but substantially mitigates its limitations. We evaluate the performance of the proposed approach against a vonventional stitching approach using two popular segmentation CNN models and two large-scale remote sensing imagery datasets. The results suggest that the proposed approach substantially reduces label inference time, while also yielding modest overall label accuracy increases. This approach contributed to our wining entry (overall performance) in the INRIA building labeling competition.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.12219](http://arxiv.org/abs/1805.12219)

##### PDF
[http://arxiv.org/pdf/1805.12219](http://arxiv.org/pdf/1805.12219)

