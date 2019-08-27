---
layout: post
title: "Don't ignore Dropout in Fully Convolutional Networks"
date: 2019-08-24 16:28:40
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Thomas Spilsbury, Paavo Camps
mathjax: true
---

* content
{:toc}

##### Abstract
Data for Image segmentation models can be costly to obtain due to the precision required by human annotators. We run a series of experiments showing the effect of different kinds of Dropout training on the DeepLabv3+ Image segmentation model when trained using a small dataset. We find that when appropriate forms of Dropout are applied in the right place in the model architecture that non-insignificant improvement in Mean Intersection over Union (mIoU) score can be observed. In our best case, we find that applying Dropout scheduling in conjunction with SpatialDropout improves baseline mIoU from 0.49 to 0.59. This result shows that even where a model architecture makes extensive use of Batch Normalization, Dropout can still be an effective way of improving performance in low data situations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09162](http://arxiv.org/abs/1908.09162)

##### PDF
[http://arxiv.org/pdf/1908.09162](http://arxiv.org/pdf/1908.09162)

