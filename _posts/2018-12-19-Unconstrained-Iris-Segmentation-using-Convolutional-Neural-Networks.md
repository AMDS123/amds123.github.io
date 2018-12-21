---
layout: post
title: "Unconstrained Iris Segmentation using Convolutional Neural Networks"
date: 2018-12-19 21:10:08
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Recognition
author: Sohaib Ahmad, Benjamin Fuller
mathjax: true
---

* content
{:toc}

##### Abstract
The extraction of consistent and identifiable features from an image of the human iris is known as iris recognition. Identifying which pixels belong to the iris, known as segmentation, is the first stage of iris recognition. Errors in segmentation propagate to later stages. Current segmentation approaches are tuned to specific environments. We propose using a convolution neural network for iris segmentation. Our algorithm is accurate when trained in a single environment and tested in multiple environments. Our network builds on the Mask R-CNN framework (He et al., ICCV 2017). Our approach segments faster than previous approaches including the Mask R-CNN network. Our network is accurate when trained on a single environment and tested with a different sensors (either visible light or near-infrared). Its accuracy degrades when trained with a visible light sensor and tested with a near-infrared sensor (and vice versa). A small amount of retraining of the visible light model (using a few samples from a near-infrared dataset) yields a tuned network accurate in both settings. For training and testing, this work uses the Casia v4 Interval, Notre Dame 0405, Ubiris v2, and IITD datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.08245](https://arxiv.org/abs/1812.08245)

##### PDF
[https://arxiv.org/pdf/1812.08245](https://arxiv.org/pdf/1812.08245)

