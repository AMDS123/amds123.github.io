---
layout: post
title: "Complex-valued neural networks for machine learning on non-stationary physical data"
date: 2019-05-29 10:47:42
categories: arXiv_CV
tags: arXiv_CV CNN Inference Deep_Learning
author: Jesper S&#xf6;ren Dramsch, Mikael L&#xfc;thje, Anders Nymark Christensen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has become an area of interest in most scientific areas, including physical sciences. Modern networks apply real-valued transformations on the data. Particularly, convolutions in convolutional neural networks discard phase information entirely. Many deterministic signals, such as seismic data or electrical signals, contain significant information in the phase of the signal. We explore complex-valued deep convolutional networks to leverage non-linear feature maps. Seismic data commonly has a lowcut filter applied, to attenuate noise from ocean waves and similar long wavelength contributions. Discarding the phase information leads to low-frequency aliasing analogous to the Nyquist-Shannon theorem for high frequencies. In non-stationary data, the phase content can stabilize training and improve the generalizability of neural networks. While it has been shown that phase content can be restored in deep neural networks, we show how including phase information in feature maps improves both training and inference from deterministic physical data. Furthermore, we show that the reduction of parameters in a complex network results in training on a smaller dataset without overfitting, in comparison to a real-valued network with the same performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12321](http://arxiv.org/abs/1905.12321)

##### PDF
[http://arxiv.org/pdf/1905.12321](http://arxiv.org/pdf/1905.12321)

