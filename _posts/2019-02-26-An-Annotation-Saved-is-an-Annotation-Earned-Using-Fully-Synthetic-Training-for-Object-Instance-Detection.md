---
layout: post
title: "An Annotation Saved is an Annotation Earned: Using Fully Synthetic Training for Object Instance Detection"
date: 2019-02-26 14:36:35
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Stefan Hinterstoisser, Olivier Pauly, Hauke Heibel, Martina Marek, Martin Bokeloh
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning methods typically require vast amounts of training data to reach their full potential. While some publicly available datasets exists, domain specific data always needs to be collected and manually labeled, an expensive, time consuming and error prone process. Training with synthetic data is therefore very lucrative, as dataset creation and labeling comes for free. We propose a novel method for creating purely synthetic training data for object detection. We leverage a large dataset of 3D background models and densely render them using full domain randomization. This yields background images with realistic shapes and texture on top of which we render the objects of interest. During training, the data generation process follows a curriculum strategy guaranteeing that all foreground models are presented to the network equally under all possible poses and conditions with increasing complexity. As a result, we entirely control the underlying statistics and we create optimal training samples at every stage of training. Using a set of 64 retail objects, we demonstrate that our simple approach enables the training of detectors that outperform models trained with real data on a challenging evaluation dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09967](http://arxiv.org/abs/1902.09967)

##### PDF
[http://arxiv.org/pdf/1902.09967](http://arxiv.org/pdf/1902.09967)

