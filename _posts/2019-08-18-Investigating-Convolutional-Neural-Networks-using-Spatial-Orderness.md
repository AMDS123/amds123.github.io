---
layout: post
title: "Investigating Convolutional Neural Networks using Spatial Orderness"
date: 2019-08-18 10:05:24
categories: arXiv_CV
tags: arXiv_CV CNN Classification Relation
author: Rohan Ghosh, Anupam K. Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNN) have been pivotal to the success of many state-of-the-art classification problems, in a wide variety of domains (for e.g. vision, speech, graphs and medical imaging). A commonality within those domains is the presence of hierarchical, spatially agglomerative local-to-global interactions within the data. For two-dimensional images, such interactions may induce an a priori relationship between the pixel data and the underlying spatial ordering of the pixels. For instance in natural images, neighboring pixels are more likely contain similar values than non-neighboring pixels which are further apart. To that end, we propose a statistical metric called spatial orderness, which quantifies the extent to which the input data (2D) obeys the underlying spatial ordering at various scales. In our experiments, we mainly find that adding convolutional layers to a CNN could be counterproductive for data bereft of spatial order at higher scales. We also observe, quite counter-intuitively, that the spatial orderness of CNN feature maps show a synchronized increase during the intial stages of training, and validation performance only improves after spatial orderness of feature maps start decreasing. Lastly, we present a theoretical analysis (and empirical validation) of the spatial orderness of network weights, where we find that using smaller kernel sizes leads to kernels of greater spatial orderness and vice-versa.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06416](http://arxiv.org/abs/1908.06416)

##### PDF
[http://arxiv.org/pdf/1908.06416](http://arxiv.org/pdf/1908.06416)

