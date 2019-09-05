---
layout: post
title: "Distance transform regression for spatially-aware deep semantic segmentation"
date: 2019-09-04 10:05:08
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation CNN Semantic_Segmentation Classification Prediction
author: Nicolas Audebert (OBELIX), Alexandre Boulch, Bertrand Le Saux, S&#xe9;bastien Lef&#xe8;vre (OBELIX)
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding visual scenes relies more and more on dense pixel-wise classification obtained via deep fully convolutional neural networks. However, due to the nature of the networks, predictions often suffer from blurry boundaries and ill-segmented shapes, fueling the need for post-processing. This work introduces a new semantic segmentation regularization based on the regression of a distance transform. After computing the distance transform on the label masks, we train a FCN in a multi-task setting in both discrete and continuous spaces by learning jointly classification and distance regression. This requires almost no modification of the network structure and adds a very low overhead to the training process. Learning to approximate the distance transform back-propagates spatial cues that implicitly regularizes the segmentation. We validate this technique with several architectures on various datasets, and we show significant improvements compared to competitive baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01671](http://arxiv.org/abs/1909.01671)

##### PDF
[http://arxiv.org/pdf/1909.01671](http://arxiv.org/pdf/1909.01671)

