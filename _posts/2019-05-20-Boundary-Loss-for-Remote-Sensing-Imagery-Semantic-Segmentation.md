---
layout: post
title: "Boundary Loss for Remote Sensing Imagery Semantic Segmentation"
date: 2019-05-20 03:02:44
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Detection
author: Alexey Bokhovkin, Evgeny Burnaev
mathjax: true
---

* content
{:toc}

##### Abstract
In response to the growing importance of geospatial data, its analysis including semantic segmentation becomes an increasingly popular task in computer vision today. Convolutional neural networks are powerful visual models that yield hierarchies of features and practitioners widely use them to process remote sensing data. When performing remote sensing image segmentation, multiple instances of one class with precisely defined boundaries are often the case, and it is crucial to extract those boundaries accurately. The accuracy of segments boundaries delineation influences the quality of the whole segmented areas explicitly. However, widely-used segmentation loss functions such as BCE, IoU loss or Dice loss do not penalize misalignment of boundaries sufficiently. In this paper, we propose a novel loss function, namely a differentiable surrogate of a metric accounting accuracy of boundary detection. We can use the loss function with any neural network for binary segmentation. We performed validation of our loss function with various modifications of UNet on a synthetic dataset, as well as using real-world data (ISPRS Potsdam, INRIA AIL). Trained with the proposed loss function, models outperform baseline methods in terms of IoU score.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07852](http://arxiv.org/abs/1905.07852)

##### PDF
[http://arxiv.org/pdf/1905.07852](http://arxiv.org/pdf/1905.07852)

