---
layout: post
title: "SurReal: Fr'echet Mean and Distance Transform for Complex-Valued Deep Learning"
date: 2019-06-24 16:12:31
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning
author: Rudrasis Chakraborty, Jiayun Wang, Stella X. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a novel deep learning architecture for naturally complex-valued data, which is often subject to complex scaling ambiguity. We treat each sample as a field in the space of complex numbers. With the polar form of a complex-valued number, the general group that acts in this space is the product of planar rotation and non-zero scaling. This perspective allows us to develop not only a novel convolution operator using weighted Fr\'echet mean (wFM) on a Riemannian manifold, but also a novel fully connected layer operator using the distance to the wFM, with natural equivariant properties to non-zero scaling and planar rotation for the former and invariance properties for the latter. 
 Compared to the baseline approach of learning real-valued neural network models on the two-channel real-valued representation of complex-valued data, our method achieves surreal performance on two publicly available complex-valued datasets: MSTAR on SAR images and RadioML on radio frequency signals. On MSTAR, at 8% of the baseline model size and with fewer than 45,000 parameters, our model improves the target classification accuracy from 94% to 98% on this highly imbalanced dataset. On RadioML, our model achieves comparable RF modulation classification accuracy at 10% of the baseline model size.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10048](http://arxiv.org/abs/1906.10048)

##### PDF
[http://arxiv.org/pdf/1906.10048](http://arxiv.org/pdf/1906.10048)

