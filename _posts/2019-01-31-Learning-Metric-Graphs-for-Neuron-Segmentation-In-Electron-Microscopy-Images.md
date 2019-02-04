---
layout: post
title: "Learning Metric Graphs for Neuron Segmentation In Electron Microscopy Images"
date: 2019-01-31 22:16:58
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Kyle Luther, H. Sebastian Seung
mathjax: true
---

* content
{:toc}

##### Abstract
In the deep metric learning approach to image segmentation, a convolutional net densely generates feature vectors at the pixels of an image. Pairs of feature vectors are trained to be similar or different, depending on whether the corresponding pixels belong to same or different ground truth segments. To segment a new image, the feature vectors are computed and clustered. Both empirically and theoretically, it is unclear whether or when deep metric learning is superior to the more conventional approach of directly predicting an affinity graph with a convolutional net. We compare the two approaches using brain images from serial section electron microscopy images, which constitute an especially challenging example of instance segmentation. We first show that seed-based postprocessing of the feature vectors, as originally proposed, produces inferior accuracy because it is difficult for the convolutional net to predict feature vectors that remain uniform across large objects. Then we consider postprocessing by thresholding a nearest neighbor graph followed by connected components. In this case, segmentations from a "metric graph" turn out to be competitive or even superior to segmentations from a directly predicted affinity graph. To explain these findings theoretically, we invoke the property that the metric function satisfies the triangle inequality. Then we show with an example where this constraint suppresses noise, causing connected components to more robustly segment a metric graph than an unconstrained affinity graph.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00100](http://arxiv.org/abs/1902.00100)

##### PDF
[http://arxiv.org/pdf/1902.00100](http://arxiv.org/pdf/1902.00100)

